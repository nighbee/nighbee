# Hi, I'm Almaz Toktassin

### Go Backend Developer · PostgreSQL, Kafka, Redis, gRPC

Go backend developer in Almaty with 1.5+ years of contract work shipping Go services to production: an EdTech LMS used by ~2,500 learners, a fintech app with a double-entry ledger (idempotency keys, optimistic locking, Kafka with retries) and an AI call-analysis SaaS. I also built a Go LLM service at QazCloud and interned at Huawei Kazakhstan.

Looking for a Go team where I can own features end to end and keep growing.

**Available immediately** · office, hybrid or remote · Kazakh (native), Russian (C2), English (C1)

📄 **[CV (PDF, English)](./ToktassinAlmaz_Golang_CV.pdf)**

## Experience

**Backend Developer (Contract)**, independent contracts · Feb 2025 – Oct 2026 · remote, Almaty
<sub>Part-time contracts alongside university; some projects overlapped.</sub>

- **OneBilim Academy** (EdTech LMS, Jul – Oct 2026)
  Owned backend and infrastructure in a 2-engineer team: ~2,500 active learners, intakes of 400–800 per stream, up to ~2,000 voice-homework uploads a day. Go services (Gin/GORM) with JWT/RBAC, an API gateway and PostgreSQL schema-per-service; WebSocket chat over Redis, S3/MinIO uploads, OpenAI Whisper/GPT/TTS for homework checking. Ran prod and staging (Docker Compose, Nginx) with backups and rollback; fixed gateway 502s under peak load.
- **BrightBund** (Technical Team Lead, social fintech, Jan – Jul 2026)
  Coordinated up to 10 backend and Flutter developers through a closed beta of 100–200 testers. Built the Go backend (Fiber, PostgreSQL + PostGIS, Redis, Kafka, GCP): double-entry ledger with idempotency keys and optimistic locking, geo search, Kafka-based push notifications with retries, rate limiting, CI/CD.
- **SalesAI** (call-analysis SaaS, Sep – Dec 2025)
  Go API and Python (FastAPI) AI pipeline for sales-call transcription and scoring (WhisperX + Gemini); cut review time per call from ~30 to 2 minutes; integrated telephony, amoCRM and Google Sheets.
- **Earlier:** ESG platform for KBTU (Go/Fiber + React, 100+ students, May – Sep 2025); Careerly.ai job matching with Gemini (Top 30 of 200+ teams, Google Firebase Studio Championship Central Asia 2025).

**Service Solution Responsible (Intern)**, Huawei Kazakhstan, MSSD / Services & Software · Jul – Oct 2026 · Almaty
Point of contact for customers: turned requirements into technical solution proposals and architecture documents for core network and base station projects; checked customer contracts for compliant and non-compliant requirements.

**Backend Engineer, AI Systems**, QazCloud · Jan – Apr 2026 · remote, part-time
ai-glpi, a Go service that sorts IT support tickets (GLPI) with a self-hosted LLM (GPT-OSS 20B). Replaced forced auto-classification with human review below a confidence threshold; added a thread-safe audit log and a `/stats/failed` endpoint to monitor pipeline failures.

**Open Source Contributor (Intern)**, Amazon OpenSearch Contributor Initiative · Mar – Aug 2023 · remote
5 merged pull requests to OpenSearch (Java): bug fixes and tests, through code review with maintainers.

## Skills

**Go:** Gin, Fiber, GORM, goroutines, channels, context, sync, table-driven tests, layered architecture
**Backend:** REST, OpenAPI/Swagger, gRPC, WebSockets, JWT/RBAC, microservices, API gateway, idempotency, retries
**Data:** PostgreSQL (schema design, indexes, migrations, transactions), Redis (cache, Pub/Sub), Kafka, S3/MinIO
**DevOps:** Docker, Docker Compose, Nginx, Linux, GitHub Actions CI/CD, GCP, Prometheus/Grafana, unit and integration tests
**Also:** Python (FastAPI), TypeScript, Java (basics); OpenAI (GPT, Whisper, TTS), Gemini, self-hosted LLM (GPT-OSS)

## Projects

| Project | What it is |
|---|---|
| [social-fintech](https://github.com/nighbee/social-fintech) | BrightBund Go backend: double-entry ledger, idempotency, optimistic locking, Kafka notifications with retries |
| [sale1](https://github.com/nighbee/sale1) | SalesAI call analyzer: Go API + Python (FastAPI) AI pipeline, WhisperX + Gemini |
| [eventlyBackend](https://github.com/nighbee/eventlyBackend) | Go event and seat-booking backend: Fiber, GORM, PostgreSQL, Redis, JWT/RBAC, Docker Compose |
| [Go-blockchain](https://github.com/nighbee/Go-blockchain) | Blockchain basics in Go, written from scratch |
| [GOcourse](https://github.com/nighbee/GOcourse) | Go coursework, from fundamentals to concurrency |

## Education

- **MSc, Software Engineering** (in progress), International Engineering and Technological University · 2026 – 2028
- **BSc, Information Systems**, Kazakh-British Technical University (KBTU), Almaty · 2022 – 2026
- **Erasmus+ exchange, Computer Science**, Ozyegin University, Istanbul · Spring 2025

## Contact

✉️ [almaztok8@gmail.com](mailto:almaztok8@gmail.com) · 💬 [t.me/ztktsn](https://t.me/ztktsn) · 🔗 [LinkedIn](https://www.linkedin.com/in/almaz-toktassin-5405922a9/) · 📞 +7 706 711 9305
