# Almaz Toktassin

**Go Backend Developer** · PostgreSQL, Kafka, Redis, gRPC

Almaty, Kazakhstan · +7 706 711 9305 · [almaztok8@gmail.com](mailto:almaztok8@gmail.com) · [github.com/nighbee](https://github.com/nighbee) · [LinkedIn](https://www.linkedin.com/in/almaz-toktassin-5405922a9/) · [t.me/ztktsn](https://t.me/ztktsn)

*Available immediately · Office, hybrid or remote · Kazakh (native), Russian (C2), English (C1)*

PDF: [ToktassinAlmaz_Golang_CV.pdf](./ToktassinAlmaz_Golang_CV.pdf)

## Summary

Go backend developer with 1.5+ years of contract work shipping Go services to production: an EdTech LMS used by ~2,500 learners, a fintech app with a double-entry ledger (idempotency keys, optimistic locking, Kafka with retries) and an AI call-analysis SaaS. Also built a Go LLM service at QazCloud and interned at Huawei Kazakhstan. Looking for a Go team where I can own features end to end and keep growing.

## Skills

- **Go:** Gin, Fiber, GORM, goroutines, channels, context, sync, table-driven tests, layered architecture
- **Backend:** REST, OpenAPI/Swagger, gRPC, WebSockets, JWT/RBAC, microservices, API gateway, idempotency, retries
- **Data:** PostgreSQL (schema design, indexes, migrations, transactions), Redis (cache, Pub/Sub), Kafka, S3/MinIO
- **DevOps:** Docker, Docker Compose, Nginx, Linux, GitHub Actions CI/CD, GCP, Prometheus/Grafana, unit and integration tests
- **Also:** Python (FastAPI), TypeScript, Java (basics); OpenAI (GPT, Whisper, TTS), Gemini, self-hosted LLM (GPT-OSS)

## Experience

### Backend Developer (Contract), independent contracts
**Feb 2025 – Oct 2026 · Remote, Almaty**
*Part-time contracts alongside university; some projects overlapped.*

**OneBilim Academy** (EdTech LMS, Jul – Oct 2026)
- Owned backend and infrastructure in a 2-engineer team for an English-learning LMS in production: ~2,500 active learners, intakes of 400–800 per stream, up to ~2,000 voice-homework uploads a day.
- Built Go services (Gin/GORM) with JWT/RBAC, an API gateway and PostgreSQL schema-per-service; added WebSocket chat over Redis, S3/MinIO uploads and OpenAI Whisper/GPT/TTS for homework checking.
- Ran prod and staging (Docker Compose, Nginx) with backups and rollback; fixed gateway 502s under peak load.

**BrightBund** (Technical Team Lead, social fintech, Jan – Jul 2026)
- Coordinated up to 10 backend and Flutter developers through a closed beta of 100–200 testers: sprint planning, code review, release quality.
- Built the Go backend (Fiber, PostgreSQL + PostGIS, Redis, Kafka, GCP): double-entry ledger with idempotency keys and optimistic locking, geo search, Kafka-based push notifications with retries, rate limiting, CI/CD.

**SalesAI** (call-analysis SaaS, Sep – Dec 2025)
- Built Go API and Python (FastAPI) AI pipeline for sales-call transcription and scoring (WhisperX + Gemini); cut review time per call from ~30 to 2 minutes; integrated telephony, amoCRM and Google Sheets.

**Earlier:** ESG platform for KBTU (Go/Fiber + React, 100+ students, May – Sep 2025); Careerly.ai job matching with Gemini (Top 30 of 200+ teams, Google Firebase Studio Championship Central Asia 2025).

### Service Solution Responsible (Intern), Huawei Kazakhstan
**Jul 2026 – Oct 2026 · MSSD / Services & Software · Almaty (on-site)**
- Point of contact for customers: turned requirements into technical solution proposals and architecture documents for core network and base station projects, using the Huawei configurator.
- Checked customer contracts for compliant and non-compliant requirements together with technical and business teams.

### Backend Engineer, AI Systems, QazCloud
**Jan 2026 – Apr 2026 · Remote (part-time)**
- Worked on ai-glpi, a Go service that sorts IT support tickets (GLPI) with a self-hosted LLM (GPT-OSS 20B).
- Replaced forced auto-classification with human review below a configurable confidence threshold; added a thread-safe audit log and a `/stats/failed` endpoint to monitor pipeline failures.

### Software Engineering Intern (Java), Amazon OpenSearch College Contributor Initiative
**Mar 2023 – Aug 2023 · Remote**
- Selected for a pilot program run by Amazon and Kazakhstan's Ministry of Science and Higher Education (100+ top students nationwide); worked on OpenSearch under the mentorship of Amazon engineers.
- 5 pull requests merged into [OpenSearch](https://github.com/opensearch-project/OpenSearch) (Java): bug fixes and tests, reviewed by the project maintainers.

## Education

- **MSc, Software Engineering** (in progress), International Engineering and Technological University · 2026 – 2028
- **BSc, Information Systems**, Kazakh-British Technical University (KBTU), Almaty · 2022 – 2026
- **Erasmus+ exchange, Computer Science**, Ozyegin University, Istanbul · Spring 2025

## Projects

- [social-fintech](https://github.com/nighbee/social-fintech): BrightBund Go backend (ledger, idempotency, Kafka)
- [sale1](https://github.com/nighbee/sale1): SalesAI call analyzer (Go API + Python AI pipeline)
- [eventlyBackend](https://github.com/nighbee/eventlyBackend): Go event and seat-booking backend (Fiber, GORM, PostgreSQL, Redis, JWT/RBAC)
- [Go-blockchain](https://github.com/nighbee/Go-blockchain): blockchain basics in Go
- [GOcourse](https://github.com/nighbee/GOcourse): Go coursework
