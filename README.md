# Ruslan Kirzhanov

Software architect, ~6 years in commercial engineering. FinTech systems where
correctness matters more than velocity. Deep PostgreSQL internals, actively
moving into Go.

## What I build

High-stakes backend systems with hard failure modes:

- Payment infrastructure, KYC/AML pipelines, antifraud logic
- Distributed services designed for consistency under partial failure
- PostgreSQL at scale: replication topology, lock contention, large-dataset
  performance

Operating at senior++/staff level — owning architecture decisions, not just
implementations.

## AI-augmented engineering

I treat AI tools as a force multiplier for an engineer who already has depth,
not a shortcut around it. In practice this means:

- Durable context engineering: project memory, decision records, feedback
  loops that persist across sessions
- Pattern discipline: Transactional Outbox, Idempotency-Key, RFC 7807,
  hexagonal boundaries — chosen deliberately, not improvised
- World-class defaults over "good enough for now"
- Reviewing AI output with the same bar as a junior PR: compiles, tested,
  no fluff, no comments that restate what the code does

The combination produces more shipped work per decision than either an
AI-skeptic or an AI-maximalist produces alone.

## Current focus

Building **Boologic** — my own company (named after George Boole), a small
series of products in FinTech and privacy infrastructure, with the long
arc aimed at funding philanthropic work.

## Technical surface

**Languages:** Python (deep), Go (growing), SQL (deep)
**Databases:** PostgreSQL (internals), Redis, ClickHouse
**Backend:** FastAPI, Django, Flask, Aiohttp, Celery, Kafka, RabbitMQ
**Infra:** Docker, Kubernetes, GitLab CI, Prometheus, Grafana, OpenTelemetry
**Patterns:** Hexagonal, DDD, Transactional Outbox, Saga, Idempotency-Key,
Circuit Breaker, Backpressure, LISTEN/NOTIFY, CQRS where it earns itself

## Selected experience

**Crypto Story Bank** — currency exchange + KYC service.
Architected the data model, cut p95 query latency 800ms → 150ms, built
role-based access control and antifraud logic.

**Sber** — analytics backend on Flask, Celery, Kafka, ClickHouse.
Dashboards in Apache Superset. PostgreSQL and Redis performance work.

**Ultimate Capital** — LMS platform, payment integrations, APIs for
analytics, CRM, and notifications.

## Contact

- Telegram: [@LJuice](https://t.me/LJuice)
- LinkedIn: [ruslan-kirzhanov](https://www.linkedin.com/in/ruslan-kirzhanov-915839221/)
- Email: recursion198@gmail.com

---

<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZ2dlZ3d0aml5emI2YTl2aXR2c3Y2aWRnenJ5em9tZnM3aHk1YTd4byZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/CuuSHzuc0O166MRfjt/giphy.gif" width="220" alt=""/>
</div>
