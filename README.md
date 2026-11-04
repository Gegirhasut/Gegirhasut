# Senior Software Engineer | Backend, Fintech & AI-Powered Products

I'm **Maxim Popelnitskiy**, a software engineer with **20+ years of professional
experience** building backend systems, payment integrations and production
applications. My deepest commercial expertise is **PHP/Laravel**, APIs, databases
and distributed services. I build complete products, from architecture and
implementation through deployment and maintenance.

My independent work extends that foundation into Python AI backends, Rust and
Android. AI coding agents are part of my development workflow; I remain responsible
for architecture, code review, testing and the systems I ship.

## Professional Engineering Impact

- **Fintech performance:** made trading CRM pages **30x faster** and critical APIs
  **10x faster** through PHP backend, SQL query and index optimization.
- **High-load Laravel systems:** designed and implemented SSO for an iGaming/payments
  platform with **15M+ users**; reduced critical business flow latency from
  **1–2 minutes to ~3 seconds** through SQL and backend optimization.
- **Payments and transactional processing:** built queued bonus payouts for
  **up to 100K users per run**; contributed to crypto, bank-transfer and payment
  aggregator integrations with webhooks and asynchronous processing.
- **Technical leadership:** managed **3 developers**, owning CRM performance and
  technical decisions; led a **PHP 5 → PHP 7** migration with **zero critical
  production incidents**.
- **Release engineering:** led **5 QA engineers** and automated build verification
  in **15 minutes**, replacing **~7 working days of manual testing per engineer**;
  integrated automated tests into CI.

The public projects below demonstrate engineering approaches and newer independent
work; they are not presented as the source code of confidential commercial systems.

## Selected Engineering Work

### [Solana Card Escrow](https://github.com/Gegirhasut/solana-card-escrow)
**Payment lifecycle and reconciliation · Rust/Anchor, Python/FastAPI, PostgreSQL, Redis**

An escrow reference implementation connecting authorization holds to clearing,
reversals and refunds. I built the on-chain program and backend, including
idempotent operations, timeout compensation and reconciliation across chain,
database and issuer records. [Verified CI](https://github.com/Gegirhasut/solana-card-escrow/actions/runs/37640523577)
passed 69 program tests and 113 backend tests. **Simulated issuer and devnet
demonstration; not a live card program or audited financial product.**

### [Paystream](https://github.com/Gegirhasut/paystream)
**Asynchronous payments · Python/FastAPI, PostgreSQL, RabbitMQ**

A payment-processing reference service built around a transactional outbox,
idempotent requests, serialized processing and signed merchant webhooks. I addressed
broker outages, ambiguous gateway outcomes, retry exhaustion and recovery of
stalled payments. [Verified CI](https://github.com/Gegirhasut/paystream/actions/runs/38683774498)
passed 195 tests with real PostgreSQL and RabbitMQ. **The payment gateway is simulated.**

### [Notification Service](https://github.com/Gegirhasut/notification-service)
**Reliable message processing · Python/FastAPI, PostgreSQL, RabbitMQ, Redis**

An SMS/email dispatch reference service with priority queues, persistent status
history, request deduplication, bounded retries and a recovery sweeper. I separated
API, dispatch and receipt handling, with integration tests against real infrastructure.
**Providers are mocked; durable end-to-end duplicate prevention requires
provider-side idempotency.**

### [RAG Agents](https://github.com/Gegirhasut/rag-agents)
**Document retrieval and AI backends · Python/FastAPI, Celery, Qdrant, PostgreSQL**

An experimental document-question-answering system with structural chunking,
background ingestion, isolated knowledge bases and streamed answers with source
references. I built the retrieval pipeline, evaluation harness and observability
to inspect retrieval quality, failure recovery and model behavior. **Independent
portfolio project; the README distinguishes implemented work from the roadmap.**

### [roughroute](https://github.com/Gegirhasut/roughroute)
**Offline routing · Rust, OpenStreetMap, WebAssembly, UniFFI/Kotlin**

A shared routing core for CLI, browser and native Android integration. I built OSM
preprocessing, compact binary graphs, A* routing and edge snapping, with property
and golden tests and documented memory-optimization work. **Approximate routes for
playback and related applications; driving restrictions are deliberately out of scope.**

### [Route Spoofer](https://github.com/Gegirhasut/route-spoofer)
**Published Android product · Kotlin, Capacitor, JavaScript**

A developer and QA tool for reproducible location scenarios. I built native
foreground-service playback, a separately tested route engine and the bridge from
the route editor to Android mock-location providers. **Publicly released on
[Google Play](https://play.google.com/store/apps/details?id=com.routespoofer.app),
with MIT-licensed source.**

**Additional PHP work:** [Laravel redirect guard](https://github.com/Gegirhasut/laravel-post-login-redirect-guard)
explores safe post-login redirects across user sessions;
[Doctrine deletion-module review](https://github.com/Gegirhasut/deletion-module-review)
shows code review, architectural reasoning and executable defect reproductions.
These are focused engineering samples, not claims about commercial deployments.

## Core Technical Expertise

**Professional foundation**

- **Backend and architecture:** PHP 8.x, Laravel, Symfony, REST APIs, database design
  and backend service architecture.
- **Fintech and distributed systems:** payment integrations, event-driven workflows,
  asynchronous processing, MySQL, PostgreSQL, Redis and RabbitMQ.
- **Infrastructure and reliability:** Linux, Docker, CI/CD, automated testing,
  deployment and ongoing production maintenance.

**Newer independent engineering work**

- **AI and automation:** Python, FastAPI, LLM APIs, document ingestion, vector retrieval,
  evaluation and AI-assisted development.
- **Systems and cross-platform development:** Rust, WebAssembly, Solana/Anchor,
  Kotlin/Android and Capacitor; independent mobile games and software products.

## Independent Products

- **[QAProvider](https://qaprovider.com)** — live crowdtesting platform connecting
  product teams with testers on real devices. Product website; source is not
  published in this portfolio.
- **[Route Spoofer](https://play.google.com/store/apps/details?id=com.routespoofer.app)** —
  published Android app, with [public source](https://github.com/Gegirhasut/route-spoofer).

## Availability & Contact

Open to **European remote roles and B2B contracts** in senior backend engineering,
fintech/payments, technical leadership and product/founding engineering, including
applied AI backend work.

Contact: [gegirhasut@gmail.com](mailto:gegirhasut@gmail.com) ·
[Telegram](https://t.me/gegirhasut)
