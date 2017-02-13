##SWOT Analysis

###Strengths
* Lightweight and RESTful, suitable for IoT and Microservices
* Client and libraries available in many languages
* Proven scalability and low resource usage. Public case studies available from users talking about how they are using NATS with 10 Million + concurrent connections with better resource utilization
* Better developer experience, making it attractive for developers wanting to build scalable microservices

###Weakness
* Lack of backend support from modern platforms. Right now Apcera, Pivotal CloudFoundry (experimental support) and few other smaller/niche platforms support this as a messaging layer and there are third party OSS connectors for many other platforms like Kubernetes, Docker, Rancher, etc.. However, having support from platform vendors is needed for wide enterprise adoption
* Not many enterprise focussed features or support for SLAs, making NATS a good platform for only cloud native, IoT and Microservices. This is not really a weakness in the Modern Enterprise context but enterprises having investments in other messaging platforms may not want to use a different platform for modern apps. However, they are working on clustering support for NATS which should make the platform more attractive for enterprises with failover and HA

###Opportunities
* Being a Lightweight RESTful platform and having a good traction for IoT and Microservices use cases may help NATS emerge as the defacto standard for these use cases
* Since NATS is open source, it gives an opportunity to extend the platform capabilities and reach more easily than a proprietary platform

###Threats
* NATS, at this moment, is a single vendor backed OSS project with few contributors in Github. It is important for them to expand and diversify the contributors. They are in the process of streamlining the contribution process and building up documentation for developers
* Lack of a business model around NATS is definitely a threat. The team understands the need and they are exploring various options. Monetizing OSS is difficult but the fact that they have an enterprise grade platform (Apcera) will help them explore interesting opportunities

