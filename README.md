## Reading Material

A collection of resources that I found interesting and useful across various domains.

> [The Tao of Programming](http://www.mit.edu/~xela/tao.html)

> [Rob Pike's 5 Rules of Programming](http://users.ece.utexas.edu/~adnan/pike.html)

## Contents

- [Go](collection/go.md#go)
  - [Pilot Run](collection/go.md#go-pilot-run)
  - [Concepts](collection/go.md#concepts)
    - [Concurrency](collection/go.md#concurrency)
    - [Profiling](collection/go.md#profiling-mag)
  - [Go Internals](collection/go.md#go-internals)
    - [Scheduler](collection/go.md#scheduler)
    - [Garbage Collector](collection/go.md#garbage-collector)
    - [Compiler](collection/go.md#compiler)
    - [Memory](collection/go.md#memory)
  - [Networking with Go](collection/go.md#networking-with-go)
- [Containers](collection/containers.md#containers)
  - [Docker](collection/containers.md#docker)
  - [Kubernetes](collection/containers.md#kubernetes-construction)
- [Data Structures and Algorithms](collection/ds-algo.md#data-structures-and-algorithms)
  - [Algorithms](collection/ds-algo.md#algorithms)
  - [Data Structures](collection/ds-algo.md#data-structures)
    - [Advanced Data Structures](collection/ds-algo.md#advanced-data-structures)
      - [Bloom filter](collection/ds-algo.md#bloom-filter)
- [Internet](collection/internet.md#internet)
  - [Webservers](collection/internet.md#webservers)
  - [Nginx](collection/internet.md#nginx)
  - [Web Caching](collection/internet.md#web-caching)
  - [Protocols](collection/internet.md#protocols)
    - [HTTP(S)](collection/internet.md#https)
      - [HTTP/2](collection/internet.md#http2)
      - [HTTP/3](collection/internet.md#http3)
    - [TCP/UDP](collection/internet.md#tcpudp)
    - [DNS](collection/internet.md#dns)
    - [BGP](collection/internet.md#bgp)
    - [Websockets](collection/internet.md#websockets)
    - [WebRTC](collection/internet.md#webrtc)
  - [Load Balancing](collection/internet.md#load-balancing)
  - [Books](collection/internet.md#networking-books-books)
- [Git](collection/git.md#git)
- [Linux](collection/linux.md#linux)
  - [Linux](collection/linux.md#linux)
  - [SSH](collection/linux.md#ssh)
  - [Linux Security](collection/linux.md#linux-security)
  - [Bash](collection/linux.md#bash)
  - [Books](collection/linux.md#linux-books)
- [OS Dev](collection/os-dev.md#os-dev)
- [C](collection/c.md#c)
- [Ruby](/collection/ruby.md#ruby)
  - [Rails](collection/ruby.md#rails)
- [Python](/collection/python.md)
- [Haskell](collection/haskell.md#haskell)
- [Javascript](collection/js.md#js)
- [Rust](collection/rust.md#rust)
- [Databases](collection/databases.md#database)
  - [PostgreSQL](collection/databases.md#postgresql)
  - [MySQL](collection/databases.md#mysql)
  - [Sharding](collection/databases.md#sharding)
  - [ClickHouse](collection/databases.md#clickhouse)
  - [Elasticsearch](collection/databases.md#elasticsearch)
  - [Papers](collection/databases.md#papers)
  - [Books](collection/databases.md#books)
- [Tor](collection/tor.md#tor)
- [Functional Programming](collection/functional-programming.md#functional-programming)
- [OAuth](collection/oauth.md#oauth)
- [Regex](collection/regex.md#regex)
- [Distributed Systems](collection/distributed-systems.md#distributed-systems)
  - [Book](collection/distributed-systems.md#books)
- [Kafka](collection/kafka.md#kafka)
- [Spark](collection/spark.md#spark)
- [Monitoring](collection/monitoring.md#monitoring)
- [System Design](collection/system-design.md#system-design)
  - [Guides](collection/system-design.md#guides)
  - [Systems](collection/system-design.md#systems)
  - [Scalability](collection/system-design.md#scalability)
  - [Event driven Architecture](collection/system-design.md#event-driven-architecture)
  - [AWS](collection/system-design.md#aws)
  - [Netflix](collection/system-design.md#netflix)
  - [Design Patterns](collection/system-design.md#design-patterns)
  - [Books](collection/system-design.md#books)
  - [Papers](collection/system-design.md#papers)
- [Privacy](collection/privacy.md#privacy)
- [Security](collection/security.md#security)
  - [Tools](collection/security.md#tools)
  - [Attacks](collection/security.md#attacks)
  - [Guides](collection/security.md#guides)
  - [Games and CTF's](collection/security.md#games-and-ctfs)
  - [Crypto](collection/security.md#crypto)
  - [Papers](collection/security.md#security-papers)
- [x vs y :hocho:](collection/x-vs-y.md#x-vs-y-hocho)
- [Useful Command Line Tools](#useful-command-line-tools)
- [Blogs](#blogs)
- [More](#more)
- [Fun](#fun)
- [More Books](#more-books)
  - [Software Development](#software-development)
  - [Lisp](#lisp)
  - [Random](#random)
- [Courses](#courses)
- [Papers](#papers)
- [Notes](Notes) [WIP]

## Legend

You might see some emojis (:sparkles:, :construction: etc) crawling all over this collection.

| emoji            | meaning                                       |
| ---------------- | --------------------------------------------- |
| :sparkles:       | More the number, the more I liked the blog :3 |
| :zap:            | super duper awesome blog                      |
| :construction:   | Pending learning on this :(                   |
| :tv:             | It's video!                                   |
| :books:          | It's a book!                                  |
| :page_with_curl: | It's a white paper!                           |
| :wrench:         | It's Debugging related                        |
| :hocho:          | faceoff                                       |
| :file_folder:    | It's a list                                   |


## Useful Command Line Tools

- [tldr](https://github.com/tldr-pages/tldr)
- [Rofi: A window switcher, application launcher and dmenu replacement](https://github.com/DaveDavenport/rofi)
- [fd: A simple, fast and user-friendly alternative to find](https://github.com/sharkdp/fd)
- [SCM breeze: Adds numbered shortcuts to the output git status, and much more ](https://github.com/scmbreeze/scm_breeze)
- [Pass: Simple password manager using gpg and ordinary unix directories](https://www.passwordstore.org/)
- [peerflix](https://github.com/mafintosh/peerflix)
- [kaf: Modern CLI for Apache Kafka](https://github.com/birdayz/kaf)
- [curl statistics made simple](https://github.com/reorx/httpstat)
- [mkcert](https://github.com/FiloSottile/mkcert)
- [sshuttle - Transparent proxy server that works as a poor man's VPN.](https://github.com/sshuttle/sshuttle)
- [jq](https://stedolan.github.io/jq/)

## Blogs

- http://arjunsreedharan.org/
- https://jvns.ca/
- https://githubengineering.com/
- http://nullprogram.com/index/
- https://zwischenzugs.com/
- https://mkdev.me/en/posts
- https://blog.cloudflare.com/
- http://prog21.dadgum.com/
- https://increment.com/programming-languages/ :sparkles:
- https://blog.filippo.io/
- http://highscalability.com
- https://notes.shichao.io/
- https://blog.acolyer.org/ - If you are into research papers
- https://lwn.net/
- https://queue.acm.org/
- https://www.the-paper-trail.org/
- https://overreacted.io/
- https://robertheaton.com/
- https://www.mnot.net/blog/
- https://systemoverlord.com/
- https://blog.jessfraz.com/
- https://www.hackinglinuxexposed.com/articles/
- https://rpis.ec/blog/
- https://dave.cheney.net/ - Mostly Golang related
- http://www.brendangregg.com/
- https://medium.com/@blanchon.vincent :sparkles:
- https://sysadvent.blogspot.com/
- [A handbook for making programming languages](http://craftinginterpreters.com/)
- https://codewithoutrules.com/
- https://microservices.io/index.html :sparkles:
- https://engineering.fb.com/
- [Cryptography Services Archives](https://cryptoservices.github.io/archives/) :lock:
- https://timilearning.com/ :construction:
- https://aws.amazon.com/builders-library/ - How Amazon builds and operates software
- https://rhinosecuritylabs.com/blog/?category=aws
- https://how.complexsystems.fail/
- https://ops.tips
- https://blog.cleancoder.com/
- https://www.akamai.com/glossary
- https://arpitbhayani.me/knowledge-base

## More

- [A list of everything that could go in the \<head\> of your document](https://github.com/joshbuchea/HEAD)
- [Constructors Considered Mildly Confusing](http://zeekat.nl/articles/constructors-considered-mildly-confusing.html)
- [Clojure - the perfect language to expand your brain?](http://eli.thegreenplace.net/2017/clojure-the-perfect-language-to-expand-your-brain/)
- [The Forgotten History of OOP](https://medium.com/javascript-scene/the-forgotten-history-of-oop-88d71b9b2d9f)
- [A better zip bomb](https://www.bamsoftware.com/hacks/zipbomb/)
- [Race Condition vs. Data Race](https://blog.regehr.org/archives/490) :sparkles:
- [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/) :sparkles: :zap:
- [A byte’s not 8 bits.](https://burstingdynamics.wordpress.com/2015/11/10/a-byte-is-not-8-bits/) :sparkles:
- [Epigrams in programming](http://www.cs.yale.edu/homes/perlis-alan/quotes.html)
- [Why stack grows down](https://gist.github.com/cpq/8598782)
- [Queryparser, an Open Source Tool for Parsing and Analyzing SQL](https://eng.uber.com/queryparser/)
- Null References: The Billion Dollar Mistake - Tony Hoare :tv:
- [Mathematical attack on RSA](https://www.nku.edu/~christensen/Mathematical%20attack%20on%20RSA.pdf)
- [Essays on programming I think about a lot](https://www.benkuhn.net/progessays/) :sparkles:
- [lzop vs compress vs gzip vs bzip2 vs lzma vs lzma2/xz benchmark, reloaded](https://stephane.lesimple.fr/blog/lzop-vs-compress-vs-gzip-vs-bzip2-vs-lzma-vs-lzma2xz-benchmark-reloaded/)
- [Andrei Pangin - Everything you wanted to know about Stack Traces and Heap Dumps](https://www.youtube.com/watch?v=FTsAXJdrJbI&t=1s) :tv:
- [The Hitchhiker’s Guide to Compression](https://go-compression.github.io/) :construction:
- [Parsing Algorithms](http://dmitrysoshnikov.com/courses/parsing-algorithms/) :construction:
- [The Differences Between Interpreter and Compiler Explained](https://thevaluable.dev/difference-between-compiler-interpreter/)
- [DevOps, SRE, and Platform Engineering](https://iximiuz.com/en/posts/devops-sre-and-platform-engineering/)
- [Upsert in SQL](https://antonz.org/sql-upsert)
- [Branch predictor: How many "if"s are too many? Including x86 and M1 benchmarks!](https://blog.cloudflare.com/branch-predictor)

## Fun

- https://turnoff.us
- https://xkcd.com
- https://impurepics.com/
- https://www.commitstrip.com
- [If Programming languages were harry potter characters](http://heeris.id.au/2014/if-programming-languages-were-harry-potter-characters/)
- [Git Koans](https://stevelosh.com/blog/2013/04/git-koans/)
- [Vim Kōans](https://sanctum.geek.nz/arabesque/vim-koans/)
- [The Dharma of Vi](https://blog.samwhited.com/2015/04/the-dharma-of-vi/)
- https://suricrasia.online/iceberg/
- https://goomics.net/

## More Books

### Software Development

- [Coders at Work](https://www.amazon.com/gp/product/1430219483)
- [The Pragmatic Programmer](https://www.amazon.com/Pragmatic-Programmer-Journeyman-Master/dp/020161622X) :sparkles:
- [Hackers: Heroes of the Computer Revolution](https://www.amazon.com/Hackers-Computer-Revolution-Steven-Levy/dp/1449388396)
- [The Mythical Man-Month](http://www.amazon.in/Mythical-Man-Month-Software-Engineering-Anniversary/dp/0201835959)
- [The Joy of Software Development](https://josd.captnemo.in/content/)

### Random

- [A handbook for making programming languages](http://www.craftinginterpreters.com/contents.html)
- [An Illustrated Book of Bad Arguments](https://bookofbadarguments.com/)
- [An illustrated introduction to computational thinking](https://bookofbadchoices.com/index.html#page/3)
- [Atomic Design by Brad Frost](http://atomicdesign.bradfrost.com/)
- https://begriffs.com/posts/2017-04-13-longterm-computing-reading.html
- [SRE Books](https://landing.google.com/sre/books/)

## Courses

- [Operating System Engineering](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-828-operating-system-engineering-fall-2012/)
- [Introduction to Algorithms](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/index.htm)
- [CS 140: Operating Systems](http://web.stanford.edu/~ouster/cgi-bin/cs140-spring14/lectures.php)
- [Awesome Courses](https://github.com/prakhar1989/awesome-courses)

## Papers

- [How Professional Hackers Understand Protected Code while Performing Attack Tasks](https://pdfs.semanticscholar.org/4bd1/2a9823b55d29a0d75c9ea9c8cd08b6fdca3e.pdf)
- [Papers We Love](https://github.com/papers-we-love) :sparkles:
- [Communicating Sequential Processes](https://spinroot.com/courses/summer/Papers/hoare_1978.pdf) :sparkles:
- [Reflections on Trusting Trust](https://users.ece.cmu.edu/~ganger/712.fall02/papers/p761-thompson.pdf)
- [Hints on programming language design](http://flint.cs.yale.edu/cs428/doc/HintsPL.pdf)
- [The Fault Tolerance of Botnets](https://www.dropbox.com/s/rvk6ybbl85zce00/The%20Fault%20Tolerance%20of%20Botnets.pdf?dl=0)
- [Paradigm Shift in Software Development](https://www.dropbox.com/s/db2tbau0jdv9pym/Paradigm%20Exercise.pdf?dl=0)
- [Cloak of Visibility](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45365.pdf)
- [The Impact of Thread-Per-Core Architecture on Application Tail Latency](https://penberg.org/papers/tpc-ancs19.pdf)
- [Zanzibar: Google’s Consistent, Global Authorization System](https://www.usenix.org/system/files/atc19-pang.pdf)
