<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1B2735,100:2E9EF7&height=200&section=header&animation=fadeIn" />

<h1 align="center">Mohamed Wasim</h1>
<h3 align="center">Backend Engineer — Scalable APIs, Microservices &amp; Event-Driven Systems</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/mohwasim">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:wasimakramuj@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Based_in-India_(GMT%2B5:30)-2E9EF7?style=flat-square" />
  <img src="https://img.shields.io/badge/Available-Remote_%7C_EU_hours_overlap-2ea44f?style=flat-square" />
</p>

<p align="center">
I design and ship backend systems that stay reliable under real production load — REST APIs, event-driven services, and data pipelines built on Java/Spring Boot and Python/FastAPI. I also build full-stack products end-to-end when the problem calls for it.
</p>

---

### Featured Build

**[OrcaChat](https://github.com/Wasims07/OrcaChat)** — a privacy-first AI chat client. Bring your own model key (OpenAI-compatible, Anthropic, Gemini, or local Ollama); everything is stored client-side, encrypted with AES-256-GCM, and the server never persists a single message.

<p align="left">
  <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

- **Zero server-side data retention** — chats and API keys never leave the browser; the backend only proxies model calls.
- **Multi-provider routing** with auto-detection from key prefix, base URL, or model name — OpenAI-compatible APIs, Anthropic, Gemini, and local models.
- **Hardened by default** — CSP, `X-Frame-Options: DENY`, `Referrer-Policy: no-referrer`, Redis-backed sliding-window rate limiting with in-memory fallback.
- File understanding (PDF, DOCX, XLSX) and client-side OCR for images, so text extraction works even with non-vision models.
- Shipped with a real Vitest suite covering storage, crypto round-trips, and retention/pinning logic — [live demo](https://orcachatone.vercel.app).

---

### Impact

- Designed and shipped a **Spring Boot microservice (8 REST endpoints)** for entity management, cutting query response time by **25%** through JPA/PostgreSQL query optimization.
- Prototyped an **event-driven notification pipeline on Kafka**, simulating real-time cross-service communication for a system later adopted into production planning.
- Built **scheduled batch synchronization jobs** to keep internal data consistent with external sources, removing a manual reconciliation step from the team's workflow.
- Maintained **75% test coverage** on services I own, catching regressions before they reached staging.

### Currently

- Deepening distributed-systems and cloud-native architecture patterns (event sourcing, CQRS, service mesh basics)
- Pushing test coverage on production services past 85%
- Open to **remote backend/API contract work and full-time roles**, with working hours that overlap CET/CEST

---

### Core Stack

**Languages & Frameworks**
<p>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
</p>

**Data & Messaging**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
</p>

**Infrastructure & Tooling**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS_EC2-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
</p>

---

### Experience

**Backend Developer — Triton Tech Labs** &nbsp;·&nbsp; 2024 – Present

- Own a Spring Boot microservice handling entity management for internal tooling; reduced average query latency by 25% via index tuning and JPA query rewrites.
- Introduced a Kafka-based proof-of-concept for real-time inter-service notifications, presented to the team as a candidate pattern for the next platform iteration.
- Built and maintain scheduled data-sync jobs (Spring Scheduler) pulling from external sources into the core system.
- Practice test-first development on new endpoints; current suite covers 75% of service logic.

---

### Selected Projects

| Project | What it demonstrates | Stack |
|---|---|---|
| [OrcaChat](https://github.com/Wasims07/OrcaChat) | Full-stack product build — client-side encryption, multi-provider AI routing, security-hardened API layer | Next.js, React 19, TypeScript |
| [Enterprise Microservices Platform](https://github.com/Wasims07/Enterprise-Microservices-Platform) | Service discovery (Eureka), API gateway routing, and Kafka-based async communication across services | Java, Spring Boot, Kafka, Eureka |
| [Weather API Service](https://github.com/Wasims07/weather-api-service) | Caching strategy with Redis, external API integration, clean FastAPI endpoint design | Python, FastAPI, Redis |
| [Employee Management System](https://github.com/Wasims07/Employee-Management-System) | Full CRUD lifecycle with layered architecture (controller/service/repository) | Java, Spring Boot, PostgreSQL, JPA |
| [Music Database Management System](https://github.com/Wasims07/Music-Database-Management-System) | Relational schema design — normalized tables, views, and triggers for data integrity | SQL |

*Each repo README includes setup instructions and, where relevant, the design decisions behind it.*

---

### Education

**B.E., Computer Science and Engineering** — Anna University

---

### Get in Touch

I'm open to backend/API contract work and full-time roles with EU-based teams — happy to jump on a call during CET business hours.

📧 [wasimakramuj@gmail.com](mailto:wasimakramuj@gmail.com) &nbsp;·&nbsp; 💼 [linkedin.com/in/mohwasim](https://www.linkedin.com/in/mohwasim)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2E9EF7,100:1B2735&height=120&section=footer&animation=fadeIn" />
