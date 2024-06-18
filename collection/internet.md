## Internet

> [Latency Numbers](https://gist.github.com/jboner/2841832)

### Webservers

- [Apache vs Nginx: Practical Considerations](https://www.digitalocean.com/community/tutorials/apache-vs-nginx-practical-considerations) :hocho:
- [The C10K problem](http://www.kegel.com/c10k.html)
- [How WebSocket server handles multiple incoming connection requests?](https://stackoverflow.com/questions/28516962/how-websocket-server-handles-multiple-incoming-connection-requests)

### Nginx

- [nginx](http://www.aosabook.org/en/nginx.html)
- [Inside NGINX: How We Designed for Performance & Scale](https://www.nginx.com/blog/inside-nginx-how-we-designed-for-performance-scale/)
- [Tuning NGINX for Performance](https://www.nginx.com/blog/tuning-nginx/)
- [Setting up your server for IPv6 (nginx)](https://bubblin.io/blog/ipv6-nginx)

### Web Caching

- [Web Cache - Everything you need to know](http://kamranahmed.info/blog/2017/03/14/quick-guide-to-http-caching/)
- [Cache Docs](https://www.mnot.net/cache_docs/)

### Protocols

- [Network Protocols – Programmer's Compendium](https://www.destroyallsoftware.com/compendium/network-protocols?share_key=97d3ba4c24d21147)

#### HTTP(S)

- [HTTP](https://www.jmarshall.com/easy/http/)
- [Capturing HTTP Packets](https://medium.com/@cjoudrey/capturing-http-packets-the-hard-way-b9c799bfb6)
- [HTTPS in the real world](https://robertheaton.com/2018/11/28/https-in-the-real-world/)
- [How does HTTPS actually work?](https://robertheaton.com/2014/03/27/how-does-https-actually-work/)
- [Designing Headers for HTTP Compression](https://www.mnot.net/blog/2018/11/27/header_compression)
- [HTTP headers for the responsible developer](https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer)
- [Evolution of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/Evolution_of_HTTP)
- [The First Few Milliseconds of an HTTPS Connection](http://www.moserware.com/2009/06/first-few-milliseconds-of-https.html) :sparkles:
- [The HTTP part 1 - Let's start small](http://dyszkiewicz.me/programming/http/server/kotlin/2018/07/31/http-part1.html)
- [How HTTPS works ...in a comic!](https://howhttps.works/)
- [How HTTPS Works in Layman's Terms - TLS 1.2 and 1.3](https://vinta.ws/code/how-https-works-in-laymans-terms-tls-1-2-and-1-3.html)
- [HTTP Caching](https://roadmap.sh/guides/http-caching)
- [HTTP Security Headers - A Complete Guide](https://nullsweep.com/http-security-headers-a-complete-guide/)
- [Reverse Proxy, HTTP Keep-Alive Timeout, and sporadic HTTP 502s](https://iximiuz.com/en/posts/reverse-proxy-http-keep-alive-and-502s/)
- [Extreme HTTP Performance Tuning: 1.2M API req/s on a 4 vCPU EC2 Instance](https://talawah.io/blog/extreme-http-performance-tuning-one-point-two-million/)

##### HTTP/2

- [Journey to HTTP/2](https://kamranahmed.info/blog/2016/08/13/http-in-depth/) :sparkles:
- [The Evolution of HTTP – HTTP/2 Deep Dive](https://www.ably.io/topic/http2)

##### HTTP/3

- [Comparing HTTP/3 vs. HTTP/2 Performance](https://blog.cloudflare.com/http-3-vs-http-2/)
- [HTTP3](https://blog.cloudflare.com/http-3-from-root-to-tip/)
- [QUIC](https://blog.cloudflare.com/the-road-to-quic/)
- [Employing QUIC Protocol to Optimize Uber’s App Performance](https://eng.uber.com/employing-quic-protocol/)
- [HTTP/3: the past, the present, and the future](https://blog.cloudflare.com/http3-the-past-present-and-future/)
- [HTTP/3 Deep Dive](https://www.ably.io/topic/http3)
- [HTTP/3 explained](https://http3-explained.haxx.se/)

#### TLS

- [How does SSL/TLS work?](https://security.stackexchange.com/questions/20803/how-does-ssl-tls-work)
- [The Illustrated TLS Connection](https://tls.ulfheim.net/)
- [The New Illustrated TLS Connection](https://tls13.ulfheim.net/)
- [What is TLS (Transport Layer Security)?](https://www.cloudflare.com/en-gb/learning/ssl/transport-layer-security-tls/)
- [Even faster connection establishment with QUIC 0-RTT resumption](https://blog.cloudflare.com/even-faster-connection-establishment-with-quic-0-rtt-resumption/)
- [A Detailed Look at RFC 8446 (a.k.a. TLS 1.3)](https://blog.cloudflare.com/rfc-8446-aka-tls-1-3/)
- [See this page fetch itself, byte by byte, over TLS](https://subtls.pages.dev/)

#### TCP/UDP

- [Discussion: UDP in web](https://news.ycombinator.com/item?id=13741155)
- [Let's code a TCP/IP stack](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)
- [When TCP sockets refuse to die](https://idea.popcount.org/2019-09-20-when-tcp-sockets-refuse-to-die/)
- [Messing With Telnet](https://jott.live/markdown/telnet_writeup)
- [How TCP Sockets Work](https://eklitzke.org/how-tcp-sockets-work)
- [How Does TCP Work?](https://sookocheff.com/post/networking/how-does-tcp-work/)
- [Once Again on TCP vs UDP](https://accu.org/index.php/journals/2180)
- [Nagle's algorithm](https://en.wikipedia.org/wiki/Nagle%27s_algorithm)
  - [40 millisecond bug](https://vorner.github.io/2020/11/06/40-ms-bug.html)
  - [TCP Performance problems caused by interaction between Nagle’s Algorithm and Delayed ACK](http://www.stuartcheshire.org/papers/NagleDelayedAck/)
- [What every developer should know about TCP](https://robertovitillo.com/what-every-developer-should-know-about-tcp/)
- [What I learned attempting the TCP Reset attack](https://squidarth.com/article/networking/2020/05/03/tcp-resets.html)

#### DNS

- [DNS in One Picture](https://medium.com/@kamranahmedse/dns-in-one-picture-d7f4783db06a)
- [The Web Developer's Guide to DNS](https://rjzaworski.com/2019/04/the-web-developers-guide-to-dns)
- [The uncertainty of measuring the DNS](https://blog.apnic.net/2018/07/18/the-uncertainty-of-measuring-the-dns/)
- [DNS Encryption Explained](https://blog.cloudflare.com/dns-encryption-explained/)
- [A cartoon intro to DNS over HTTPS](https://hacks.mozilla.org/2018/05/a-cartoon-intro-to-dns-over-https/)
- [Hello and welcome to DNS!](https://github.com/ahupowerdns/hello-dns)
- [How DNS Works](https://howdns.works/ep1/)
- [Beyond DNS over HTTPS: Trustless DNS Privacy](https://alyssa.is/proposing-dns-over-tcp-over-tor/)
- [Fun with DNS TXT Records](https://thoughts.theden.sh/posts/dns-txt-record-fun/)

#### BGP

- [What Is BGP? | BGP Routing Explained](https://www.cloudflare.com/learning/security/glossary/what-is-bgp/)
- [THE TWO-NAPKIN PROTOCOL](https://computerhistory.org/blog/the-two-napkin-protocol/?key=the-two-napkin-protocol)
- [Playing battleships over BGP](https://blog.benjojo.co.uk/post/bgp-battleships)

#### Websockets

- [WebSockets for fun and profit](https://stackoverflow.blog/2019/12/18/websockets-for-fun-and-profit/)
- [The WebSocket Protocol: RFC 6455](https://tools.ietf.org/html/rfc6455)
- [How WebSockets Work](https://blog.teamtreehouse.com/an-introduction-to-websockets)
- [HTTP and Websockets: Understanding the capabilities of today’s web communication technologies](https://medium.com/platform-engineer/web-api-design-35df8167460)
- [WebSockets - A Conceptual Deep Dive](https://www.ably.io/topic/websockets)
- [How HTML5 Web Sockets Interact With Proxy Servers](https://www.infoq.com/articles/Web-Sockets-Proxy-Servers/)
- [How Do Websockets Work?](https://sookocheff.com/post/networking/how-do-websockets-work/)
- [What are Long-Polling, Websockets, Server-Sent Events (SSE) and Comet?](https://stackoverflow.com/questions/11077857/what-are-long-polling-websockets-server-sent-events-sse-and-comet)
- [Building realtime apps with Go and WebSockets: client-side considerations](https://www.ably.io/topic/websockets-golang)
- [Websockets 101](https://lucumr.pocoo.org/2012/9/24/websockets-101/)
- [Scalable WebSocket Architecture](https://blog.hathora.dev/scalable-websocket-architecture/)

#### WebRTC

- [WebRTC for the Curious](https://webrtcforthecurious.com/)

### Load Balancing

- [Load Balancing](https://blog.vivekpanyam.com/scaling-a-web-service-load-balancing/)
- [GLB: GitHub's open source load balancer](https://githubengineering.com/glb-director-open-source-load-balancer/)
- [What Is Load Balancing?](https://www.nginx.com/resources/glossary/load-balancing/)
- [Understanding Nginx HTTP Proxying, Load Balancing, Buffering, and Caching](https://www.digitalocean.com/community/tutorials/understanding-nginx-http-proxying-load-balancing-buffering-and-caching)
- [Introduction to modern network load balancing and proxying](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236)
- [Load Balancing TLS Connections: Tradeoffs](https://er4hn.info/blog/2023.02.18-tls-load-balancer/)

### NAT

- [How NAT traversal works](https://tailscale.com/blog/how-nat-traversal-works/)
- [NAT Slipstreaming](https://samy.pl/slipstream/)

### Random

- [The future of the open internet](https://medium.freecodecamp.com/inside-the-invisible-war-for-the-open-internet-dd31a29a3f08)
- [What happens when...](https://github.com/alex/what-happens-when) :sparkles::zap:
- [How Wi-Fi Works](http://www.verizoninternet.com/bookmark/how-wifi-works/)
- [How Does the Internet Work?](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm) :page_with_curl:
- [The Law of Leaky Abstractions](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/) :sparkles:
- [How to crawl a quarter billion webpages in 40 hours](http://www.michaelnielsen.org/ddi/how-to-crawl-a-quarter-billion-webpages-in-40-hours/)
- [The world in which IPv6 was a good design](https://apenwarr.ca/log/20170810)
- [The Non-complexity of /etc/nsswitch.conf](https://developers.redhat.com/blog/2018/11/26/etc-nsswitch-conf-non-complexity/) :sparkles:
- [What is Envoy](https://www.envoyproxy.io/docs/envoy/latest/intro/what_is_envoy)
- [High Performance Browser Networking](https://hpbn.co/) :books:
- [HAProxy](http://www.haproxy.org/)
- [Kerberos: The Network Authentication Protocol](https://web.mit.edu/kerberos/)
- [curl HTTP cheat sheet](https://curl.github.io/curl-cheat-sheet/http-sheet.html)
- [cURL security anti-patterns](https://blog.pan-net.cloud/posts/curl-security-anti-patterns/)
- [Staying out of TTL hell](http://calpaterson.com/ttl-hell.html)
- [Stateful vs Stateless Authentication](https://www.openidentityplatform.org/blog/stateless-vs-stateful-authentication)
- [How to win at CORS](https://jakearchibald.com/2021/cors/)
- [The perils of the “real” client IP](https://adam-p.ca/blog/2022/03/x-forwarded-for/)

### Networking Books :books:

- [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html)
- [Understanding IP Addressing: Everything You Ever Wanted To Know](http://pages.di.unipi.it/ricci/501302.pdf)
- [Kurose and Ross - Top Down Networking](http://amzn.in/d/3S7Wd4s)
- TCP/IP Illustrated
