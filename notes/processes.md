# Processes

## Zombie Process \(or Defunct Process\)

A process which has finished the execution but still has entry in the process table to report to its parent process is known as a zombie process. A child process always first becomes a zombie before being removed from the process table. The parent process reads the exit status of the child process which reaps off the child process entry from the process table.

### Why do we need to prevent the creation of Zombie process?

There is one process table per system. The size of the process table is finite. If too many zombie processes are generated, then the process table will be full. That is, the system will not be able to generate any new process, then the system will come to a standstill. Hence, we need to prevent the creation of zombie processes.

### Prevention of Zombie processes

* Using wait\(\) system call
* By ignoring the SIGCHLD signal
* By using a signal handler
* Double forking
  * The parent calls wait and creates a child. The child creates a grandchild and exits.
  * The grandchild executes its instruction\(task\) and eventually it terminates. As the child has already exited, the grandchild will be taken care by init process.
  * Init collect the exit status of grandchild. Hence the grandchild is not a zombie.

## Orphan Process

A process whose parent process no more exists i.e. either finished or terminated without waiting for its child process to terminate is called an orphan process. However, the orphan process is soon adopted by init process, once its parent process dies.

## Process States

* Created-Process is newly created by system call, is not ready to run
* User running-Process is running in user mode which means it is a user process.
* Kernel Running-Indicates process is a kernel process running in kernel mode.
* Zombie- Process does not exist/ is terminated.
* Preempted- When process runs from kernel to user mode, it is said to be preempted.
* Ready to run in memory- It indicated that process has reached a state where it is ready to run in memory and is waiting for kernel to schedule it.
* Ready to run, swapped– Process is ready to run but no empty main memory is present
* Sleep, swapped- Process has been swapped to secondary storage and is at a blocked state.
* Asleep in memory- Process is in memory\(not swapped to secondary storage\) but is in blocked state.

## Process Transition

* User-running: Process is in user-running.
* Kernel-running: Process is allocated to kernel and hence, is in kernel mode.
* Ready to run in memory: Further, after processing in main memory process is rescheduled to the Kernel.i.e.The process is not executing but is ready to run as soon as the kernel schedules it.
* Asleep in memory: Process is sleeping but resides in main memory. It is waiting for the task to begin.
* Ready to run, swapped: Process is ready to run and be swapped by the processor into main memory, thereby allowing kernel to schedule it for execution.
* Sleep, Swapped: Process is in sleep state in secondary memory, making space for execution of other processes in main memory. It may resume once the - task is fulfilled.
* Preempted: Kernel preempts an on-going process for allocation of another process, while the first process is moving from kernel to user mode.
* Created: Process is newly created but not running. This is the start state for all processes.
* Zombie: Process has been executed thoroughly and exit call has been enabled.

The process, thereby, no longer exists. But, it stores a statistical record for the process. This is the final state of all processes.

