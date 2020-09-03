# Reading Material

A collection of resources that I found useful and interesting across various domains.

> [The Tao of Programming](http://www.mit.edu/~xela/tao.html)

> [Rob Pike's 5 Rules of Programming](http://users.ece.utexas.edu/~adnan/pike.html)

## Contents

- [Javascript](#js)
    - [Pilot Run](#pilot-run)
    - [Advanced Concepts](#advanced-concepts)
    - [Node.js](#nodejs)
    - [React, Redux](#react-redux)
    - [v8](#v8)
    - [Books](#js-books)
- [Security](#security)
    - [Tools](#tools)
    - [Attacks](#attacks)
    - [Guides](#guides)
    - [Games and CTF's](#games-and-ctfs)
    - [Crypto](#crypto)
    - [Papers](#security-papers)
- [Docker](#docker)
- [Algorithms](#algorithms)
- [Data Structures](#data-structures)
    - [Advanced Data Structures](#advanced-data-structures)
        - [Bloom filter](#bloom-filter)
- [Internet](#internet)
    - [Webservers](#webservers)
    - [Protocols](#protocols)
        - [HTTP(S)](#https)
        - [TCP/UDP](#tcpudp)
        - [DHCP](#dhcp)
        - [DNS](#dns)
        - [BGP](#bgp)
    - [Load Balancing](#load-balancing)
    - [Books](#networking-books-books)
    - [Papers](#networking-papers-page_with_curl)
- [Git](#git)
- [Linux](#linux)
    - [Linux](#linux)
    - [Kernel](#kernel)
    - [SSH](#ssh)
    - [Linux Security](#linuxsecurity)
    - [Bash](#bash)
    - [Books](#linux-books)
- [OS Dev](#os-dev)
- [C](#c)
- [Ruby](#ruby)
- [Rails](#rails)
- [Haskell](#haskell)
- [Go](#go)
    - [Pilot Run](#go-pilot-run)
    - [Concepts](#concepts)
        - [Concurrency](#concurrency)
        - [Profiling](#profiling)
    - [Go Internals](#go-internals)
    - [Networking with Go](#networking-with-go)
    - [Papers](#go-papers)
- [Rust](#rust)
- [Kubernetes](#kubernetes)
- [Database](#database)
- [Blockchain, Bitcoin](#blockchain-bitcoin)
- [Tor](#tor)
- [Functional Programming](#functional-programming)
- [OAuth](#oauth)
- [Regex](#regex)
- [Distributed Systems](#distributed-sytems)
- [Kafka](#kafka)
- [Spark](#spark)
- [Monitoring](#monitoring)
- [System Design](#system-design)
    - [Scalability](#scalability)
    - [Event driven Architecture](#event-driven-architecture)
    - [AWS](#aws)
    - [Netflix](#netflix)
- [Privacy](#privacy)
- [x vs y :hocho:](#x-vs-y-hocho)
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
- [Notes](/Notes) [WIP]

## Legend

You might some emojis (:sparkles:, :construction: etc) crawling all over this collection. 

| emoji  |  meaning |
| ------------ | ------------ |
| :sparkles:  | More the number, the more I liked the blog :3 |
| :zap:  | super duper awesome blog |
| :construction:  | Pending learning on this :( |
| :tv:  | It's video! |
| :books:  | It's a book! |
| :page_with_curl:  | It's a white paper! |
| :wrench:  | Debugging |
| :file_folder:  | List |
| :hocho:  | faceoff |

## JS

### Pilot Run

- [Objects in javascript](https://stackoverflow.com/questions/3691125/objects-in-javascript/3691209#3691209)
- [Two Pillars of Javascript](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3)
- [How are the Event Loop, Callback Queue, and Javascript’s single thread connected?](https://stackoverflow.com/questions/29421781/how-are-the-event-loop-callback-queue-and-javascript-s-single-thread-connected) :sparkles:
- [Philip Roberts: What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
- [Types in Javascript](https://jcemer.com/types-in-javascript-what-you-should-care.html)
- [Modern JavaScript Cheatsheet](https://github.com/mbeaudru/modern-js-cheatsheet)
- [Arrow function vs function declaration / expressions: Are they equivalent / exchangeable?](https://stackoverflow.com/a/34361380)

### Advanced Concepts

- [this in JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
- [What is a Promise?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261)
- [Lazy, composable, and modular JavaScript](https://codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript)
- [Advanced JS](http://htmldog.com/guides/javascript/advanced/)
- [The Dao of Immutability](https://medium.com/javascript-scene/the-dao-of-immutability-9f91a70c88cd)
- [Composing Software](https://medium.com/javascript-scene/composing-software-an-introduction-27b72500d6ea) :sparkles::sparkles:
- [What is the Difference Between Class and Prototypal Inheritance?](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9)
- [What is a Closure?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36)
- [Circular dependencies in JavaScript](https://medium.com/content-uneditable/circular-dependencies-in-javascript-a-k-a-coding-is-not-a-rock-paper-scissors-game-9c2a9eccd4bc)
- [Hoisting in Javascript](https://codeburst.io/hoisting-in-javascript-515c987336d3)
- [Async-Await](https://thomashunter.name/presentations/async-await-javascript-v1/)
- [Await and Async Explained with Diagrams and Examples](http://nikgrozev.com/2017/10/01/async-await/)
- [JavaScript engine fundamentals: Shapes and Inline Caches](https://mathiasbynens.be/notes/shapes-ics) :sparkles:
- [Javascript : The Curious Case of Null >= 0](https://blog.campvanilla.com/javascript-the-curious-case-of-null-0-7b131644e274)
- [How to Fix the ES6 `class` keyword](https://medium.com/javascript-scene/how-to-fix-the-es6-class-keyword-2d42bb3f4caf#.mcpw9sl95)
- [The Modern JavaScript Tutorial](https://javascript.info/)
- [Elements of JavaScript Style](https://medium.com/javascript-scene/elements-of-javascript-style-caa8821cb99f)
- [The JavaScript Encyclopedia](http://javascript.crockford.com/)
- [Javascript Debugging](https://developer.chrome.com/devtools/docs/javascript-debugging)
- [Headless Chromium](https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md)
- [Rich JavaScript Applications – the Seven Frameworks](http://blog.stevensanderson.com/2012/08/01/rich-javascript-applications-the-seven-frameworks-throne-of-js-2012/)
- [Object-oriented Programming in vanilla JavaScript](https://hackernoon.com/object-oriented-programming-in-vanilla-javascript-f3945b15f08a)
- [Essential Image Optimization](https://images.guide/) :sparkles:
- [Why does Google prepend while(1); to their JSON responses?](https://stackoverflow.com/questions/2669690/why-does-google-prepend-while1-to-their-json-responses)
- [In defense of Functional CSS](https://www.mikecr.it/ramblings/functional-css/)
- [Douglas Crockford: Really. JavaScript.](https://www.youtube.com/watch?v=lTWGoL1N-Kc) :tv:
- [Defensive JavaScript](https://www.javascriptjanuary.com/blog/defensive-javascript)
- [What is `this`? The Inner Workings of JavaScript Objects](https://medium.com/javascript-scene/what-is-this-the-inner-workings-of-javascript-objects-d397bfa0708a)
- [Responsible JavaScript](https://alistapart.com/article/responsible-javascript-part-1/)
- [Mistakes we make using JavaScript Promises](https://www.betamark.com/blog/mistakes-using-javascript-promises/)
- [Webpack How-to](https://github.com/petehunt/webpack-howto)

### Node.js

- [Getting Started with NodeJS](http://stackoverflow.com/questions/2353818/how-do-i-get-started-with-node-js)
- [Looking into assembly code of coercion](https://wanago.io/2018/04/02/1-2-3-9-looking-into-assembly-code-of-coercion/)

### React, Redux

- [Under the hood ReactJS](https://github.com/Bogdan-Lyashenko/Under-the-hood-ReactJS)
- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [React Implementation Notes](https://reactjs.org/docs/implementation-notes.html)
- [React Internals](http://www.mattgreer.org/articles/react-internals-part-one-basic-rendering/)
- [Scheduling in React](https://philippspiess.com/scheduling-in-react/)

### v8

- [v8 Resource](https://github.com/ray-cp/browser_pwn_resources/blob/master/v8_resources.md)
- [Understanding V8’s Bytecode](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775)
- [Concurrent marking in V8](https://v8project.blogspot.com/2018/06/concurrent-marking.html)
- [V8 / Chrome Architecture Reading List - For Vulnerability Researchers](https://zon8.re/posts/v8-chrome-architecture-reading-list-for-vulnerability-researchers/)

### JS Books

- [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)
- [Javascript: The Good Parts](http://www.amazon.in/Javascript-Good-Parts-D-Crockford/dp/0596517742)
- [Mostly Adequate Guide to Functional Programming](https://drboolean.gitbooks.io/mostly-adequate-guide/)
- [Programming JavaScript Applications](http://chimera.labs.oreilly.com/books/1234000000262/)
- [The JavaScript Way](https://github.com/bpesquet/thejsway)
- [Speaking JS](http://speakingjs.com/es5/index.html)

## Security

### Attacks

- [SSL Strip](https://github.com/moxie0/sslstrip)
- [SQL Injection](https://www.owasp.org/index.php/Testing_for_SQL_Injection_(OTG-INPVAL-005))
- [Binary Exploitation](https://github.com/CodeMaxx/Binary-Exploitation)
- [SQL Attack Constraint Based](https://dhavalkapil.com/blogs/SQL-Attack-Constraint-Based/)
- [DNS Reconnaissance – DNSRecon](https://pentestlab.blog/2012/11/13/dns-reconnaissance-dnsrecon/)
- [What is a DDoS Attack?](https://www.cloudflare.com/learning/ddos/what-is-a-ddos-attack/)
- [Server Side Request Forgery (SSRF)?](https://www.acunetix.com/blog/articles/server-side-request-forgery-vulnerability/)
- [All you need to know about SYN floods](https://blog.dubbelboer.com/2012/04/09/syn-cookies.html)
- ["kernel: Possible SYN flooding on port X. Sending cookies" is logged](https://access.redhat.com/solutions/30453)
- [SSL Strip for Newbies](https://avicoder.me/2016/02/22/SSLstrip-for-newbies/)
- [Cold Boot Attack](https://en.wikipedia.org/wiki/Cold_boot_attack)
- [Heartbleed Bug](http://heartbleed.com/)
- [Shellshock](https://en.wikipedia.org/wiki/Shellshock_%28software_bug%29)
- [Mirai Botnet](https://en.wikipedia.org/wiki/Mirai_(malware))
- [POODLE](https://en.wikipedia.org/wiki/POODLE)
- [Format string attack](https://www.owasp.org/index.php/Format_string_attack)
- [Off-by-one error](https://en.wikipedia.org/wiki/Off-by-one_error)
- [EFAIL](https://efail.de/)
- [HTTP Desync Attacks: Request Smuggling Reborn](https://portswigger.net/research/http-desync-attacks-request-smuggling-reborn)
- [The SSL FREAK vulnerability explained](https://robertheaton.com/2015/04/06/the-ssl-freak-vulnerability/)
- [Abusing HTTP hop-by-hop request headers](https://nathandavison.com/blog/abusing-http-hop-by-hop-request-headers)
- [Memcrashed - Major amplification attacks from UDP port 11211](https://blog.cloudflare.com/memcrashed-major-amplification-attacks-from-port-11211/amp/)
- [Analyzing the Attacks on my Website](https://dev.to/pluralsight/analyzing-the-attacks-on-my-website-30jf)
- [How does a TCP reset attack work](https://robertheaton.com/2020/04/27/how-does-a-tcp-reset-attack-work/)
- [Cracking the lens: targeting HTTP's hidden attack-surface](https://portswigger.net/research/cracking-the-lens-targeting-https-hidden-attack-surface)
- [Web Cache Entanglement: Novel Pathways to Poisoning](https://portswigger.net/research/web-cache-entanglement)
- [Reading Data via CSS Injection](https://curesec.com/blog/article/blog/Reading-Data-via-CSS-Injection-180.html)

### Tools

- [John the Ripper](http://www.openwall.com/john/pro/linux/)
- [Hashcat](https://hashcat.net/hashcat/)
- [XSStrike](https://github.com/s0md3v/XSStrike)
- [GDB: The GNU Project Debugger](https://www.gnu.org/software/gdb/documentation/)
    - [gdb Debugging Full Example (Tutorial): ncurses](http://www.brendangregg.com/blog/2016-08-09/gdb-example-ncurses.html)
    - [GDB Cheatsheet](https://darkdust.net/files/GDB%20Cheat%20Sheet.pdf)
    - [CppCon 2015: Greg Law "Give me 15 minutes & I'll change your view of GDB"](https://www.youtube.com/watch?v=PorfLSr3DDI) :tv:
- [Cipher Tools](http://rumkin.com/tools/cipher/)

### Guides

- [CTF Field Guide](https://trailofbits.github.io/ctf) :sparkles:
- [Buffer Overflow](http://cecs.wright.edu/~pmateti/InternetSecurity/Lectures/BufferOverflow/alephOne.html)
- [Sometimes HTTP > HTTPS](https://stormpath.com/blog/why-http-is-sometimes-better-than-https)
- [Security list for fun and profit](https://github.com/zbetcheckin/Security_list)
- [What “hacking” competitions/challenges exist?](https://security.stackexchange.com/questions/3592/what-hacking-competitions-challenges-exist)
- [Shodan](https://www.shodan.io/)
- [Reverse Shell Cheat Sheet](http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet) :sparkles:
- [Beware of strncpy() and strncat()](https://eklitzke.org/beware-of-strncpy-and-strncat)
- [Lessons learned and misconceptions regarding encryption and cryptology](https://security.stackexchange.com/questions/2202/lessons-learned-and-misconceptions-regarding-encryption-and-cryptology) :sparkles:
- [GOT and PLT for pwning](https://systemoverlord.com/2017/03/19/got-and-plt-for-pwning.html)
- [A Look at The Draft for JWT Best Current Practices](https://auth0.com/blog/a-look-at-the-latest-draft-for-jwt-bcp/)
- [LiveOverflow Binary Hacking](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN) :tv:
- [Advanced web security topics](https://blog.georgovassilis.com/2016/04/16/advanced-web-security-topics/)
- [Don't publicly expose .git](https://en.internetwache.org/dont-publicly-expose-git-or-how-we-downloaded-your-websites-sourcecode-an-analysis-of-alexas-1m-28-07-2015/) :sparkles:
- [The State Of Software Security In 2019](https://noncombatant.org/2019/01/06/state-of-security-2019/) :lock:
- [CSRF](https://cheatsheetseries.owasp.org/cheatsheets/Cross-Site_Request_Forgery_Prevention_Cheat_Sheet.html)
- [The definitive super list for "Google Hacking"](https://gist.github.com/cmartinbaughman/5877945)
- [A list of useful payloads and bypass for Web Application Security and Pentest/CTF](https://github.com/swisskyrepo/PayloadsAllTheThings/)
- [Now you C me, now you don't: An introduction to the hidden attack surface of interpreted languages](https://securitylab.github.com/research/now-you-c-me)

### Games and CTF's

- [Web for Pentesters](https://www.pentesterlab.com/exercises/web_for_pentester/course)
- [Overthewire](http://overthewire.org/wargames/)
- [Crypto Challenges](http://cryptopals.com/)
- https://picoctf.com/
- https://pwnable.kr
- http://gracker.org/
- http://websec.fr/
- https://365.csaw.io/
- https://crackmes.one/

### Crypto

- [So, You Want To Learn To Break Ciphers](https://littlemaninmyhead.wordpress.com/2015/09/28/so-you-want-to-learn-to-break-ciphers/)
- [Alice & Bob : A History of The World’s Most Famous Cryptographic Couple](http://cryptocouple.com/)
- [Implementing AES](http://blog.nindalf.com/implementing-aes/)
- [A Stick Figure Guide to the Advanced Encryption Standard (AES)](http://www.moserware.com/2009/09/stick-figure-guide-to-advanced.html)
- [An Intensive Introduction to Cryptography](https://intensecrypto.org/public/) :book:
- [First SHA1 Collision](https://security.googleblog.com/2017/02/announcing-first-sha1-collision.html)
- [Myths about /dev/urandom](https://www.2uo.de/myths-about-urandom/#blocking)
- [The Joy of Cryptography](http://web.engr.oregonstate.edu/~rosulekm/crypto/)
- [Bcrypt Step by Step](https://qvault.io/2020/08/24/bcrypt-step-by-step/)
- [Why shouldn't we roll our own?](http://security.stackexchange.com/questions/18197/why-shouldnt-we-roll-our-own) :sparkles:
- [How to securely hash passwords?](https://security.stackexchange.com/a/31846/179997)
- [How To Safely Store A Password](https://codahale.com/how-to-safely-store-a-password/)
- [So you want to roll your own crypto?](https://vnhacker.blogspot.com/2020/08/so-you-want-to-roll-your-own-crypto.html?m=1)

### Security Papers

- [Untraceable electronic mail, return addresses, and digital pseudonyms](https://mirror.robert-marquardt.com/anonbib/cache/chaum-mix.pdf)
- [Understanding the Mirai Botnet](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-antonakakis.pdf)
- [Exposing Private Information by Timing Web Applications](https://crypto.stanford.edu/~dabo/papers/webtiming.pdf)
- [Security, Authentication, and Public Key Systems](http://www.merkle.com/papers/Thesis1979.pdf)
- [A Future-Adaptable Password Scheme](https://www.usenix.org/legacy/events/usenix99/provos/provos.pdf)
- [Too Much Crypto](https://eprint.iacr.org/2019/1492.pdf)

## Docker

- [Docker Internals](http://docker-saigon.github.io/post/Docker-Internals/)
- [Understanding Docker Internals](https://medium.com/@nagarwal/understanding-the-docker-internals-7ccb052ce9fe)
- [Docker Secure Deployment](https://github.com/GDSSecurity/Docker-Secure-Deployment-Guidelines)
- [Docker Curriculum](https://prakhar.me/docker-curriculum/)
- [Docker Cheatsheet](https://github.com/eon01/DockerCheatSheet)
- [A tiny but valid `init` for containers](https://github.com/krallin/tini)
- [Intro Guide to Dockerfile Best Practices](https://blog.docker.com/2019/07/intro-guide-to-dockerfile-best-practices/)
- [Introduction to Container Security](https://www.docker.com/sites/default/files/WP_IntrotoContainerSecurity_08.19.2016.pdf) :page_with_curl:

## Algorithms

> [Know Thy Complexities!](http://bigocheatsheet.com/#)

- [Complexity of Python Operations](https://www.ics.uci.edu/~pattis/ICS-33/lectures/complexitypython.txt)
- [Heap Algorithm](http://ruslanledesma.com/2016/06/17/why-does-heap-work.html)
- [Linked lists are still hard](https://brennan.io/2017/04/21/linked-lists-are-still-hard/)
- [Understanding Dijkstra's Algorithm](https://aos.github.io/2018/02/24/understanding-dijkstras-algorithm/)
- [How to think in graphs](https://medium.freecodecamp.org/i-dont-understand-graph-theory-1c96572a1401)
- [Ask HN: What's your favorite elegant/beautiful algorithm?](https://news.ycombinator.com/item?id=18236396)
- [Algorithms Behind Modern Storage Systems](https://queue.acm.org/detail.cfm?id=3220266)
- [The Knuth-Morris-Pratt Algorithm in my own words](http://jakeboxer.com/blog/2009/12/13/the-knuth-morris-pratt-algorithm-in-my-own-words/)
- [Why is processing a sorted array faster than processing an unsorted array?](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array) :sparkles: :zap:
- [Introduction to Algorithms](https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844) :books:

## Data Structures

### Advanced Data Structures

#### Bloom filter

- [What are Bloom filters?](https://blog.medium.com/what-are-bloom-filters-1ec2a50c68ff)
- [When Bloom filters don't bloom](https://blog.cloudflare.com/when-bloom-filters-dont-bloom/)

## Internet

### Webservers

- [Apache vs Nginx: Practical Considerations](https://www.digitalocean.com/community/tutorials/apache-vs-nginx-practical-considerations)
- [The C10K problem](http://www.kegel.com/c10k.html)
- [nginx](http://www.aosabook.org/en/nginx.html)
- [How WebSocket server handles multiple incoming connection requests?](https://stackoverflow.com/questions/28516962/how-websocket-server-handles-multiple-incoming-connection-requests)
- [Understanding Nginx HTTP Proxying, Load Balancing, Buffering, and Caching](https://www.digitalocean.com/community/tutorials/understanding-nginx-http-proxying-load-balancing-buffering-and-caching)

### Web Caching

- [Web Cache - Everything you need to know](http://kamranahmed.info/blog/2017/03/14/quick-guide-to-http-caching/)
- [Cache Docs](https://www.mnot.net/cache_docs/)

### Protocols

#### HTTP(S)

- [HTTP](https://www.jmarshall.com/easy/http/)
- [Capturing HTTP Packets](https://medium.com/@cjoudrey/capturing-http-packets-the-hard-way-b9c799bfb6)
- [HTTPS in the real world](https://robertheaton.com/2018/11/28/https-in-the-real-world/)
- [How does HTTPS actually work?](https://robertheaton.com/2014/03/27/how-does-https-actually-work/)
- [Designing Headers for HTTP Compression](https://www.mnot.net/blog/2018/11/27/header_compression)
- [HTTP headers for the responsible developer](https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer)
- [Journey to HTTP/2](https://kamranahmed.info/blog/2016/08/13/http-in-depth/) :sparkles:
- [Comparing HTTP/3 vs. HTTP/2 Performance](https://blog.cloudflare.com/http-3-vs-http-2/)
- [HTTP3](https://blog.cloudflare.com/http-3-from-root-to-tip/)
- [QUIC](https://blog.cloudflare.com/the-road-to-quic/)
- [Employing QUIC Protocol to Optimize Uber’s App Performance](https://eng.uber.com/employing-quic-protocol/)
- [HTTP/3: the past, the present, and the future](https://blog.cloudflare.com/http3-the-past-present-and-future/)
- [Evolution of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Evolution_of_HTTP)

#### TCP/UDP

- [How does SSL/TLS work?](https://security.stackexchange.com/questions/20803/how-does-ssl-tls-work)
- [The Illustrated TLS Connection](https://tls.ulfheim.net/)
- [The New Illustrated TLS Connection](https://tls13.ulfheim.net/)
- [Discussion: UDP in web](https://news.ycombinator.com/item?id=13741155)
- [Let's code a TCP/IP stack](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)
- [When TCP sockets refuse to die](https://idea.popcount.org/2019-09-20-when-tcp-sockets-refuse-to-die/)
- [Messing With Telnet](https://jott.live/markdown/telnet_writeup)
- [How TCP Sockets Work](https://eklitzke.org/how-tcp-sockets-work)
- [How Does TCP Work?](https://sookocheff.com/post/networking/how-does-tcp-work/)

#### DHCP

- [DHCP configuration file /etc/dhcp/dhcpd.conf explained](https://www.thegeekdiary.com/dhcp-configuration-file-etcdhcpdhcpd-conf-explained/)

#### DNS

- [DNS in One Picture](https://medium.com/@kamranahmedse/dns-in-one-picture-d7f4783db06a)
- [The Web Developer's Guide to DNS](https://rjzaworski.com/2019/04/the-web-developers-guide-to-dns)
- [The uncertainty of measuring the DNS](https://blog.apnic.net/2018/07/18/the-uncertainty-of-measuring-the-dns/)

> [A cartoon intro to DNS over HTTPS](https://hacks.mozilla.org/2018/05/a-cartoon-intro-to-dns-over-https/)

#### BGP

- [What Is BGP? | BGP Routing Explained](https://www.cloudflare.com/learning/security/glossary/what-is-bgp/)

### Load Balancing

- [Load Balancing](https://blog.vivekpanyam.com/scaling-a-web-service-load-balancing/)
- [GLB: GitHub's open source load balancer](https://githubengineering.com/glb-director-open-source-load-balancer/)

### Random

- [What are Long-Polling, Websockets, Server-Sent Events (SSE) and Comet?](https://stackoverflow.com/questions/11077857/what-are-long-polling-websockets-server-sent-events-sse-and-comet)
- [The future of the open internet](https://medium.freecodecamp.com/inside-the-invisible-war-for-the-open-internet-dd31a29a3f08)
- [What happens when...](https://github.com/alex/what-happens-when) :sparkles::zap:
- [How Wi-Fi Works](http://www.verizoninternet.com/bookmark/how-wifi-works/)
- [Let 'localhost' be localhost](https://tools.ietf.org/html/draft-west-let-localhost-be-localhost-04)
- [Network Ingress Filtering: Defeating Denial of Service Attacks which employ IP Source Address Spoofing](https://tools.ietf.org/html/bcp38)
- [How Does the Internet Work?](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm) :page_with_curl:
- [The Law of Leaky Abstractions](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/) :sparkles:
- [How to crawl a quarter billion webpages in 40 hours](http://www.michaelnielsen.org/ddi/how-to-crawl-a-quarter-billion-webpages-in-40-hours/)
- [Setting up your server for IPv6 (nginx)](https://bubblin.io/blog/ipv6-nginx)
- [Latency Numbers](https://gist.github.com/jboner/2841832)
- [The world in which IPv6 was a good design](https://apenwarr.ca/log/20170810)
- [The Non-complexity of /etc/nsswitch.conf](https://developers.redhat.com/blog/2018/11/26/etc-nsswitch-conf-non-complexity/) :sparkles:
- [What is Envoy](https://www.envoyproxy.io/docs/envoy/latest/intro/what_is_envoy)
- [High Performance Browser Networking](https://hpbn.co/)
- [HAProxy](http://www.haproxy.org/)
- [Kerberos: The Network Authentication Protocol](https://web.mit.edu/kerberos/)
- [WebRTC for the Curious](https://webrtcforthecurious.com/)

### Networking Books :books:

- [HTTP: The Definitive Guide](http://shop.oreilly.com/product/9781565925090.do)
- [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html)
- [Understanding IP Addressing: Everything You Ever Wanted To Know](http://pages.di.unipi.it/ricci/501302.pdf)
- [Kurose and Ross - Top Down Networking](http://amzn.in/d/3S7Wd4s)
- TCP/IP Illustrated
- [High Performance Browser Networking](https://hpbn.co/)
- [Computer Networking : Principles, Protocols and Practice, 2nd edition](http://cnp3book.info.ucl.ac.be/2nd/html/)

### Networking Papers :page_with_curl:

- [API Design](https://github.com/papers-we-love/papers-we-love/blob/master/api_design/api-design.pdf)
- [Breach: Reviving The Crime Attack](http://breachattack.com/resources/BREACH%20-%20SSL,%20gone%20in%2030%20seconds.pdf)
- [Cloak of Visibility](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45365.pdf)
- [Thinking about Availability in Large Service Infrastructures](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/46181.pdf)
- [A Look Back at “Security Problems in the TCP/IP Protocol Suite”](https://www.cs.columbia.edu/~smb/papers/acsac-ipext.pdf)
- [Filecoin: A Decentralized Storage Network](https://filecoin.io/filecoin.pdf)
- [Breaking the Browser Language Barrier](http://plasma-umass.github.io/doppio-demo/paper.pdf)
- [Defending Internet Freedom through Decentralization Back to the Future?](http://dci.mit.edu/assets/papers/decentralized_web.pdf)
- [The anatomy of a large-scale hypertextual Web search engine](http://zoo.cs.yale.edu/classes/cs426/2012/bib/brin98theanatomy.pdf)
- [The Tail at Scale](https://cseweb.ucsd.edu/~gmporter/classes/fa17/cse124/post/schedule/p74-dean.pdf)
- [Automating chaos experiments in production](https://arxiv.org/pdf/1905.04648.pdf)

## Git

- [Making Commit in past](http://stackoverflow.com/questions/3895453/how-do-i-make-a-git-commit-in-the-past)
- [A Successful Git Branching Model](http://nvie.com/posts/a-successful-git-branching-model/)
- [Oh shit, git!](http://ohshitgit.com/)
- [Git from the inside out](https://codewords.recurse.com/issues/two/git-from-the-inside-out)
- [What’s Wrong With Git? - Git Merge 2017](https://www.youtube.com/watch?v=31XZYMjg93o) :tv:
- [Git Aliases of the Gods!](https://www.youtube.com/watch?v=3IIaOj1Lhb0) :tv:
- [High-level Problems with Git and How to Fix Them](https://gregoryszorc.com/blog/2017/12/11/high-level-problems-with-git-and-how-to-fix-them/)
- [Git Submodules: Adding, Using, Removing, Updating](https://chrisjean.com/git-submodules-adding-using-removing-and-updating/)
- [Git from the bottom up](https://jwiegley.github.io/git-from-the-bottom-up/)
- [Advanced Git Commands You Will Actually Use](https://stosb.com/blog/advanced-git-commands-you-will-actually-use/)
- [Commit Often, Perfect Later, Publish Once: Git Best Practices](http://sethrobertson.github.io/GitBestPractices/)
- [Rebase with history -- implementation ideas](http://softwareswirl.blogspot.in/2009/08/rebase-with-history-implementation.html)
- [Git team workflows: merge or rebase?](https://www.atlassian.com/git/articles/git-team-workflows-merge-or-rebase)
- [Git introduction – .git directory](http://slidedeck.io/mikhail-vnukov/git-basics)
- [How to teach Git](https://rachelcarmena.github.io/2018/12/12/how-to-teach-git.html)
- [Git Immersion](http://gitimmersion.com/index.html)
- [Git Compression of Blobs and Packfiles](https://gist.github.com/matthewmccullough/2695758)
- [Why do Git/Mercurial repositories use less space?](https://softwareengineering.stackexchange.com/questions/148434/why-do-git-mercurial-repositories-use-less-space/148498#148498)
- [How bad can it git? Characterizing secret leakage in public GitHub repositories](https://blog.acolyer.org/2019/04/08/how-bad-can-it-git-characterizing-secret-leakage-in-public-github-repositories/)
- [Understanding git for real by exploring the .git directory](https://www.daolf.com/posts/git-series-part-1/)
- [git add --patch and --interactive](https://nuclearsquid.com/writings/git-add/)
- [Git gc](https://www.atlassian.com/git/tutorials/git-gc)
- [Pro Git](https://git-scm.com/book/en/v2) :books:
- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
- [Git Hooks](https://githooks.com/)
- `git rebase --onto`
    - https://twitter.com/mluisbrown/status/1291756770445099009
    - https://git-scm.com/docs/git-rebase
- `git push --force-with-lease`
    - https://git-scm.com/docs/git-push#Documentation/git-push.txt---force-with-leaseltrefnamegtltexpectgt

## Linux

### Linux

- [Linux Insides](https://0xax.gitbooks.io/linux-insides/content/index.html)
- [chmod Tutorial](http://catcode.com/teachmod/)
- [Linux Tracing Systems](https://jvns.ca/blog/2017/07/05/linux-tracing-systems/)
- [Orphan vs Zombie vs Daemon Processes](https://www.gmarik.info/blog/2012/orphan-vs-zombie-vs-daemon-processes/)
- [Linux Bridge](http://goyalankit.com/blog/linux-bridge)
- [inetd Vs xinetd in linux](http://unixadminschool.com/blog/2011/07/inetd-vs-xinetd-in-linux/)
- [The Lost Art of the Makefile](http://www.olioapps.com/blog/the-lost-art-of-the-makefile/) :sparkles::sparkles:
- [rm -rf remains](https://lambdaops.com/rm-rf-remains/) :sparkles:
- [Linux Containers in 500 lines](https://blog.lizzie.io/linux-containers-in-500-loc.html)
- [What happens when you start a process on Linux?](https://jvns.ca/blog/2016/10/04/exec-will-eat-your-brain/)
- [The Unix and Internet Fundamentals HOWTO](https://www.tldp.org/HOWTO/Unix-and-Internet-Fundamentals-HOWTO/index.html) :sparkles::sparkles:
- [How does the system shutdown of a linux kernel work internally?](https://unix.stackexchange.com/a/122667/)
- [The Definitive Guide to Linux System Calls](https://blog.packagecloud.io/eng/2016/04/05/the-definitive-guide-to-linux-system-calls/) :sparkles:
- [grep your way to freedom](https://anniecherkaev.com/grep-your-way-to-freedom)
- [The real power of Linux executables](https://ownyourbits.com/2018/05/23/the-real-power-of-linux-executables/)
- [x86 Assembly Guide](http://www.cs.virginia.edu/~evans/cs216/guides/x86.html) :sparkles:
- [Linux file descriptors](https://monometric.io/article/file-descriptors-in-2018)
- [UNIX Syscalls](https://john-millikin.com/unix-syscalls)
- [How statically linked programs run on Linux](https://eli.thegreenplace.net/2012/08/13/how-statically-linked-programs-run-on-linux) :sparkles:
- [File Types in Linux](https://linuxconfig.org/identifying-file-types-in-linux)
- [Write your Own Virtual Machine](https://justinmeiners.github.io/lc3-vm/?fbclid=IwAR10_Mr9b--R5KaentRh_W2d4gyDcHt70jbIOuF_FYDXy8NwyFRN9qkQC10)
- [Killing processes that don't want to die](https://lwn.net/Articles/754980/)
- [Threads and fork(): think twice before mixing them](https://www.linuxprogrammingblog.com/threads-and-fork-think-twice-before-using-them)
- [Loading and ptrace'ing a process on Linux](http://system.joekain.com/2015/06/08/debugger.html)
- [Understanding glibc malloc](https://sploitfun.wordpress.com/2015/02/10/understanding-glibc-malloc/)
- [Systemd as tragedy](https://lwn.net/SubscriberLink/777595/a71362cc65b1c271/)
- [The Good, the Bad, and the Ugly: The Unix! Legacy](http://herpolhode.com/rob/ugly.pdf)
- [Rethinking PID 1](http://0pointer.de/blog/projects/systemd.html)
- [What is Overcommit? And why is it bad?](https://www.etalabs.net/overcommit.html)
- [Your terminal is not a terminal: An Introduction to Streams](https://lucasfcosta.com/2019/04/07/streams-introduction.html)
- [How fast are Unix domain sockets?](https://blog.myhro.info/2017/01/how-fast-are-unix-domain-sockets)
- [The 101 of ELF files on Linux: Understanding and Analysis](https://linux-audit.com/elf-binaries-on-linux-understanding-and-analysis/)
- [Linux namespaces](http://ifeanyi.co/posts/linux-namespaces-part-1/)
- [Why should text files end with a newline?](https://stackoverflow.com/questions/729692/why-should-text-files-end-with-a-newline)
- [What has to happen with Unix virtual memory when you have no swap space](https://utcc.utoronto.ca/~cks/space/blog/unix/NoSwapConsequence)
- [htop explained](https://peteris.rocks/blog/htop/)
- [The Linux Scheduler: a Decade of Wasted Cores](https://blog.acolyer.org/2016/04/26/the-linux-scheduler-a-decade-of-wasted-cores/)
- [Linux Log Files that are Located under /var/log Directory](https://www.thegeekstuff.com/2011/08/linux-var-log-files/)
- [Basic Linux Privilege Escalation](https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/)
- [An Evening with Berferd In Which a Cracker is Lured, Endured, and Studied](https://www.cheswick.com/ches/papers/berferd.pdf) :page_with_curl:
- [“zero copy networking” vs “kernel bypass”?](https://stackoverflow.com/a/18346526)
- [Understanding cgroups](https://www.grant.pizza/blog/understanding-cgroups/)
- [The brokenness of the sendfile() system call](https://blog.phusion.nl/2015/06/04/the-brokenness-of-the-sendfile-system-call/)

### Kernel

- [Kernel Map](http://www.makelinux.net/kernel_map/)
- [Documentation extracted from the Linux kernel](https://www.kernel.org/doc/)
- [The Linux Kernel documentation](https://www.kernel.org/doc/html/latest/)
- [Pushing the Limits of Kernel Networking](https://rhelblog.redhat.com/2015/09/29/pushing-the-limits-of-kernel-networking/)
- [The Linux Kernel Module Programming Guide](http://www.tldp.org/LDP/lkmpg/2.6/lkmpg.pdf)
- [The Linux Kernel](https://linux-kernel-labs.github.io/refs/heads/master/lectures/intro.html)

### SSH

- [Secure Secure Shell](https://stribika.github.io/2015/01/04/secure-secure-shell.html)
- [SSH Examples, Tips & Tunnels](https://hackertarget.com/ssh-examples-tunnels/)
- [Endlessh: an SSH Tarpit](https://nullprogram.com/blog/2019/03/22/)
- [Comparing SSH Encryption Algorithms - RSA, DSA, ECDSA, or EdDSA?](https://gravitational.com/blog/comparing-ssh-keys/)

### Linux Security

- [Linux Kernel Exploitation](https://github.com/xairy/linux-kernel-exploitation)
- [Dirty Cow](https://chao-tic.github.io/blog/2017/05/24/dirty-cow)
- [Explaining Dirty COW local root exploit - CVE-2016-5195](https://www.youtube.com/watch?v=kEsshExn7aE) :tv:
- [Linux Firewall Tutorial: IPTables Tables, Chains, Rules Fundamentals](http://www.thegeekstuff.com/2011/01/iptables-fundamentals/)
- [Security Tips for Linux Servers](https://www.tecmint.com/linux-server-hardening-security-tips/)
- [Three kinds of memory leaks](https://blog.nelhage.com/post/three-kinds-of-leaks/)
- [Running Untrusted Programs in Linux](https://stackoverflow.com/questions/4249063/run-an-untrusted-c-program-in-a-sandbox-in-linux-that-prevents-it-from-opening-f)
- [Writing a simple rootkit for linux](https://w3.cs.jmu.edu/kirkpams/550-f12/papers/linux_rootkit.pdf)
- [Do sudo and .profile/.bashrc enable trivial privilege escalation?](https://security.stackexchange.com/questions/187502/do-sudo-and-profile-bashrc-enable-trivial-privilege-escalation)
- [How to break out of a chroot() jail](https://web.archive.org/web/20160127150916/http://www.bpfh.net/simes/computing/chroot-break.html)
- [Securing Debian Manual](https://www.debian.org/doc/manuals/securing-debian-howto/index.en.html#contents)

### Bash

- [Bash Guide for Beginners](http://tldp.org/LDP/Bash-Beginners-Guide/html/)
- [Shellcoding](http://www.vividmachines.com/shellcode/shellcode.html)
- [Creating a bash completion script](https://iridakos.com/tutorials/2018/03/01/bash-programmable-completion-tutorial.html)
- [Explain Shell](https://explainshell.com/)
- [Writing a Unix Shell](https://indradhanush.github.io/blog/writing-a-unix-shell-part-1/)
- [Learn Shell](http://www.learnshell.org/) :books:

### BPF

- [BPF: Tracing and More](http://www.brendangregg.com/Slides/LCA2017_BPF_tracing_and_more.pdf)
- [Cloudflare architecture and how BPF eats the world](https://blog.cloudflare.com/cloudflare-architecture-and-how-bpf-eats-the-world/)

### Linux Books

- [Linux Device Drivers](http://free-electrons.com/doc/books/ldd3.pdf)
- [Conquering The Command Line](http://conqueringthecommandline.com/book)

## OS dev

- [Operating Systems Lecture Notes](http://people.csail.mit.edu/rinard/osnotes/)
- [Kernel 101 – Let’s write a Kernel](http://arjunsreedharan.org/post/82710718100/kernel-101-lets-write-a-kernel)
- [Kernel development](http://www.osdever.net/bkerndev/Docs/intro.htm)
- [Computer architecture for network engineers](https://github.com/lukego/blog/issues/18)
- [Building a simple Kernel](http://wiki.osdev.org/Bare_Bones)
- [How Does an Intel Processor Boot?](https://binarydebt.wordpress.com/2018/10/06/how-does-an-x86-processor-boot/)
- [implement your own Linux kernel](https://david942j.blogspot.com/2018/10/note-learning-kvm-implement-your-own.html)

### Books

- [Os Dev Books](http://wiki.osdev.org/Books#TCP.2FIP)
- [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- [Rute User's Tutorial and Exposition](https://rlworkman.net/howtos/rute/)
- [The OS Classics](https://www.allthingsdistributed.com/2020/07/the-os-classics.html)

## C

- [Lightweight HTTP Server](http://kukuruku.co/hub/cpp/lightweight-http-server-in-less-than-40-lines-on-libevent-and-c-11)
- [Understanding C by learning assembly](https://www.recurse.com/blog/7-understanding-c-by-learning-assembly) :sparkles::sparkles:
- [Smashing The Stack For Fun And Profit](http://cecs.wright.edu/~pmateti/InternetSecurity/Lectures/BufferOverflow/alephOne.html)
- [GNU Make: A Program for Directing Recompilation](http://web.mit.edu/gnu/doc/html/make_toc.html)
- [ncurses Programming HOWTO](http://www.tldp.org/HOWTO/NCURSES-Programming-HOWTO/)
- [Make your own build system](http://jstimpfle.de/blah/buildsystem/buildsystem.html)
- [Malloc tutorial](https://danluu.com/malloc-tutorial/)
- [Let's Build a Compiler, by Jack Crenshaw](https://compilers.iecc.com/crenshaw/)
- [Back to Basics](https://www.joelonsoftware.com/2001/12/11/back-to-basics/)
- [Tearing apart printf()](http://www.maizure.org/projects/printf/index.html) :sparkles::sparkles:

## Ruby

- [Ruby Programming](https://www.theodinproject.com/courses/ruby-programming)
- [Metaprogramming in Ruby](http://ruby-metaprogramming.rubylearning.com/)
- [Visualizing Your Ruby Heap](http://tenderlovemaking.com/2017/09/27/visualizing-your-ruby-heap.html)
- [7 Deadly Sins of Ruby Metaprogramming](https://www.codeschool.com/blog/2015/04/24/7-deadly-sins-of-ruby-metaprogramming/)
- [Guide to Ruby](http://poignant.guide/book/) :book:
- [Ruby Under a Microscope](http://patshaughnessy.net/ruby-under-a-microscope) :book:

## Rails

- [RoR Tutorial](https://www.railstutorial.org/book/frontmatter) :book:
- [Predicting Test Failures](http://tenderlovemaking.com/2015/02/13/predicting-test-failues.html)
- [XSS and Rails](http://blog.bigbinary.com/2012/05/10/xss-and-rails.html)
- [RailsConf 2014 - All the Little Things by Sandi Metz](https://www.youtube.com/watch?v=8bZh5LMaSmE) :tv:

## Haskell

- [Official Documentation](https://www.haskell.org/documentation)
- [How to learn Haskell](https://github.com/bitemyapp/learnhaskell)
- [Fighting spam with Haskell](https://code.facebook.com/posts/745068642270222/fighting-spam-with-haskell/) :sparkles:
- [Huge list of videos, talks, courses for Haskell programming language](https://github.com/hzlmn/haskell-must-watch)
- [Happy Learn Haskell Tutorial](http://www.happylearnhaskelltutorial.com/)
- [Some Notes About How I Write Haskell](https://blog.infinitenegativeutility.com/2017/12/some-notes-about-how-i-write-haskell)
- [Learn You a Haskell for Great Good!](http://learnyouahaskell.com/chapters)

<details>
<summary>Books</summary>
<p>

- [Open-source Haskell books](http://hn.premii.com/#/article/14392423)
- [Learn You a Haskell](http://learnyouahaskell.com)
- [Real World Haskell](http://book.realworldhaskell.org/read/)
- [Haskell Programming from first principles](http://haskellbook.com/)
- [Beginning Haskell](http://www.apress.com/in/book/9781430262503)

</p>
</details>

## Go

> [Go FAQ](https://golang.org/doc/faq)

### Go Pilot run

- [Tour of Go](https://tour.golang.org/)
- [Go by example](https://gobyexample.com/)
- [Effective Go](https://golang.org/doc/effective_go.html)
- [Golang channels tutorial](http://guzalexander.com/2013/12/06/golang-channels-tutorial.html)
- [Resources for new Go programmers](https://dave.cheney.net/resources-for-new-go-programmers)

### Concepts

> Do not communicate by sharing memory; instead, share memory by communicating.

#### Concurrency

> Concurrency is not Parallelism

- [Go Concurrency from the Ground Up](http://www.doxsey.net/blog/go-concurrency-from-the-ground-up)
- [How Goroutines Work](http://blog.nindalf.com/how-goroutines-work/) :sparkles:
- [Concurrency is not Parallelism](https://talks.golang.org/2012/waza.slide) :sparkles:
- [Concurrency in golang and a mini Load-balancer](https://gist.github.com/rushilgupta/228dfdf379121cb9426d5e90d34c5b96)
- [Channels in Go](https://go101.org/article/channel.html)
- [Go Concurrency Patterns](https://talks.golang.org/2012/concurrency.slide#33)
- [Concurrent programming, with examples](https://begriffs.com/posts/2020-03-23-concurrent-programming.html?hn=1)
- [Slow down your code with goroutines](https://appliedgo.net/concurrencyslower/)
- [How to Gracefully Close Channels](https://go101.org/article/channel-closing.html) :sparkles:
- [Go channels on steroids](https://docs.google.com/document/d/1yIAYmbvL3JxOKOjuCyon7JhW4cSv1wy5hC0ApeGMV9s/pub)

#### Profiling :mag:

> [Go Diagnostics](https://golang.org/doc/diagnostics.html) :wrench:

- [Profiling Go](http://www.integralist.co.uk/posts/profiling-go/)
- [Scheduler Tracing In Go](https://www.ardanlabs.com/blog/2015/02/scheduler-tracing-in-go.html)
- [Profiling and optimizing Go web applications](https://artem.krylysov.com/blog/2017/03/13/profiling-and-optimizing-go-web-applications/)
- [Profiling Go Programs](https://blog.golang.org/profiling-go-programs)
- [pprof](https://jvns.ca/blog/2017/09/24/profiling-go-with-pprof/)
- [Building efficient statsd library in Go](https://talks.godoc.org/github.com/smira/gopherconru2018/go-statsd.slide#1)
- [go tool trace](https://making.pusher.com/go-tool-trace/)

#### More

- [Interfaces in Go](http://jordanorelli.com/post/32665860244/how-to-use-interfaces-in-go)
- [Go Data Structures: Interfaces](https://research.swtch.com/interfaces)
- [The Case For Go](https://gist.github.com/ungerik/3731476)
- [Applied Go](https://appliedgo.net/)
- [Golang Has Generics](http://blog.jonathanoliver.com/golang-has-generics/)
- [Go-tcha: When nil != nil](https://dev.to/pauljlucas/go-tcha-when-nil--nil-hic)
- [SOLID Go Design](https://dave.cheney.net/2016/08/20/solid-go-design)
- [Simple techniques to optimise Go programs](https://stephen.sh/posts/quick-go-performance-improvements)
- [Less is exponentially more](https://commandcenter.blogspot.com/2012/06/less-is-exponentially-more.html)
- [A whirlwind tour of Go’s runtime environment variables](https://dave.cheney.net/tag/godebug)
- [Allocation efficiency in high-performance Go services](https://segment.com/blog/allocation-efficiency-in-high-performance-go-services/)
- [How we optimized our DNS server using go tools](https://medium.com/@arash.cordi/how-we-optimized-our-dns-server-using-go-tools-d753e1a5e709) :sparkles:
- [Optimizing M3: How Uber Halved Our Metrics Ingestion Latency by (Briefly) Forking the Go Compiler](https://eng.uber.com/optimizing-m3/) :sparkles:
- [Go’s hidden #pragmas](https://dave.cheney.net/2018/01/08/gos-hidden-pragmas)

### Go Internals

> [Everything about Go: internals, concurrency, compiler, or packages available in the Go community.](https://medium.com/a-journey-with-go)

- [Golang’s Real-time GC in Theory and Practice](https://making.pusher.com/golangs-real-time-gc-in-theory-and-practice/) :sparkles:
- [Go compiler internals](https://eli.thegreenplace.net/2019/go-compiler-internals-adding-a-new-statement-to-go-part-1/)
- [The Go Memory Model](https://golang.org/ref/mem) :sparkles:
- [Visually Understanding Worker Pool](https://medium.com/coinmonks/visually-understanding-worker-pool-48a83b7fc1f5)
- [Go’s Extended Concurrency: Semaphores (Part 1)](https://medium.com/@deckarep/gos-extended-concurrency-semaphores-part-1-5eeabfa351ce)
- [Getting to Go: The Journey of Go's Garbage Collector](https://blog.golang.org/ismmkeynote)
- [The Go scheduler](https://morsmachine.dk/go-scheduler)
- [The Case For A Go Worker Pool](https://brandur.org/go-worker-pool)
- [Visualizing Concurrency in Go](http://divan.github.io/posts/go_concurrency_visualize/)
- [Go & Assembly](http://www.doxsey.net/blog/go-and-assembly)
- [Go at Google: Language Design in the Service of Software Engineering](https://talks.golang.org/2012/splash.article)
- [Memory Leaking Scenarios](https://go101.org/article/memory-leaking.html)
- [Memory Order Guarantees in Go](https://go101.org/article/memory-model.html)
- [Dissecting Go Binaries](https://www.grant.pizza/dissecting-go-binaries/)
- [Go Internals](https://github.com/teh-cmc/go-internals)
- [Are large slices more expensive than smaller ones?](https://dave.cheney.net/2020/03/01/are-large-slices-more-expensive-than-smaller-ones) :mag:
- [The Tail at Scale](https://blog.acolyer.org/2015/01/15/the-tail-at-scale/)
- [Contiguous stacks in Go](https://agis.io/post/contiguous-stacks-golang/)
- [How does the go build command work ?](https://dave.cheney.net/2013/10/15/how-does-the-go-build-command-work)

### Networking with Go

- [Writing Network Drivers in Go](https://www.net.in.tum.de/fileadmin/bibtex/publications/theses/2018-ixy-go.pdf)
- [Go for Javascript Developers](https://github.com/pazams/go-for-javascript-developers)
- [Network Programming with Go](http://tumregels.github.io/Network-Programming-with-Go/)
- [A Million WebSockets and Go](https://medium.freecodecamp.org/million-websockets-and-go-cc58418460bb)
- [TCP/IP Networking in Go](https://appliedgo.net/networking/)
- [HTTPS and Go](https://www.kaihag.com/https-and-go/)

### Go Papers

- [Analysis of the Go runtime scheduler](http://www.cs.columbia.edu/~aho/cs6998/reports/12-12-11_DeshpandeSponslerWeiss_GO.pdf)
- [An Implementation and Analysis of a Kernel Network Stack in Go with the CSP Style](https://arxiv.org/abs/1603.05636)

## Rust

- [A Gentle Introduction To Rust](https://stevedonovan.github.io/rust-gentle-intro/1-basics.html)
- [Rust Docs](https://doc.rust-lang.org/rust-by-example/std/result.html)
- [Rust Design Patterns](https://github.com/rust-unofficial/patterns)
- [Rethinking Systems Programming](https://thoughtram.io/rust-and-nickel/#/) :sparkles:
- [The Rust Programming Language](https://doc.rust-lang.org/book/)
- [Learning systems programming with Rust](https://jvns.ca/blog/2016/09/11/rustconf-keynote/)
- [Learn Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/index.html)
- [Fearless Concurrency with Rust](https://blog.rust-lang.org/2015/04/10/Fearless-Concurrency.html)

## Kubernetes

- [What even is a kubelet?](http://kamalmarhubi.com/blog/2015/08/27/what-even-is-a-kubelet/)
- [Kubernetes from the ground up: the API server](http://kamalmarhubi.com/blog/2015/09/06/kubernetes-from-the-ground-up-the-api-server/)
- [Kubernetes from the ground up: the scheduler](http://kamalmarhubi.com/blog/2015/11/17/kubernetes-from-the-ground-up-the-scheduler/)
- [Kubernetes: Getting Started With a Local Deployment](https://blog.jetstack.io/blog/k8s-getting-started-part2/)
- [Awesome Kubernetes](https://github.com/ramitsurana/awesome-kubernetes)

## Database

- [Secure PostgreSQL](https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps) :lock:
- [SQL vs NoSQL](https://www.airpair.com/postgresql/posts/sql-vs-nosql-ko-postgres-vs-mongo)
- [Build a simple database](https://cstack.github.io/db_tutorial/)
- [One Giant Leap For SQL: MySQL 8.0 Released](https://modern-sql.com/blog/2018-04/mysql-8.0) :sparkles:
- [MongoDB is to NoSQL like MySQL to SQL — in the most harmful way](https://use-the-index-luke.com/blog/2013-10/mysql-is-to-sql-like-mongodb-to-nosql)
- [How Postgres Makes Transactions Atomic](https://brandur.org/postgres-atomicity)
- [Things I Wished More Developers Knew About Databases](https://medium.com/@rakyll/things-i-wished-more-developers-knew-about-databases-2d0178464f78)
- [Building Robust Systems with ACID and Constraints](https://brandur.org/acid) :sparkles:
- [Awesome Database Learning](https://github.com/pingcap/awesome-database-learning)
- [Database Internals](https://www.databass.dev/) :book: :construction:

### Sharding

- [Sharding](https://en.wikipedia.org/wiki/Shard_(database_architecture)#Implementation_of_shards)
- [Principles of Sharding for Relational Databases](https://www.citusdata.com/blog/2017/08/09/principles-of-sharding-for-relational-databases/)
- [Understanding Database Sharding](https://www.digitalocean.com/community/tutorials/understanding-database-sharding)

<details>
<summary>Papers</summary>
<p>

- [Spanner: Google’s Globally Distributed Database](http://delivery.acm.org/10.1145/2500000/2491245/a8-corbett.pdf)
- [A Call to Arms: Revisiting Database Design](https://arxiv.org/pdf/1105.6001.pdf)
- [Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)
- [ACIDRain: Concurrency-Related Attacks on Database-Backed Web Applications](http://www.bailis.org/papers/acidrain-sigmod2017.pdf)

</p>
</details>

## BlockChain, Bitcoin

- [Bitcoin Resources](https://bitcoin.org/en/resources)
- [Blockchain: the revolution we’re not ready for](https://medium.freecodecamp.org/blockchain-is-our-first-22nd-century-technology-d4ad45fca2ce)
- [How Bitcoin Transaction Works](http://imgur.com/a/wvO9H)
- [How Bitcoin Works Under the Hood](https://www.youtube.com/watch?v=Lx9zgZCMqXE) :tv:
- [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
- [Bitcoin, Ethereum, Blockchain, Tokens, ICOs](https://hackernoon.com/bitcoin-ethereum-blockchain-tokens-icos-why-should-anyone-care-890b868cec06)
- [Using the raw Bitcoin protocol](http://www.righto.com/2014/02/bitcoins-hard-way-using-raw-bitcoin.html)
- [Bitcoin mining the hard way](http://www.righto.com/2014/02/bitcoin-mining-hard-way-algorithms.html)
- [EthList: The Crowdsourced Ethereum Reading List](https://github.com/Scanate/EthList)
- [CryptoEconomics](https://hackernoon.com/cryptoeconomics-paving-the-future-of-blockchain-technology-13b04dab971)
- [Emails from Satoshi Nakamoto to Hal Finney](http://online.wsj.com/public/resources/documents/finneynakamotoemails.pdf)
- [Building Blockchain in Go](https://jeiwan.cc/posts/building-blockchain-in-go-part-1/)
- [The Blockchain Dictionary](https://www.theblockchainnewsletter.com/glossary.html)
- [Bitcoin Resources](https://lopp.net/bitcoin.html)
- [Is CPU mining even worth the Ether?](https://ethereum.stackexchange.com/questions/2325/is-cpu-mining-even-worth-the-ether)
- [Nativecoin - build your own crypto-currency](https://lhartikk.github.io/)

<details>
<summary>Books</summary>
<p>

[Mastering Bitcoin](http://chimera.labs.oreilly.com/books/1234000001802/)

</p>
</details>

<details>
<summary>Papers</summary>
<p>

### BlockChain

- [Bitcoin Paper](https://bitcoin.org/bitcoin.pdf)
- [Blockchain Paper](http://scet.berkeley.edu/wp-content/uploads/BlockchainPaper.pdf)
- [Hashcash](http://www.hashcash.org/papers/hashcash.pdf)
- [Introduction To Blockchain](https://bravenewcoin.com/assets/Reference-Papers/A-Gentle-Introduction/A-Gentle-Introduction-To-Blockchain-Technology-WEB.pdf)
- https://medium.com/founder-playbook/67-blockchain-articles-whitepapers-that-shaped-crypto-into-what-it-is-today-c538facfceb9
- [Blockchains from a Distributed Computing Perspective](http://cs.brown.edu/courses/csci2952-a/papers/perspective.pdf)
- [Blockstack: A Global Naming and Storage System Secured by Blockchains](https://www.usenix.org/system/files/conference/atc16/atc16_paper-ali.pdf)
- [IPFS](https://ipfs.io/ipfs/QmR7GSQM93Cx5eAg6a6yRzNde1FQv7uL6X1o4k7zrJa3LX/ipfs.draft3.pdf) :page_with_curl:
- [Bitcoin-NG: A Scalable Blockchain Protocol](http://arxiv.org/abs/1510.02037)
- [A Secure Sharding Protocol For Open Blockchain](https://www.comp.nus.edu.sg/~loiluu/papers/elastico.pdf)
- [Enhancing Bitcoin Security and Performance with Strong Consistency via Collective Signing](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_kokoris-kogias.pdf)
- [Service-Oriented Sharding for Blockchain](https://arxiv.org/pdf/1611.06816.pdf)
- [The stellar consensus protocol: A federated model for internet-level consensus](https://cdn.relayto.com/media/files/bHseNPaMRnmuKKqyO8hT_stellar-consensus-protocol.pdf)

### Ethereum

- [Ethereum White Paper](https://github.com/ethereum/wiki/wiki/White-Paper)
- [Step by Step Towards Creating a Safe Smart Contract: Lessons and Insights from a Cryptocurrency Lab](http://fc16.ifca.ai/bitcoin/papers/DAKMS16.pdf)
- [A Concurrent Perspective on Smart Contracts](https://arxiv.org/pdf/1702.05511.pdf)

### Cryptocurrencies

- [Zerocash: Decentralized Anonymous Payments from Bitcoin](http://ieeexplore.ieee.org/abstract/document/6956581/)
- [SoK: Research Perspectives and Challenges for Bitcoin and Cryptocurrencies](https://www.ieee-security.org/TC/SP2015/papers-archived/6949a104.pdf)
- [Lightning Network](https://lightning.network/lightning-network-paper.pdf)

</p>
</details>

## Tor

- [Research problems: Ten ways to discover Tor bridges](https://blog.torproject.org/blog/research-problems-ten-ways-discover-tor-bridges)
- [Selected Papers in Anonymity](https://www.freehaven.net/anonbib/topic.html) :page_with_curl:
- [Onion Router](https://www.onion-router.net/)
- [Handling bot attacks against a Tor hidden service](http://hn.premii.com/#/article/14280084)
- [Anti-Censorship & Transparency - Roger Dingledine](https://www.youtube.com/watch?v=35l56KjTCb8) :tv:
- [How does Tor work?](https://robertheaton.com/2019/04/06/how-does-tor-work/)
- [How Tor Works](https://jordan-wright.com/blog/2015/02/28/how-tor-works-part-one/)

<details>
<summary>Papers</summary>
<p>

- [Tor Design](https://svn.torproject.org/svn/projects/design-paper/tor-design.pdf)
- [Tor Bridge Discovery](http://www.cs.uml.edu/~xinwenfu/paper/Bridge.pdf)
- [A Model of Onion Routing with Provable Anonymity](https://www.onion-router.net/Publications/or-iomodel.pdf)
- [Locating Hidden Servers](https://www.onion-router.net/Publications/locating-hidden-servers.pdf)

</p>
</details>

## Functional Programming

- [What is Functional Programming ?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0)
- [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon)
- [What is a Functional Composition](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-function-composition-20dfb109a1a0)
- [What is Pure function?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976)
- [Functional Programming](http://wiki.c2.com/?FunctionalProgramming)
- [So You Want to be a Functional Programmer](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536)
- [Practical Functional Programming](https://hackernoon.com/practical-functional-programming-6d7932abc58b)
- [Mostly Adequate Guide to Functional Programming](https://mostly-adequate.gitbooks.io/mostly-adequate-guide/) :sparkles:
- [Parse, don’t validate](https://lexi-lambda.github.io/blog/2019/11/05/parse-don-t-validate/)
- [Functors, Applicatives, And Monads In Pictures](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html) :sparkles: :sparkles: :zap: :zap:
- [A Glossary of Functional Programming](https://degoes.net/articles/fp-glossary)
- [Scala Italy 2019 - John A De Goes - A Tour of Functional Design](https://vimeo.com/370819261) :tv:

## OAuth

- [An Introduction to OAuth 2](https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2)
- [The OAuth 2.0 Authorization Framework RFC](https://tools.ietf.org/html/rfc6749)
- [Securing API with OAuth 2.0](https://alexbilbie.com/2013/02/securing-your-api-with-oauth-2/) :lock:

## Regex

- [Learn Regex](http://regexr.com/)
- [Interactive Exercise](https://regexone.com/)
- https://github.com/zeeshanu/learn-regex
- [Regex For Noobs](https://www.janmeppe.com/blog/regex-for-noobs/)

## Distributed Systems

> [Distributed Systems for fun and profit](http://book.mixu.net/distsys/)

- [Introduction to Distributed System Design](http://www.hpcs.cs.tsukuba.ac.jp/~tatebe/lecture/h23/dsys/dsd-tutorial.html)
- [Raft: Understandable Distributed Consensus](http://thesecretlivesofdata.com/raft/)
- [HTTP is obsolete. It's time for the Distributed Web](https://blog.neocities.org/blog/2015/09/08/its-time-for-the-distributed-web.html)
- Rack Model
- [If you need a global lock in your distributed system, then you're already in trouble](https://news.ycombinator.com/item?id=11066258) :sparkles:
    - Parent Thread [Is Redlock Safe? Reply to Redlock Analysis](https://news.ycombinator.com/item?id=11065933)
- [How to beat the CAP theorem](http://nathanmarz.com/blog/how-to-beat-the-cap-theorem.html) :sparkles:
- [Designing Distributed Systems: Patterns and Paradigms for Scalable, Reliable Services](https://www.oreilly.com/library/view/designing-distributed-systems/9781491983638/) :book: :construction:

## Kafka

- ["Apache Kafka and the Next 700 Stream Processing Systems" by Jay Kreps](https://www.youtube.com/watch?v=9RMOc0SwRro) :tv:
- [A Practical Introduction to Kafka Storage Internals](https://medium.com/@durgaswaroop/a-practical-introduction-to-kafka-storage-internals-d5b544f6925f)
- [Streaming 101: The world beyond batch](https://www.oreilly.com/ideas/the-world-beyond-batch-streaming-101)
- [Kafka and Zookeeper with Docker](https://medium.com/rahasak/kafka-and-zookeeper-with-docker-65cff2c2c34f)
- [A Guide To The Kafka Protocol](https://cwiki.apache.org/confluence/display/KAFKA/A+Guide+To+The+Kafka+Protocol#AGuideToTheKafkaProtocol-Introduction)
- [The Unofficial Kafka Rebalance How-To](https://tomlee.co/2019/03/the-unofficial-kafka-rebalance-how-to/)
- [High Performance Kafka Producers](https://www.jesseyates.com/2020/01/01/high-performance-kafka-producers.html)
- [__consumer_offsets topic in kafka](https://kafka.apache.org/0110/documentation.html#impl_offsettracking)
- [Vertically scaling Kafka consumers](https://www.jesseyates.com/2019/12/04/vertically-scaling-kafka-consumers.html)
- [Apache Kafka Rebalance Protocol, or the magic behind your streams applications](https://medium.com/streamthoughts/apache-kafka-rebalance-protocol-or-the-magic-behind-your-streams-applications-e94baf68e4f2)
- [Apache Kafka Supports 200K Partitions Per Cluster](https://www.confluent.io/blog/apache-kafka-supports-200k-partitions-per-cluster/)
- [It’s Okay To Store Data In Apache Kafka](https://www.confluent.io/blog/okay-store-data-apache-kafka/)
- [Kafka: The Definitive Guide](https://www.confluent.io/resources/kafka-the-definitive-guide/) :book:
- [uReplicator: Uber Engineering’s Robust Apache Kafka Replicator](https://eng.uber.com/ureplicator-apache-kafka-replicator/)

## Spark

- [Memory Management Overview](http://spark.apache.org/docs/latest/tuning.html#memory-management-overview)
- [Tricks of the Trade: Tuning JVM Memory for Large-scale Services](https://eng.uber.com/jvm-tuning-garbage-collection/)
- [Managing Spark Partitions with Coalesce and Repartition](https://medium.com/@mrpowers/managing-spark-partitions-with-coalesce-and-repartition-4050c57ad5c4#.36o8a7b5j)

### Logging

- [Spark Streaming Logging Configuration](http://shzhangji.com/blog/2015/05/31/spark-streaming-logging-configuration/)
- [S3 Log4j Appender](https://www.therealvan.com/s3loggerappender.html)
- [Log4j appender with S3 and search publishing](https://github.com/bluedenim/log4j-s3-search)

## Monitoring

- [When to use the Pushgateway](https://prometheus.io/docs/practices/pushing/)
- [Common pitfalls when using the Pushgateway](https://www.robustperception.io/common-pitfalls-when-using-the-pushgateway)
- [Statsd: Measure Anything, Measure Everything](https://codeascraft.com/2011/02/15/measure-anything-measure-everything/)
- [JVM Profiler: An Open Source Tool for Tracing Distributed JVM Applications at Scale](https://eng.uber.com/jvm-profiler/)
- [Telltale: Netflix Application Monitoring Simplified](https://netflixtechblog.com/telltale-netflix-application-monitoring-simplified-5c08bfa780ba)

## System Design

- [(A few) Ops Lessons We All Learn The Hard Way -- a Twitter](https://twitter.com/jschauma/status/1220902743482814467?s=19)
- [Reddit: How We Built r/Place](https://redditblog.com/2017/04/13/how-we-built-rplace/) :sparkles:
- [Questioning the Lambda Architecture](https://www.oreilly.com/ideas/questioning-the-lambda-architecture)
- [A Brief History of High Availability](https://www.cockroachlabs.com/blog/brief-history-high-availability/)
- [What is Kappa Architecture?](http://milinda.pathirage.org/kappa-architecture.com/)
- [Introduction to Microservices](https://www.nginx.com/blog/introduction-to-microservices/)
- [Uber: Why Uber Engineering Switched from Postgres to MySQL](https://eng.uber.com/mysql-migration/)
- [Principles of chaos engineering](http://principlesofchaos.org/)
- [Introduction to modern network load balancing and proxying](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236)
- [Dropbox: How we migrated Dropbox from Nginx to Envoy](https://dropbox.tech/infrastructure/how-we-migrated-dropbox-from-nginx-to-envoy)
- [Cloudflare: How Cloudflare’s Architecture Can Scale to Stop the Largest Attacks](https://www.cloudflare.com/media/pdf/cf-wp-dns-attacks.pdf)
- [Learn how to design large-scale systems](https://github.com/donnemartin/system-design-primer) :sparkles:

### Scalability

- [Jeremy Edberg - Scalable Cloud Architectures | Tech Talk](https://www.youtube.com/watch?v=cCAO9moDucI&t=1s) :tv:
- [CS75 (Summer 2012) Lecture 9 Scalability Harvard Web Development](https://www.youtube.com/watch?v=-W9F__D3oY4) :tv:
- [A Word on Scalability](https://www.allthingsdistributed.com/2006/03/a_word_on_scalability.html)
- [Scalability for Dummies - Part 3: Cache](http://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache) :sparkles:

### Event driven Architecture

- [Build Services on a Backbone of Events](https://www.confluent.io/blog/build-services-backbone-events/)

### AWS

- [Everything You Need To Know About Networking On AWS](https://grahamlyons.com/article/everything-you-need-to-know-about-networking-on-aws)
- [Deep Dive on Amazon ECS Cluster Auto Scaling](https://aws.amazon.com/blogs/containers/deep-dive-on-amazon-ecs-cluster-auto-scaling/) :sparkles:
- [Designing scalable API on AWS spot instances](https://blog.adapty.io/designing-scalable-api-on-aws-stop-instance/)

### Netflix

- [Mastering Chaos - A Netflix Guide to Microservices](https://www.youtube.com/watch?v=CZ3wIuvmHeM) :tv: :sparkles:
- [How we scaled nginx and saved the world 54 years every day](https://blog.cloudflare.com/how-we-scaled-nginx-and-saved-the-world-54-years-every-day)
- [Building fast.com](https://netflixtechblog.com/building-fast-com-4857fe0f8adb)
- [AWS re:Invent 2017: How Netflix Tunes Amazon EC2 Instances for Performance (CMP325)](https://www.youtube.com/watch?v=89fYOo1V2pA) :tv:
- [AWS re:Invent 2015: A Day in the Life of a Netflix Engineer (DVO203)](https://www.youtube.com/watch?v=-mL3zT1iIKw) :zap:

## Privacy

- [Cutting Google out of your life](https://degoogle.jmoore.dev/)

## x vs y :hocho:

- [Ruby vs Python](https://hackernoon.com/ruby-vs-python-the-definitive-faq-5cb0046292be#.xptk2egps)
- [Weapon of Mass Destruction](http://www.kitploit.com/2017/02/wmd-weapon-of-mass-destruction-python.html)
- [Leaving Clojure for Ruby](https://blog.appcanary.com/2017/hard-isnt-simple-ruby-clojure.html)
- [Why Rust and not Go](https://blog.juliobiason.me/thoughts/why-rust-and-not-go/) :sparkles:
- [Why Go and Rust are Competitors](http://www.doxsey.net/blog/why-go-and-rust-are-competitors)
- [A Response to Hello World](http://www.doxsey.net/blog/a-response-to-hello-world)
- [Kafka vs. Pulsar vs. RabbitMQ: Performance, Architecture, and Features Compared](https://www.confluent.io/kafka-vs-pulsar/)

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

## Blogs

- http://arjunsreedharan.org/
- https://jvns.ca/
- https://githubengineering.com/
- http://nullprogram.com/index/
- https://zwischenzugs.com/
- https://mkdev.me/en/posts
- http://www.uliaea.ca/
- https://blog.cloudflare.com/
- http://prog21.dadgum.com/
- https://increment.com/programming-languages/ :sparkles:
- https://blog.filippo.io/
- http://highscalability.com
- https://notes.shichao.io/
- https://blog.acolyer.org/ - If you are into research papers
- https://lwn.net/
- https://queue.acm.org/
- https://www.linuxjournal.com/
- https://www.the-paper-trail.org/
- https://overreacted.io/
- https://robertheaton.com/
- https://www.mnot.net/blog/
- https://systemoverlord.com/
- https://blog.rpis.ec/
- https://blog.jessfraz.com/
- https://www.hackinglinuxexposed.com/articles/
- [Owasp](https://www.owasp.org/)
- https://rpis.ec/
- https://dave.cheney.net/ - Mostly Golang related
- http://www.brendangregg.com/
- https://www.scalescale.com/
- https://medium.com/@blanchon.vincent :sparkles:
- https://sysadvent.blogspot.com/
- [A handbook for making programming languages](http://craftinginterpreters.com/)
- https://codewithoutrules.com/
- - [Cryptography Services Archives](https://cryptoservices.github.io/archives/) :lock:

## More

- [Password storage in source control](https://stackoverflow.com/questions/559611/password-storage-in-source-control)
- [Global Variables are Bad](http://wiki.c2.com/?GlobalVariablesAreBad)
- [Difference b/w Integration and Unit Tests](https://stackoverflow.com/questions/10752/what-is-the-difference-between-integration-and-unit-tests/7876055#7876055)
- [The language of choice](https://codewords.recurse.com/issues/four/the-language-of-choice)
- [Programmer Competency Matrix](http://sijinjoseph.com/programmer-competency-matrix/)
- [Hacker's guide to Neural Networks](http://karpathy.github.io/neuralnets/)
- [Return to the Source](http://www.cipht.net/2017/10/05/why-read-code.html)
- [A list of everything that could go in the \<head\> of your document](https://github.com/joshbuchea/HEAD)
- [Design Patterns](https://sourcemaking.com/design_patterns) :sparkles:
- [Ask HN: “Write your own” or “Build your own” software projects](https://news.ycombinator.com/item?id=16591918)
- [Software Testing Anti-patterns](http://blog.codepipes.com/testing/software-testing-antipatterns.html) *
- [Detecting the use of "curl | bash" server side](https://www.idontplaydarts.com/2016/04/detecting-curl-pipe-bash-server-side/)
- [A Practical Introduction to Container Terminology](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/)
- [A Programmable Programming Language](https://cacm.acm.org/magazines/2018/3/225475-a-programmable-programming-language/fulltext)
- [Constructors Considered Mildly Confusing](http://zeekat.nl/articles/constructors-considered-mildly-confusing.html)
- [Hacker101](https://www.hacker101.com/)
- [MooTools](https://github.com/mootools/mootools-core)
- [Developer resources for desktop apps](http://askubuntu.com/questions/335454/developer-resources-for-desktop-apps)
- [Clojure - the perfect language to expand your brain?](http://eli.thegreenplace.net/2017/clojure-the-perfect-language-to-expand-your-brain/)
- [International Journal of Proof-of-Concept or Get The Fuck Out](https://www.alchemistowl.org/pocorgtfo/)
- [An Introduction to Hashing in the Era of Machine Learning](https://blog.bradfieldcs.com/an-introduction-to-hashing-in-the-era-of-machine-learning-6039394549b0)
- [Making a virtual machine in Google Sheets](https://briansteffens.github.io/2017/07/03/google-sheets-virtual-machine.html)
- [How Did Software Get So Reliable Without Proof?](http://www.gwern.net/docs/math/1996-hoare.pdf)
- [Google’s secret and Linear Algebra](http://verso.mat.uam.es/~pablo.fernandez/ems63-pablo-fernandez_final.pdf)
- [The Forgotten History of OOP](https://medium.com/javascript-scene/the-forgotten-history-of-oop-88d71b9b2d9f)
- [When setting an environment variable gives you a 40x speedup](https://news.sherlock.stanford.edu/posts/when-setting-an-environment-variable-gives-you-a-40-x-speedup)
- [Meet the Flexbox Inspector](https://gedd.ski/) :sparkles:
- [A better zip bomb](https://www.bamsoftware.com/hacks/zipbomb/)
- [Race Condition vs. Data Race](https://blog.regehr.org/archives/490) :sparkles:
- [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/) :sparkles:
- [A byte’s not 8 bits.](https://burstingdynamics.wordpress.com/2015/11/10/a-byte-is-not-8-bits/) :sparkles:
- [Epigrams in programming](http://www.cs.yale.edu/homes/perlis-alan/quotes.html)
- [The Danger of “Simplicity”](https://asthasr.github.io/posts/danger-of-simplicity)
- [Front End Checklist](https://github.com/thedaviddias/Front-End-Checklist) :file_folder:
- [See Python, See Python Go, Go Python Go](https://blog.heroku.com/see_python_see_python_go_go_python_go)
- [Why stack grows down](https://gist.github.com/cpq/8598782)
- [Programmer's critique of missing structure of operating systems](http://blog.rfox.eu/en/Programmer_s_critique_of_missing_structure_of_oper.html)
- [S2 Cells](https://s2geometry.io/devguide/s2cell_hierarchy.html)
- [JVM Profiler: An Open Source Tool for Tracing Distributed JVM Applications at Scale](https://eng.uber.com/jvm-profiler/)
- [Queryparser, an Open Source Tool for Parsing and Analyzing SQL](https://eng.uber.com/queryparser/)
- [Enabling Machine Learning with Apache Flink - Sherin Thomas](https://www.youtube.com/watch?v=_4lXkjqpMxI&t=12s) :tv:
- [High-Throughput, Thread-Safe, LRU Caching](https://tech.ebayinc.com/engineering/high-throughput-thread-safe-lru-caching/)
- [Sorting 1 million 8-decimal-digit numbers with 1 MB of RAM](https://stackoverflow.com/questions/12748246/sorting-1-million-8-decimal-digit-numbers-with-1-mb-of-ram)
- Null References: The Billion Dollar Mistake - Tony Hoare :tv:
- [Mathematical attack on RSA](https://www.nku.edu/~christensen/Mathematical%20attack%20on%20RSA.pdf)
- [In defence of swap: common misconceptions](https://chrisdown.name/2018/01/02/in-defence-of-swap.html)
- [The Twelve-Factor App](https://12factor.net/)
- [Data Structures & Algorithms I Actually Used Working at Tech Companies](https://blog.pragmaticengineer.com/data-structures-and-algorithms-i-actually-used-day-to-day/)
- [Epigrams on Programming](http://pu.inf.uni-tuebingen.de/users/klaeren/epigrams.html)
- [Choose Boring Technology](https://mcfunley.com/choose-boring-technology)
- [Essays on programming I think about a lot](https://www.benkuhn.net/progessays/) :sparkles:
- [PHP The Wrong Way](https://phpthewrongway.com/)
- [Laws of UX](https://lawsofux.com/)
- [How to stop procrastinating by using the Fogg Behavior Model](https://www.deprocrastination.co/blog/how-to-stop-procrastinating-by-using-the-fogg-behavior-model)
- [lzop vs compress vs gzip vs bzip2 vs lzma vs lzma2/xz benchmark, reloaded](https://stephane.lesimple.fr/blog/lzop-vs-compress-vs-gzip-vs-bzip2-vs-lzma-vs-lzma2xz-benchmark-reloaded/)
- [Andrei Pangin - Everything you wanted to know about Stack Traces and Heap Dumps](https://www.youtube.com/watch?v=FTsAXJdrJbI&t=1s) :tv:

## Fun

- https://turnoff.us
- https://xkcd.com
- https://impurepics.com/
- https://www.commitstrip.com
- [If Programming languages were harry potter characters](http://heeris.id.au/2014/if-programming-languages-were-harry-potter-characters/)

## More Books

### Software Development

- [Coders at Work](https://www.amazon.com/gp/product/1430219483)
- [The Pragmatic Programmer](https://www.amazon.com/Pragmatic-Programmer-Journeyman-Master/dp/020161622X) :sparkles:
- [Hackers: Heroes of the Computer Revolution](https://www.amazon.com/Hackers-Computer-Revolution-Steven-Levy/dp/1449388396)
- [Working Effectively with Legacy Code](https://www.amazon.com/gp/product/0131177052)
- [Programming Pearls](https://www.amazon.com/gp/product/0201657880)
- [The Art of Computer Programming](https://www.amazon.com/gp/product/0201896834)
- [Refactoring: Improving the Design of Existing Code](https://www.amazon.com/gp/product/0201485672)
- [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.com/gp/product/0132350882)
- [Code Complete: A Practical Handbook of Software Construction](https://www.amazon.com/gp/product/0735619670)
- [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612) :sparkles:
- [The Mythical Man-Month](http://www.amazon.in/Mythical-Man-Month-Software-Engineering-Anniversary/dp/0201835959)
- [The Joy of Software Development](https://josd.captnemo.in/content/)

### Lisp

- [Practical Common Lisp](http://www.gigamonkeys.com/book/)
- [The Common Lisp Cookbook](https://lispcookbook.github.io/cl-cookbook/)
- [Common Lisp: A Gentle Introduction to Symbolic Computation](http://www-cgi.cs.cmu.edu/afs/cs.cmu.edu/user/dst/www/LispBook/index.html)

### Random

- [Understanding Message Brokers](http://www.oreilly.com/programming/free/files/understanding-message-brokers.pdf)
- [A handbook for making programming languages](http://www.craftinginterpreters.com/contents.html)
- [Ask HN: What language-agnostic programming books should I read ?](https://news.ycombinator.com/item?id=14486657)
- [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262592)
- [An Illustrated Book of Bad Arguments](https://bookofbadarguments.com/)
- [An illustrated introduction to computational thinking](https://bookofbadchoices.com/index.html#page/3)
- [Atomic Design by Brad Frost](http://atomicdesign.bradfrost.com/)
- https://begriffs.com/posts/2017-04-13-longterm-computing-reading.html
- [What is the single most influential book every programmer should read? [closed]](https://stackoverflow.com/questions/1711/what-is-the-single-most-influential-book-every-programmer-should-read) :books:
- [A Reading List For the Self-Taught Computer Scientist](https://www.reddit.com/r/books/comments/ch0wt/a_reading_list_for_the_selftaught_computer/) :books:
- [SRE Books](https://landing.google.com/sre/books/)

## Courses

- [Computer Systems Security](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-858-computer-systems-security-fall-2014/index.htm)
- [Operating System Engineering](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-828-operating-system-engineering-fall-2012/)
- [Introduction to Algorithms](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/index.htm)
- [Introduction to Computer Science and Programming in Python](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/index.htm)
- [Computer System Engineering](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-033-computer-system-engineering-spring-2009/)
- [CIS 194: Introduction to Haskell (Spring 2013)](http://www.seas.upenn.edu/~cis194/spring13/lectures.html)
- [CS 140: Operating Systems](http://web.stanford.edu/~ouster/cgi-bin/cs140-spring14/lectures.php)
- [Offensive Computer Security](http://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/lectures.html)
- [CS155: Computer and Network Security](https://courseware.stanford.edu/pg/courses/lectures/349991)
- [CIS 194: Introduction to Haskell](http://www.seas.upenn.edu/~cis194/)
- [CS143: Compilers](https://web.stanford.edu/class/archive/cs/cs143/cs143.1128/)
- [CNIT 127: Exploit Development](https://samsclass.info/127/127_S18.shtml)
- [Modern Binary Exploitation](http://security.cs.rpi.edu/courses/binexp-spring2015/)
- [Computer System Engineering](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-033-computer-system-engineering-spring-2018/)
- [Awesome Courses](https://github.com/prakhar1989/awesome-courses)
- [CS6038/CS5138 Malware Analysis, UC](https://class.malware.re/)

## Papers

- [Back to the Future: Lisp as a Base for a Statistical Computing System](https://www.stat.auckland.ac.nz/~ihaka/downloads/Compstat-2008.pdf)
- [How Professional Hackers Understand Protected Code while Performing Attack Tasks](https://pdfs.semanticscholar.org/4bd1/2a9823b55d29a0d75c9ea9c8cd08b6fdca3e.pdf)
- [Papers We Love](https://github.com/papers-we-love) :sparkles:
- [Communicating Sequential Processes](https://spinroot.com/courses/summer/Papers/hoare_1978.pdf) :sparkles:
- [Hints on programming language design](http://flint.cs.yale.edu/cs428/doc/HintsPL.pdf)
- [The Fault Tolerance of Botnets](https://www.dropbox.com/s/rvk6ybbl85zce00/The%20Fault%20Tolerance%20of%20Botnets.pdf?dl=0)
- [Paradigm Shift in Software Development](https://www.dropbox.com/s/db2tbau0jdv9pym/Paradigm%20Exercise.pdf?dl=0)
- [Interpreting the Data: Parallel Analysis with Sawzall](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/9b122a21c1436da94c67a74bfdfba7e57a4d203e.pdf)
