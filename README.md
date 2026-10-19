<p align="center">
<img src="assets/banner.svg" width="100%" alt="Rodrigo Dantas. Senior Software Engineer, Tech Lead, Solopreneur. Software that earns its place in production." />
</p>

**Senior Software Engineer & Tech Lead** with **10 years building software**, after five in systems analysis and infrastructure. Currently at **FiServ via Go2Win**, working on banking operations and financial compliance.

I build with Java, Spring, and Python, and work across the stack when the problem calls for it. Experience across Brazil and the US in banking, fintech, compliance, retail, travel, insurtech, and SaaS.

São Paulo, Brazil · GMT-3 · Portuguese **native** · English **fluent** · Spanish **advanced**

<p>
<a href="https://calendar.app.google/R4jWYVHJgZodVK147"><img src="assets/book-call.svg" width="124" height="44" alt="Book a call with Rodrigo" /></a>
<a href="mailto:rodrigo.dantas@hustletech.dev"><img src="assets/email.svg" width="124" height="44" alt="Email Rodrigo Dantas" /></a>
</p>

[Experience](#experience) · [HustleTech](#hustletech) · [Projects](#projects) · [Engineering](#engineering) · [Education](#education--speaking) · [Connect](#connect) · [Holocrons](#holocrons--by-the-numbers)

<p align="center">
<a href="#engineering"><img src="assets/talk-engineering.svg" width="270" alt="For engineers: explore architecture, systems, APIs, and practical engineering tradeoffs." /></a>
<a href="#experience"><img src="assets/hire-an-engineer.svg" width="270" alt="For recruiters: see senior engineering experience, delivery, and technical ownership." /></a>
<a href="#hustletech"><img src="assets/technical-cofounder.svg" width="270" alt="For founders and partners: explore HustleTech and my experience owning product architecture and delivery." /></a>
</p>

## Experience

### FiServ · via Go2Win

**Senior Software Engineer, Operations** · Oct 2024 - Present

- Banking and compliance APIs, with end-to-end transaction and incident investigation.
- **Average triage reduced from ~60 to ~20 minutes** using LLM-assisted investigation, with human-reviewed decisions.

### KIS Solutions

**Senior Software Engineer** · Sep 2022 - Sep 2024

- Full-stack web and mobile delivery across **5 client projects**, within a team of **8 engineers**, including CDC/ETL pipelines.
- Mentored **3 juniors who progressed to mid-level**, with PR reviews alongside senior architects and shared technical ownership.

### MetalToad

**Senior Software Engineer** · Jun 2021 - Aug 2022

- Software delivery for multiple US clients.
- **Salesforce Apex → RabbitMQ → Java/Spring** integration for notifications.

### Via Varejo (Casas Bahia) · via Opah

**Technical Lead** · May 2020 - Apr 2021

- Technical leadership for **digital insurance embedded in retail checkout**.
- Policy issuance, digital signatures and evidence, authentication, and an accessible customer experience.

### UOL · via Opah

**Senior Software Engineer** · Oct 2019 - May 2020 · São Paulo, Brazil

- Supported payment services, UOL Mail, online antivirus, and antifraud products.
- Built and maintained **Java and Apache Camel integrations**, working with Kotlin, Quarkus, and TDD.

### CVC · via Opah

**Senior Java Developer** · Mar 2019 - Sep 2019 · São Paulo, Brazil

- Built the **Java/Spring backend for airline package sales**.
- An ETL/Kafka pipeline synchronized a saturated legacy Oracle database with MongoDB instances, directing frequent reads to MongoDB while retaining writes in Oracle.

### Transire (ITBAM)

**Software Developer** · Jul 2018 - Feb 2019 · São Paulo, Brazil

- **PedeJa:** a food-ordering and delivery platform built with Java/Spring.
- **Ghost Market:** checkout-free retail using Node.js and RFID to bill customers as they walked out.

### Tap4 Mobile

**Software Developer** · Sep 2016 - Jun 2018 · São Paulo, Brazil

- Integrated CRM data for an events app, segmenting customers by age, peak days, and payment method in **Angular 2 dashboards**.
- Built incident-monitoring alert screens and an Android app for Musashi.

## HustleTech

**Founder & sole engineer · 2016 - Present**

HustleTech is **my solopreneur company**. I've independently developed **3 apps and 2 games**, from concept to implementation, working **outside business hours** alongside my engineering career. My full-time role remains my professional priority.

### Products in development

- **Condo:** multi-tenant B2B SaaS for Brazilian condominium management.
- **Ardha:** single-tenant B2C tarot platform.

### Architecture & delivery

- **Platform:** Java/Spring Boot modular monoliths on GCP Cloud Run; React and React Native clients; PostgreSQL and Redis. Terraform and GitHub Actions support delivery.
- **Data & access:** database-enforced tenancy constraints, Redis-backed RBAC, and an LGPD-aware identity model.
- **Engineering automation:** LLM-powered agents assist testing, architecture review, vulnerability scanning, and code quality. Design, implementation, and delivery are part of the same ownership loop.

[Explore HustleTech →](https://hustletech.dev/)

## Projects

Public repositories to explore the decisions, architecture, and code.

### [LLM Gateway ↗](https://github.com/napalm23zero/llm-gateway)

A Python/FastAPI experiment in **semantic caching and correctness**. Streaming responses, deterministic cache safeguards, routing, fallback, and observability. Benchmark work is in progress.

`Python` `FastAPI` `PostgreSQL / pgvector` `Redis` `SSE`

### [Event-Driven Orders Platform ↗](https://github.com/napalm23zero/lab-event-driven-orders-platform)

An architectural lab exploring **SAGA, Outbox, and CDC** with Debezium, plus observability through OpenTelemetry and Grafana. AWS infrastructure is described with Terraform.

`Kafka` `Debezium` `PostgreSQL` `OpenTelemetry` `Terraform`

### Experiments & roadmap

These are **in progress or planned**; the scope below describes the intended work.

#### Distributed Systems Playground · In progress

Reference architectures for **event sourcing, CQRS, and saga orchestration**, with production patterns, tests, benchmarks, and documentation.

`Java · Spring · Kafka · PostgreSQL`

#### Opinionated Backend Starter · Coming soon

A backend foundation covering **authentication, observability, CI/CD, and multi-tenancy**.

`NestJS · TypeScript · Docker · GCP`

#### LLM Agent Reference Stack · Coming soon

Production patterns for **tool calling, evals, fallback strategies, and cost controls**. Demos are not deployments.

`Python · FastAPI · LangChain · Vector DBs`

#### Edge + Cloud IoT Stack · Planned

An edge-to-cloud reference stack that goes beyond a blinking LED.

`ESP32 · Python · GCP IoT · MQTT`

## Engineering

### Approach & collaboration

- **Architecture follows the constraints:** microservices, modular monoliths, event-driven systems, CDC/ETL, and multi-tenant SaaS. Business needs and operational tradeoffs guide the design.
- **Leadership stays hands-on:** clear technical direction, practical feedback, and shared ownership.
- **Communication connects the work:** technical and stakeholder conversations with teams in the US, Europe, Mexico, Argentina, and Colombia.

Java, Spring, and Python are my core backend tools. React, Next.js, and React Native support full-stack delivery; APIs, messaging, observability, and infrastructure connect the pieces.

### Languages

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="34" height="34" alt="Java" title="Java"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="34" height="34" alt="Python" title="Python"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="34" height="34" alt="TypeScript" title="TypeScript"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="34" height="34" alt="JavaScript" title="JavaScript"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="34" height="34" alt="Node.js" title="Node.js"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="34" height="34" alt="Go" title="Go"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" width="34" height="34" alt="Kotlin" title="Kotlin"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="34" height="34" alt="C#" title="C#"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="34" height="34" alt="C++" title="C++"/>
</p>

Java · Python · TypeScript · JavaScript · Node.js · Go · Kotlin · C# · C++

### Backend, web & mobile

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="34" height="34" alt="Spring" title="Spring"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/quarkus/quarkus-original.svg" width="34" height="34" alt="Quarkus" title="Quarkus"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" width="34" height="34" alt="NestJS" title="NestJS"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="34" height="34" alt="React" title="React"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" width="34" height="34" alt="Angular" title="Angular"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="34" height="34" alt="Next.js" title="Next.js"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="34" height="34" alt="FastAPI" title="FastAPI"/>
</p>

Spring · Quarkus · NestJS · React · Angular · Next.js · FastAPI

### Cloud & delivery

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="34" height="34" alt="GCP" title="Google Cloud"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="34" height="34" alt="AWS" title="AWS"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width="34" height="34" alt="Azure" title="Azure"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="34" height="34" alt="Docker" title="Docker"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="34" height="34" alt="Kubernetes" title="Kubernetes"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" width="34" height="34" alt="Terraform" title="Terraform"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jenkins/jenkins-original.svg" width="34" height="34" alt="Jenkins" title="Jenkins"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" width="34" height="34" alt="GitHub Actions" title="GitHub Actions"/> <img src="https://cdn.simpleicons.org/nginx/009639" width="34" height="34" alt="NGINX" title="NGINX"/> <img src="https://cdn.simpleicons.org/redhatopenshift/EE0000" width="34" height="34" alt="OpenShift" title="Red Hat OpenShift"/>
</p>

Google Cloud · AWS · Azure · Docker · Kubernetes · Terraform · Jenkins · GitHub Actions · NGINX · Red Hat OpenShift

### Data & integration

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="34" height="34" alt="PostgreSQL" title="PostgreSQL"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="34" height="34" alt="MongoDB" title="MongoDB"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="34" height="34" alt="Redis" title="Redis"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="34" height="34" alt="MySQL" title="MySQL"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" width="34" height="34" alt="Oracle / PL/SQL" title="Oracle / PL/SQL"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-original.svg" width="34" height="34" alt="SQL Server" title="SQL Server"/> <img src="https://dbdb.io/media/logos/firebird.png" width="34" height="34" alt="Firebird" title="Firebird"/> <img src="https://discover.strongdm.com/hubfs/ibm-db2-logo.png" width="34" height="34" alt="IBM DB2" title="IBM DB2"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" width="34" height="34" alt="Apache Kafka" title="Apache Kafka"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rabbitmq/rabbitmq-original.svg" width="34" height="34" alt="RabbitMQ" title="RabbitMQ"/> <img src="https://cdn.simpleicons.org/apache/D22128" width="34" height="34" alt="Apache Camel" title="Apache Camel"/>
</p>

PostgreSQL · MongoDB · Redis · MySQL · Oracle / PL/SQL · SQL Server · Firebird · IBM DB2 · Apache Kafka · RabbitMQ · Apache Camel

### AI & machine learning

<p>
<img src="https://static.freepnglogo.com/images/all_img/1702059841openai-icon-png.png" width="34" height="34" alt="OpenAI" title="OpenAI / LLM Agents"/> <img src="https://cdn.simpleicons.org/anthropic/D97757" width="34" height="34" alt="Anthropic" title="Anthropic / Claude"/> <img src="https://cdn.simpleicons.org/langchain/1C3C3C" width="34" height="34" alt="LangChain" title="LangChain / RAG"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="34" height="34" alt="Pandas" title="Pandas"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="34" height="34" alt="NumPy" title="NumPy"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="34" height="34" alt="TensorFlow" title="TensorFlow"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="34" height="34" alt="PyTorch" title="PyTorch"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/elasticsearch/elasticsearch-original.svg" width="34" height="34" alt="Elasticsearch" title="Vector DBs (Elasticsearch)"/>
</p>

OpenAI / LLM Agents · Anthropic / Claude · LangChain / RAG · Pandas · NumPy · TensorFlow · PyTorch · Vector DBs (Elasticsearch)

### Operating systems & hardware

<p>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="34" height="34" alt="Linux" title="Linux"/> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/UbuntuCoF.svg/3840px-UbuntuCoF.svg.png?utm_source=commons.wikimedia.org&utm_campaign=index&utm_content=thumbnail" width="34" height="34" alt="Ubuntu" title="Ubuntu"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/archlinux/archlinux-original.svg" width="34" height="34" alt="Arch Linux" title="Arch Linux"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/debian/debian-original.svg" width="34" height="34" alt="Debian" title="Debian"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/raspberrypi/raspberrypi-original.svg" width="34" height="34" alt="Raspberry Pi" title="Raspberry Pi"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" width="34" height="34" alt="Arduino" title="Arduino / ESP32"/>
</p>

Linux · Ubuntu · Arch Linux · Debian · Raspberry Pi · Arduino / ESP32

## Education & speaking

### Education & direction

**B.Sc. Computer Science**, Universidade Estácio, São Paulo · Jan 2023 - Jun 2026

Coursework in algorithms, data structures, operating systems, networks, and software engineering, with applications built in Java, Python, and C++.

Building toward **Senior Software Architect** through complex projects, continued learning, and certifications.

### Technical talks

- **2021:** *MongoDB: What Problems Does It Actually Solve?* · Universidade Estácio.
- **2020:** *Best Practices in RESTful API Development with Node.js and Swagger* · Universidade Estácio.

## Connect

Engineering conversations, full-time opportunities, and thoughtful technical cofounder discussions. Tell me what you're building and where I could help.

**[rodrigo.dantas@hustletech.dev](mailto:rodrigo.dantas@hustletech.dev)** · **[Book a call](https://calendar.app.google/R4jWYVHJgZodVK147)**

[LinkedIn](https://www.linkedin.com/in/dantas-rodrigo) · [HustleTech](https://hustletech.dev/) · [Medium](https://medium.com/@napalm23zero) · [Dev.to](https://dev.to/napalm23zero) · [Twitter / X](https://twitter.com/napalm23zero)

Writing about LLM-assisted engineering, personal products, and the engineering decisions that matter.

## Holocrons / by the numbers

### GitHub activity

<div align="center">

<a href="https://github.com/napalm23zero">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=napalm23zero&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true&bg_color=10151d&title_color=df5b68&icon_color=df5b68&text_color=d4d4d4&ring_color=df5b68" alt="GitHub stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=napalm23zero&layout=compact&theme=radical&hide_border=true&bg_color=10151d&title_color=df5b68&text_color=d4d4d4&langs_count=10" alt="Top languages"/>
</a>

<br><br>

<a href="https://git.io/streak-stats">
  <img src="https://streak-stats.demolab.com?user=napalm23zero&theme=radical&hide_border=true&background=10151d&ring=df5b68&fire=df5b68&currStreakLabel=df5b68&sideLabels=d4d4d4&dates=a8a29e&stroke=2a0e0e&currStreakNum=d4d4d4&sideNums=d4d4d4" alt="GitHub streak"/>
</a>

</div>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=napalm23zero&style=flat-square&color=9D2933&label=profile+views&labelColor=0d1117" alt="Profile views" />
<img src="https://img.shields.io/github/followers/napalm23zero?style=flat-square&color=9D2933&labelColor=0d1117&label=followers" alt="GitHub followers" />
</p>

### Historical snapshots & developer folklore

Languages cover the last five years across roles. Commit times and operating systems retain the historical snapshot; the coffee, gaming, and debugging counters are developer folklore.

<p align="center">
<img src="assets/holocrons-languages.svg" width="400" alt="Language snapshot: Java 32%, Python 17%, TypeScript 13%, JavaScript and SQL 9% each, Kotlin 6%, Go 5%, Bash 4%, Groovy and C# 3%, other 2%." />
<img src="assets/holocrons-rhythm.svg" width="400" alt="Commit time snapshot: dawn 26.8%, morning 13.1%, afternoon 19.6%, evening 24%, night 23.5%." />
<br>
<img src="assets/holocrons-systems.svg" width="400" alt="Operating system snapshot: Linux 64%, Windows 20.4%, macOS 15.4%." />
<img src="assets/holocrons-personal.svg" width="400" alt="Developer folklore: coffee, gaming, sleep deprivation, StackOverflow, bugs, debugging, and one very close call with rm." />
</p>

<p align="center"><sub>Stay curious. Own the tradeoffs. Ship things that matter.</sub></p>
