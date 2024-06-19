## System Design

### Guides

- [Metcalfe's law](https://en.wikipedia.org/wiki/Metcalfe%27s_law)
- [Learn how to design large-scale systems](https://github.com/donnemartin/system-design-primer) :sparkles:
- [A Brief History of High Availability](https://www.cockroachlabs.com/blog/brief-history-high-availability/)
- [Introduction to Microservices](https://www.nginx.com/blog/introduction-to-microservices/)
- [What is Kappa Architecture?](http://milinda.pathirage.org/kappa-architecture.com/)
- [Principles of chaos engineering](http://principlesofchaos.org/)
- [Microservices — architecture nihilism in minimalism's clothes](https://vlfig.me/posts/microservices) :sparkles:
- [Failing over without falling over](https://stackoverflow.blog/2020/10/23/adrian-cockcroft-aws-failover-chaos-engineering-fault-tolerance-distaster-recovery/) :zap:
- [Timeouts, retries, and backoff with jitter](https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/)
- [Why are services slow sometimes?](https://dev.to/aws/why-are-services-slow-sometimes-mn3) :zap:
  - [If at first you don't get an answer...](https://dev.to/aws/if-at-first-you-don-t-get-an-answer-3e85)
- [Understanding Connections & Pools](https://sudhir.io/understanding-connections-pools/) :zap: :zap:
- [The Big Little Guide to Message Queues](https://sudhir.io/the-big-little-guide-to-message-queues/)
- [MonolithFirst](https://martinfowler.com/bliki/MonolithFirst.html)
- [A List of Post-mortems!](https://github.com/danluu/post-mortems)
- [Exponential Backoff And Jitter](https://aws.amazon.com/blogs/architecture/exponential-backoff-and-jitter/)
- [What we talk about when we talk about System Design](https://maheshba.bitbucket.io/blog/2023/07/12/Design.html)
- https://systemdesign.one/
- [Real Time Presence Platform System Design](https://systemdesign.one/real-time-presence-platform-system-design/)
- [Live Comment System Design](https://systemdesign.one/live-comment-system-design/)
- [Distributed Counter System Design](https://systemdesign.one/distributed-counter-system-design/)

### Systems

> [(A few) Ops Lessons We All Learn The Hard Way](https://www.netmeister.org/blog/ops-lessons.html)

- [Reddit: How We Built r/Place](https://redditblog.com/2017/04/13/how-we-built-rplace/) :sparkles:
- [Uber: Why Uber Engineering Switched from Postgres to MySQL](https://eng.uber.com/mysql-migration/)
- [Dropbox: How we migrated Dropbox from Nginx to Envoy](https://dropbox.tech/infrastructure/how-we-migrated-dropbox-from-nginx-to-envoy)
- [Cloudflare: How Cloudflare’s Architecture Can Scale to Stop the Largest Attacks](https://www.cloudflare.com/media/pdf/cf-wp-dns-attacks.pdf)
- Making Instagram.com faster
  - [Part 1](https://instagram-engineering.com/making-instagram-com-faster-part-1-f350c8fba0d4) - Prefetching data
  - [Part 2](https://instagram-engineering.com/making-instagram-com-faster-part-2-f350c8fba0d4) - Pushing data directly to the client rather than waiting for the client to request the data
  - [Part 3](https://instagram-engineering.com/making-instagram-com-faster-part-3-cache-first-6f3f130b9669) - Cache-first rendering
  - [Part 4](https://instagram-engineering.com/making-instagram-com-faster-code-size-and-execution-optimizations-part-4-57668be796a8) - Code size and execution optimizations
- [Billions of Messages a Day - Yelp's Real-time Data Pipeline](https://engineeringblog.yelp.com/2016/07/billions-of-messages-a-day-yelps-real-time-data-pipeline.html)
- [The WhatsApp Architecture Facebook Bought For $19 Billion](http://highscalability.com/blog/2014/2/26/the-whatsapp-architecture-facebook-bought-for-19-billion.html)
- [Airbnb: Avoiding Double Payments in a Distributed Payments System](https://medium.com/airbnb-engineering/avoiding-double-payments-in-a-distributed-payments-system-2981f6b070bb)
- [How We Developed DingTalk: Implementing the Message System Architecture](https://www.alibabacloud.com/blog/how-we-developed-dingtalk-implementing-the-message-system-architecture_595905)
- [Intelligent DNS based load balancing at Dropbox](https://dropbox.tech/infrastructure/intelligent-dns-based-load-balancing-at-dropbox)
- [Redis Explained](https://architecturenotes.co/redis/)
- [How Discord Stores Trillions Of Messages](https://discord.com/blog/how-discord-stores-trillions-of-messages)

### Scalability

- [Jeremy Edberg - Scalable Cloud Architectures | Tech Talk](https://www.youtube.com/watch?v=cCAO9moDucI&t=1s) :tv:
- [CS75 (Summer 2012) Lecture 9 Scalability Harvard Web Development](https://www.youtube.com/watch?v=-W9F__D3oY4) :tv: :zap:
- [A Word on Scalability](https://www.allthingsdistributed.com/2006/03/a_word_on_scalability.html)
- [Scalability for Dummies](https://www.lecloud.net/post/7295452622/scalability-for-dummies-part-1-clones) :sparkles:
- [Scalable System Design Patterns](https://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html)
- [Scalable Web Architecture and Distributed Systems](https://www.aosabook.org/en/distsys.html)
- [The Tail at Scale](https://cseweb.ucsd.edu/~gmporter/classes/fa17/cse124/post/schedule/p74-dean.pdf) :page_with_curl:
- [Automating chaos experiments in production](https://arxiv.org/pdf/1905.04648.pdf)
- [Eventually Consistent - Revisited](https://www.allthingsdistributed.com/2008/12/eventually_consistent.html)

### Event driven Architecture

- [Build Services on a Backbone of Events](https://www.confluent.io/blog/build-services-backbone-events/)

### AWS

- [Everything You Need To Know About Networking On AWS](https://grahamlyons.com/article/everything-you-need-to-know-about-networking-on-aws)
- [Deep Dive on Amazon ECS Cluster Auto Scaling](https://aws.amazon.com/blogs/containers/deep-dive-on-amazon-ecs-cluster-auto-scaling/) :sparkles: :construction:
- [Designing scalable API on AWS spot instances](https://blog.adapty.io/designing-scalable-api-on-aws-stop-instance/)
- [Workload isolation using shuffle-sharding](https://aws.amazon.com/builders-library/workload-isolation-using-shuffle-sharding/)
- [The Hitchhiker's Guide to AWS ECS and Docker](https://start.jcolemorrison.com/the-hitchhikers-guide-to-aws-ecs-and-docker/)
- [AWS IAM Policies in a Nutshell](https://start.jcolemorrison.com/aws-iam-policies-in-a-nutshell/)
- [What You Need to Know About IOPS](https://cloudcasts.io/article/what-you-need-to-know-about-iops)
- [Why was a query to my Amazon RDS MySQL DB instance blocked when there is no other active session?](https://aws.amazon.com/premiumsupport/knowledge-center/blocked-mysql-query/)
- [Things you wish you didn't need to know about S3](https://blog.plerion.com/things-you-wish-you-didnt-need-to-know-about-s3/)
- [Intentionally leaking AWS keys](https://brokenco.de/2021/01/15/leaking-aws-keys.html)
- [A Solution to HTTP 502 Errors with AWS ALB](https://www.tessian.com/blog/how-to-fix-http-502-errors/)
- [S3 Express One Zone, Not Quite What I Hoped For](https://jack-vanlightly.com/blog/2023/11/29/s3-express-one-zone-not-quite-what-i-hoped-for)
- [Things you wish you didn't need to know about S3](https://blog.plerion.com/things-you-wish-you-didnt-need-to-know-about-s3)

### Netflix

- [Mastering Chaos - A Netflix Guide to Microservices](https://www.youtube.com/watch?v=CZ3wIuvmHeM) :tv: :sparkles:
- [How we scaled nginx and saved the world 54 years every day](https://blog.cloudflare.com/how-we-scaled-nginx-and-saved-the-world-54-years-every-day)
- [Building fast.com](https://netflixtechblog.com/building-fast-com-4857fe0f8adb)
- [AWS re:Invent 2017: How Netflix Tunes Amazon EC2 Instances for Performance (CMP325)](https://www.youtube.com/watch?v=89fYOo1V2pA) :tv:
- [AWS re:Invent 2015: A Day in the Life of a Netflix Engineer (DVO203)](https://www.youtube.com/watch?v=-mL3zT1iIKw) :tv: :zap:
- [Edge Authentication and Token-Agnostic Identity Propagation](https://netflixtechblog.com/edge-authentication-and-token-agnostic-identity-propagation-514e47e0b602)

### Cloudflare

- [A deep-dive into Cloudflare’s autonomous edge DDoS protection](https://blog.cloudflare.com/deep-dive-cloudflare-autonomous-edge-ddos-protection/)

## Design Patterns

- [The Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
- [DESIGN PATTERNS](https://refactoring.guru/design-patterns)
- [“Don’t Mock What You Don’t Own” in 5 Minutes](https://hynek.me/articles/what-to-mock-in-5-mins/)
- [Semantic Versioning 2.0.0](https://semver.org/)
- [The Duct Tape Programmer](https://www.joelonsoftware.com/2009/09/23/the-duct-tape-programmer/)
- [How To Design A Good API and Why it Matters](https://www.youtube.com/watch?v=heh4OeB9A-c) :tv:
- [The Twelve-Factor App](https://12factor.net/)
- [The Danger of “Simplicity”](https://asthasr.github.io/posts/danger-of-simplicity)
- [Ask HN: “Write your own” or “Build your own” software projects](https://news.ycombinator.com/item?id=16591918)
- [Design Patterns](https://sourcemaking.com/design_patterns) :sparkles:
- [Software Testing Anti-patterns](http://blog.codepipes.com/testing/software-testing-antipatterns.html)
- [Difference b/w Integration and Unit Tests](https://stackoverflow.com/questions/10752/what-is-the-difference-between-integration-and-unit-tests/7876055#7876055)
- [The language of choice](https://codewords.recurse.com/issues/four/the-language-of-choice)
- [Programmer Competency Matrix](http://sijinjoseph.com/programmer-competency-matrix/)

### Caching

- [Constant time implementation of the LFU cache eviction algorithm](https://arpitbhayani.me/blogs/lfu)
- [2Q-cache algorithm for disk-backed databases](https://arpitbhayani.me/blogs/2q-cache/)
- [Writing a very fast cache service with millions of entries in Go](https://allegro.tech/2016/03/writing-fast-cache-service-in-go.html)

### More

- [How we migrated from AWS to GCP with minimal downtime](https://postgresml.org/blog/how-we-migrated-from-aws-to-gcp-with-minimal-downtime?ref=dailydev)
- [Unreliability At Scale](https://blog.dshr.org/2021/06/unreliability-at-scale.html)
- [Unified Streaming And Batch Pipelines At LinkedIn](https://engineering.linkedin.com/blog/2023/unified-streaming-and-batch-pipelines-at-linkedin--reducing-proc)
- [JVM Profiler: An Open Source Tool for Tracing Distributed JVM Applications at Scale](https://eng.uber.com/jvm-profiler/)
- [Making a virtual machine in Google Sheets](https://briansteffens.github.io/2017/07/03/google-sheets-virtual-machine.html)
- [The Life of a Data Byte](https://queue.acm.org/detail.cfm?id=3419941) :sparkles: :zap: :construction:
- [Anything can be a message queue if you use it wrongly enough](https://xeiaso.net/blog/anything-message-queue)
- [High-Throughput, Thread-Safe, LRU Caching](https://tech.ebayinc.com/engineering/high-throughput-thread-safe-lru-caching/)
- [Sorting 1 million 8-decimal-digit numbers with 1 MB of RAM](https://stackoverflow.com/questions/12748246/sorting-1-million-8-decimal-digit-numbers-with-1-mb-of-ram)
- [Building a high performance JSON parser](https://dave.cheney.net/paste/gophercon-sg-2023.html)
- [Riak's Bitcask - A Log-Structured Hash Table for Fast Key/Value Data](https://highscalability.com/riaks-bitcask-a-log-structured-hash-table-for-fast-keyvalue/)

### Books

- Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems

### Papers

- [All you need to know about the Google File System](https://vutr.substack.com/p/i-spent-8-hours-reading-the-paper)
- [Silent Data Corruptions at Scale](https://arxiv.org/pdf/2102.11245)
- [Cores that don’t count](https://dl.acm.org/doi/pdf/10.1145/3458336.3465297)
- [Dynamo: Amazon’s Highly Available Key-value Store ](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
