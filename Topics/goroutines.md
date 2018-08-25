## Go

- Go is a concurrent open source programming language developed at Google.
- Combines native compilation and static types with a lightweight dynamic feel.
- Features
    - Native code generation (compiled)
    - Statically typed
    - Composition via interfaces
    - Memory safe
    - Garbage collected
    - Native concurrency support
    - scalable
- Go is Object Oriented, but not in the usual way.
    - no classes (methods may be declared on any type)
    - no subtype inheritance
    - interfaces are satisfied implicitly (structural typing)


## Goroutines

- Independently executing function, launched by `go` statement.
- has it's own call stack, which grows or shrinks as reqd.
- Very cheap. (practically running thousands of goroutines.) (or lightweight threads)
- NOT a thread. (might be only one thread in a program with thousands of goroutines)
- goroutines are multiplexed dynamically onto threads as needed to keep all the goroutines running.
- communicate via channels

A **channel** provides a connection between goroutines, allowing them to communicate.

## The Go Approach

> Don't communicate by sharing memory, share memory by communicating

## Channels

- a typed conduit that may be synchronous (unbuffered) or asynchronous (buffered)
- serve to synchronize execution of concurrently running functions and to provide a mechanism for their communication by passing a value of a specified type
- first class values, can be used anywhere like other values: as struct elements, function arguments, function returning values and even like a type for another channel

## Refereances

- https://talks.golang.org/
- https://talks.golang.org/2012/goforc.slide
- https://talks.golang.org/2012/concurrency.slide
- https://talks.golang.org/2012/10things.slide
 
