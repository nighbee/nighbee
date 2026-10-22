# Hi, I'm Almaz Toktassin — Go Backend Engineer

## Payments · Microservices (gRPC, Kafka, PostgreSQL)

Middle Go backend engineer in Almaty, focused on **payment platforms and transaction integrity**:
**double-entry ledger, ACID transactions, idempotency keys, optimistic locking, anti-fraud charging**.
Production Go microservices with **gRPC/Protobuf, Kafka and PostgreSQL**, event-driven flows,
OpenTelemetry tracing, Prometheus/Grafana observability, Docker, Kubernetes (K3s) and GitHub Actions CI/CD.
English C1 · Russian C2 · Kazakh native — open to hybrid work from Kazakhstan and remote worldwide.

📄 **[CV — Go Backend (PDF)](./ToktassinAlmaz_GoBackend_CV.pdf)**

## What I do

- Design payment backends around an atomic ACID double-entry ledger (idempotency, optimistic locking)
- Build Go microservices with gRPC/Protobuf, REST/OpenAPI, WebSockets and event-driven Kafka flows (DLQ, retries)
- Design PostgreSQL schemas (indexing, migrations, pool budgeting) with Redis caching and Pub/Sub/Streams
- Secure services with JWT/OAuth2/RBAC, rate limiting, fail2ban, TLS — plus anti-abuse/anti-fraud controls
- Ship with Docker Compose, Nginx gateways, health/backup routines, staging-first deploys with rollback tags
- Lead small engineering teams: planning, code reviews, release quality

## Professional experience

- **Backend Developer (Contract), Independent — fintech payments** (Feb 2025 – Present, projects partially in parallel)
  - **BrightBund, Technical Team Lead** (Jan – Jul 2026): production Go payments backend (Fiber, PostgreSQL 16 + PostGIS,
    Redis, Kafka, MinIO on GCP) centered on an atomic ACID double-entry ledger with idempotency keys, optimistic locking
    and upfront anti-fraud charging; led 10 backend/Flutter engineers through a 100–200 tester closed beta.
  - **OneBilim Academy, backend/infra owner** (Jul 2026 – Present): Go microservices (Gin/GORM, 18 services, ~150 endpoints)
    for ~2,500 learners and ~2,000 uploads/day; Postgres tuning, pool budgeting, fixed gateway TIME_WAIT/502 at peak.
  - **SalesAI** (Sep – Dec 2025): polyglot microservices (Go/Fiber + Python/FastAPI + TS/Playwright) over gRPC and Redis
    Streams; cut call-analysis time from 30 min to 2 min.
  - **ESG platform, KBTU** (May – Sep 2025): Go/Fiber clean-layered backend, JWT RBAC for 20+ events; manual tracking down 80%.
- **Backend Engineer (AI Systems) — QazCloud** (Jan – Apr 2026): production Go microservice for ITSM ticket
  categorization; human-in-the-loop review with confidence thresholds; thread-safe audit logging + `/stats/failed` monitoring.
- **Open Source Contributor — Amazon OpenSearch** (Mar – Aug 2023): 5 merged pull requests (Java) — bug fixes and
  reliability in a distributed search engine.

## Featured projects

| Project | Focus |
|---|---|
| [social-fintech](https://github.com/nighbee/social-fintech) | Contract fintech backend in Go (BrightBund): double-entry ledger, ACID transactions, Kafka fan-out, Docker/Nginx/fail2ban prod stack. |
| [eventlyBackend](https://github.com/nighbee/eventlyBackend) | Concurrency-safe Go event-booking backend (Fiber, GORM, PostgreSQL, Redis): JWT auth, RBAC, caching, unique-constraint anti-double-booking. |
| [sale1](https://github.com/nighbee/sale1) | Diploma call-analyzer SaaS: Go API orchestrator + Python AI workers + TS automation over gRPC/Redis Streams, observability, PDF/Excel reporting. |
| [Go-blockchain](https://github.com/nighbee/Go-blockchain) | Blockchain implementation in Go — consensus/ledger mechanics from first principles. |
| [GOcourse](https://github.com/nighbee/GOcourse) | Go coursework: language fundamentals through concurrent programs. |
| [indrive](https://github.com/nighbee/indrive) | Go legislative-analysis platform: semantic contradiction/duplicate detection over the national legal corpus. |
| [industrix](https://github.com/nighbee/industrix) | Multi-service Go workspaces system: protobuf/Buf contracts, Docker Compose, infra tooling. |

## Technical skills

**Languages:** Go (primary, Gin/Fiber), SQL, Python, TypeScript
**Backend & Payments:** Microservices, REST, gRPC/Protobuf, OpenAPI/Swagger, event-driven architecture, JWT/OAuth2/RBAC,
Clean/Layered Architecture, double-entry ledger, ACID, idempotency keys, optimistic locking, anti-fraud charging,
concurrency (goroutines, channels, sync primitives)
**Data & Messaging:** PostgreSQL (design, indexing, migrations, tuning, pool budgeting), Redis (caching, Pub/Sub, Streams),
Kafka (fan-out, retries, DLQ), PostGIS, MinIO/S3
**Infrastructure & Quality:** Docker, Docker Compose, Kubernetes (K3s, KEDA), Nginx, GCP, GitHub Actions CI/CD,
Prometheus/Grafana, OpenTelemetry tracing, structured logging, health checks, unit/integration testing
**Security:** bcrypt, TLS/HTTPS, rate limiting, anti-abuse, fail2ban, OWASP basics
**Languages (spoken):** English (C1), Russian (C2), Kazakh (native)

## Education

- **International Engineering and Technological University (METU)** — MSc Software Engineering, 2026–2028
- **Kazakh-British Technical University (KBTU)** — Bachelor of Information Systems, 2022–2026
- **Ozyegin University (Erasmus+ Exchange)** — Computer Science, Istanbul, Jan–Jun 2025

## Explore more

- 📄 [CV — Go Backend (PDF)](./ToktassinAlmaz_GoBackend_CV.pdf)
- 💼 [GitHub repositories](https://github.com/nighbee?tab=repositories)
- 🔗 [LinkedIn](https://www.linkedin.com/in/almaz-toktassin-5405922a9/)
- ✉️ [Email](mailto:almaztoktasin7@gmail.com)
- 💬 [Telegram](https://t.me/ztktsn)

> Open to Middle Go Backend roles — payments/fintech, microservices (gRPC, Kafka, PostgreSQL) — hybrid Almaty/Astana or remote.
