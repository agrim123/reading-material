## Go

> [Go FAQ](https://golang.org/doc/faq)

### Go Pilot run

- [x] [Tour of Go](https://tour.golang.org/)
- [ ] [Go by example](https://gobyexample.com/)
- [ ] [Effective Go](https://golang.org/doc/effective_go.html)
- [ ] [Golang channels tutorial](http://guzalexander.com/2013/12/06/golang-channels-tutorial.html)
- [ ] [Resources for new Go programmers](https://dave.cheney.net/resources-for-new-go-programmers)
- [ ] [The zero value](https://golang.org/ref/spec#The_zero_value)
- [ ] [Darker Corners of Go](https://rytisbiel.com/2021/03/06/darker-corners-of-go/) :sparkles:
- [ ] [Know Your Nil](http://jeremymikkola.com/posts/2017_03_29_know_your_nil.html)

### Concepts

> Do not communicate by sharing memory; instead, share memory by communicating.

#### Concurrency

> Concurrency is not Parallelism

- [Go Concurrency from the Ground Up](https://www.doxsey.net/blog/go-concurrency-from-the-ground-up)
- [How Goroutines Work](https://blog.nindalf.com/posts/how-goroutines-work/) :sparkles:
- [Concurrency is not Parallelism](https://talks.golang.org/2012/waza.slide) :sparkles: :zap:
- [Concurrency in golang and a mini Load-balancer](https://gist.github.com/rushilgupta/228dfdf379121cb9426d5e90d34c5b96)
- [Channels in Go](https://go101.org/article/channel.html)
- [Go Concurrency Patterns](https://talks.golang.org/2012/concurrency.slide)
- [Concurrent programming, with examples](https://begriffs.com/posts/2020-03-23-concurrent-programming.html?hn=1)
- [Slow down your code with goroutines](https://appliedgo.net/concurrencyslower/)
- [How to Gracefully Close Channels](https://go101.org/article/channel-closing.html) :sparkles:
- [Go channels on steroids](https://docs.google.com/document/d/1yIAYmbvL3JxOKOjuCyon7JhW4cSv1wy5hC0ApeGMV9s/pub)
- [Visualizing Concurrency in Go](http://divan.github.io/posts/go_concurrency_visualize/)
- [Go’s Extended Concurrency: Semaphores (Part 1)](https://medium.com/@deckarep/gos-extended-concurrency-semaphores-part-1-5eeabfa351ce)
- [Channel Axioms](https://dave.cheney.net/2014/03/19/channel-axioms) :sparkles:
- [Go Concurrency Patterns: Pipelines and cancellation](https://blog.golang.org/pipelines)
- [Using contexts to avoid leaking goroutines](https://rakyll.org/leakingctx/)
- [Why is a Goroutine’s stack infinite ?](https://dave.cheney.net/2013/06/02/why-is-a-goroutines-stack-infinite)
- [Advanced Go Concurrency Patterns](https://talks.golang.org/2013/advconc.slide#1)
- [sync.RWMutex](https://medium.com/golangspec/sync-rwmutex-ca6c6c3208a0)

#### Profiling :mag:

> [Go Diagnostics](https://golang.org/doc/diagnostics.html) :wrench:

- [Profiling Go](http://www.integralist.co.uk/posts/profiling-go/)
- [Profiling and optimizing Go web applications](https://artem.krylysov.com/blog/2017/03/13/profiling-and-optimizing-go-web-applications/)
- [Profiling Go Programs](https://blog.golang.org/profiling-go-programs)
- [pprof](https://jvns.ca/blog/2017/09/24/profiling-go-with-pprof/)
- [go tool trace](https://making.pusher.com/go-tool-trace/)
- [Various go profiling methods](https://github.com/DataDog/go-profiler-notes/)
- [pprof++: A Go Profiler with Hardware Performance Monitoring](https://eng.uber.com/pprof-go-profiler/)

### Go Internals

> [Everything about Go: internals, concurrency, compiler, or packages available in the Go community.](https://medium.com/a-journey-with-go)

- [Go Internals](https://github.com/teh-cmc/go-internals)
- [How does the go build command work?](https://dave.cheney.net/2013/10/15/how-does-the-go-build-command-work)
- [Introducing the Go Race Detector](https://blog.golang.org/race-detector)
- String interning in Go
  - [String interning in Go](https://artem.krylysov.com/blog/2018/12/12/string-interning-in-go/)
  - [Interning strings in Go](https://commaok.xyz/post/intern-strings/)
- [Arrays, slices (and strings): The mechanics of 'append'](https://blog.golang.org/slices)
- [Go’s hidden #pragmas](https://dave.cheney.net/2018/01/08/gos-hidden-pragmas)
- [Detecting Race Conditions With Go](https://www.ardanlabs.com/blog/2013/09/detecting-race-conditions-with-go.html)
- https://vitalcs.substack.com/p/goroutines-under-the-hood

#### Scheduler

- [The Go scheduler](https://morsmachine.dk/go-scheduler) :sparkles:
- [Scheduler Tracing In Go](https://www.ardanlabs.com/blog/2015/02/scheduler-tracing-in-go.html)
- [Analysis of the Go runtime scheduler](http://www.cs.columbia.edu/~aho/cs6998/reports/12-12-11_DeshpandeSponslerWeiss_GO.pdf) :page_with_curl:
- [Go's work-stealing scheduler](https://rakyll.org/scheduler/)

#### Garbage Collector

- [Golang’s Real-time GC in Theory and Practice](https://making.pusher.com/golangs-real-time-gc-in-theory-and-practice/) :sparkles:
- [Getting to Go: The Journey of Go's Garbage Collector](https://blog.golang.org/ismmkeynote)
- [runtime: Large maps cause significant GC pauses](https://github.com/golang/go/issues/9477)
- [How We Saved 70K Cores Across 30 Mission-Critical Services (Large-Scale, Semi-Automated Go GC Tuning @Uber)](https://eng.uber.com/how-we-saved-70k-cores-across-30-mission-critical-services/)
- [A Guide to the Go Garbage Collector](https://tip.golang.org/doc/gc-guide)
- [An attempt at visualizing the Go GC](https://www.aadhav.me/posts/visualizing-the-go-gc/)
- [Avoiding high GC overhead with large heaps](https://blog.gopheracademy.com/advent-2018/avoid-gc-overhead-large-heaps/)

#### Compiler

- [Go compiler internals](https://eli.thegreenplace.net/2019/go-compiler-internals-adding-a-new-statement-to-go-part-1/)
- [Go & Assembly](http://www.doxsey.net/blog/go-and-assembly)
- [Dissecting Go Binaries](https://www.grant.pizza/dissecting-go-binaries/)

#### Memory

- [The Go Memory Model](https://golang.org/ref/mem) :sparkles:
- [Go memory ballast: How I learnt to stop worrying and love the heap](https://blog.twitch.tv/en/2019/04/10/go-memory-ballast-how-i-learnt-to-stop-worrying-and-love-the-heap-26c2462549a2/)
- [Memory Leaking Scenarios](https://go101.org/article/memory-leaking.html)
- [Memory Order Guarantees in Go](https://go101.org/article/memory-model.html)
- [GO MEMORY MANAGEMENT](https://povilasv.me/go-memory-management/)
- [Contiguous stacks in Go](https://agis.io/post/contiguous-stacks-golang/)
- [Memory Optimizations for Go Systems](https://medium.com/swlh/memory-optimizations-for-go-systems-48d95cf64a13)
- [A few bytes here, a few there, pretty soon you’re talking real memory](https://dave.cheney.net/2021/01/05/a-few-bytes-here-a-few-there-pretty-soon-youre-talking-real-memory) :construction:
- [Golang escape analysis](http://www.agardner.me/golang/garbage/collection/gc/escape/analysis/2015/10/18/go-escape-analysis.html) :construction:
- [Are large slices more expensive than smaller ones?](https://dave.cheney.net/2020/03/01/are-large-slices-more-expensive-than-smaller-ones) :mag:
- [There is no pass-by-reference in Go](https://dave.cheney.net/2017/04/29/there-is-no-pass-by-reference-in-go)
- [Allocation efficiency in high-performance Go services](https://segment.com/blog/allocation-efficiency-in-high-performance-go-services/)

### Networking with Go

- [Network Programming with Go](http://tumregels.github.io/Network-Programming-with-Go/)
- [A Million WebSockets and Go](https://medium.freecodecamp.org/million-websockets-and-go-cc58418460bb)
- [TCP/IP Networking in Go](https://appliedgo.net/networking/)
- [An Implementation and Analysis of a Kernel Network Stack in Go with the CSP Style](https://arxiv.org/abs/1603.05636) :page_with_curl:
- [Gotchas in the Go Network Packages Defaults](https://martin.baillie.id/wrote/gotchas-in-the-go-network-packages-defaults/) :sparkles:

### More

- [Interfaces in Go](http://jordanorelli.com/post/32665860244/how-to-use-interfaces-in-go)
- [Go Data Structures: Interfaces](https://research.swtch.com/interfaces)
- [Applied Go](https://appliedgo.net/)
- [Golang Has Generics](http://blog.jonathanoliver.com/golang-has-generics/)
- [Go-tcha: When nil != nil](https://dev.to/pauljlucas/go-tcha-when-nil--nil-hic)
- [SOLID Go Design](https://dave.cheney.net/2016/08/20/solid-go-design)
- [Simple techniques to optimise Go programs](https://stephen.sh/posts/quick-go-performance-improvements)
- [A whirlwind tour of Go’s runtime environment variables](https://dave.cheney.net/tag/godebug)
- [How we optimized our DNS server using go tools](https://medium.com/@arash.cordi/how-we-optimized-our-dns-server-using-go-tools-d753e1a5e709) :sparkles:
- [Optimizing M3: How Uber Halved Our Metrics Ingestion Latency by (Briefly) Forking the Go Compiler](https://eng.uber.com/optimizing-m3/) :sparkles:
- [Writing a very fast cache service with millions of entries in Go](https://allegro.tech/2016/03/writing-fast-cache-service-in-go.html)
- [Go, without package scoped variables](https://dave.cheney.net/2017/06/11/go-without-package-scoped-variables)
- [How to generate a random string of a fixed length in Go?](https://stackoverflow.com/a/31832326)
- [Building efficient statsd library in Go](https://talks.godoc.org/github.com/smira/gopherconru2018/go-statsd.slide#1)
- [Gopher Puzzlers](https://talks.godoc.org/github.com/davecheney/presentations/gopher-puzzlers.slide#1) :zap:
- [Visually Understanding Worker Pool](https://medium.com/coinmonks/visually-understanding-worker-pool-48a83b7fc1f5)
- [The Case For A Go Worker Pool](https://brandur.org/go-whttps://www.ardanlabs.com/blog/2015/02/scheduler-tracing-in-go.htmlorker-pool)
- [Go at Google: Language Design in the Service of Software Engineering](https://talks.golang.org/2012/splash.article)
- [Life of an HTTP request in a Go server](https://eli.thegreenplace.net/2021/life-of-an-http-request-in-a-go-server/)
- [Send data from file without loading into memory](https://stackoverflow.com/questions/42261421/send-os-stdin-via-http-post-without-loading-file-into-memory)
- [Data Race Patterns in Go](https://eng.uber.com/data-race-patterns-in-go/)
- [Optimizing Large File Transfers in Linux with Go - An Exploration of TCP and Syscall](https://dev.to/douglasmakey/optimizing-large-file-transfers-in-linux-with-go-an-exploration-of-tcp-and-syscall-15eo)
- [Pardon the Interruption: Loop Preemption in Go 1.14](https://www.youtube.com/watch?v=1I1WmeSjRSw)
- [Mastering WebSockets With Go](https://programmingpercy.tech/blog/mastering-websockets-with-go/)
- [proposal: arena: new package providing memory arenas](https://github.com/golang/go/issues/51317)
- [A Tale of Two `rand`s](https://blog.gopheracademy.com/advent-2017/a-tale-of-two-rands/)
