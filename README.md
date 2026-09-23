# Abimbola Alexander Omoyola

**Full-Stack Software / Platform Engineer** — React • Node.js • Python • Automation

Nine years turning requirements into working systems: APIs, automation, cloud
infrastructure and the AI workflows on top. Enterprise customers at Persado and
Microsoft, plus a set of products I design, ship and operate myself.

Based in Allen, TX (Dallas–Fort Worth) · Open to remote

[Portfolio](https://omoyola.com) · [LinkedIn](https://www.linkedin.com/in/abimbola-omoyola-825875285/) · [Email](mailto:xanderabim@gmail.com)

---

## What I'm building

### [Plus234Feed](https://plus234feed.com) — Nigerian news and data-intelligence platform

Designed, built and operated solo. Nigerian market, macro and civic data is
scattered across publishers, regulators and PDFs, and most of it is stale by the
time anyone can use it — this keeps it current and serves it fast from the edge.

- FastAPI backend, **200+ endpoints** across 30+ route modules: articles, auth, NGX market data, CBN rates, FX, NBS statistics, legislators, newsletters
- **36 scheduled GitHub Actions pipelines** running Python scrapers and ETL into Supabase Postgres, across separate dev and production environments
- **13 Cloudflare Workers** in front of the API: per-endpoint cache TTLs, page aggregators, image resizing, OG image generation, a KV-backed URL shortener, rate-limited proxies
- Node/TypeScript services on Render: AI daily brief, article processing with embeddings, unified search, newsletters via AWS SES
- Next.js 14 frontend (App Router, SSR + ISR), an internal React admin portal, and a Flutter app in development
- [**Intel API**](https://www.plus234feed.com/intel) — a developer data API over the same tables: API-key issuing, hashing and revocation, daily usage limits, and a response envelope carrying source and freshness on every payload

`Python` `FastAPI` `TypeScript` `Next.js` `Cloudflare Workers` `Supabase Postgres` `GitHub Actions`

### [Plus234Feed MCP Server](https://www.plus234feed.com/mcp) — grounded Nigerian data inside AI assistants

Assistants answer questions about Nigerian rates, markets and politics
confidently and wrongly, because that data changes faster than training and is
thin online. This gives them the current numbers and the archive instead.

- **13 tools** over a **~177,000-article** news archive, NGX equities and **2,482 corporate filings**, naira official-vs-parallel rates, NBS statistics and the National Assembly
- Two search tools on purpose: semantic search over pgvector embeddings for meaning, exact keyword search with Postgres `ts_rank` for names and tickers — each fails where the other works
- Responses lead with the period they are quoting, and tools report their own coverage gaps rather than implying a fact is absent from the world
- Speaks MCP over stdio, so queries and credentials stay on the client's machine

`TypeScript` `MCP SDK` `Postgres` `pgvector` `Node`

### [WebSentry](https://websentry.dev) — website security scanning and monitoring

Grades any site across **15 independent checks** — TLS, security headers, CSP,
cookies, CORS, DNS and email authentication, mixed content, vulnerable JS
libraries — and explains each result rather than just scoring it.

- Shareable and white-label PDF reports
- Scheduled rescans as queued jobs, with alerts on grade regressions
- REST API for CI/CD

`TypeScript` `Cloudflare Workers` `D1` `R2` `Queues` `React`

### Web Signals — conversion analytics with AI-written site audits

Site owners see traffic numbers but not where intent builds or leaks. This
scores each session by intent and turns behaviour into prioritised findings.

- Tracker that survives modern frontends: fetch/XHR interception for AJAX form
  submissions, SPA route changes via the history API, MutationObserver for
  elements added later
- Session intent scoring with traffic-source and UTM breakdown
- Claude-generated audit findings, prioritised, with shareable report pages and
  task tracking from todo to deployed

`TypeScript` `Cloudflare Workers` `D1` `R2` `Claude` `React`

### Application Agent — job applications that never invent an answer

Finds matching roles across five ATS platforms, then drafts answers that cite
the resume line each claim came from — and declines to answer when the resume
does not support one.

- Adapters for Greenhouse, Lever, Ashby, Workable and SmartRecruiters behind one interface
- Discovery over public job-board APIs, with keyword pre-scoring before any paid model call
- Per-answer confidence, provenance on every claim, and a human check before anything is submitted

`Python` `FastAPI` `Playwright` `SQLAlchemy` `Claude`

### Smaller edge services

| Project | What it does |
|---|---|
| [EdgeSubmit](https://edgesubmit.com) | Form endpoint for static sites: validation, rate limiting and spam checks at the edge, email delivery, submission log |
| SplitCast | A/B testing from a single script tag, variant assignment and results in D1 |
| [PxShot](https://pxshot.dev) | Screenshot API for developers, on Cloudflare Browser Rendering |
| [LeadZap](https://leadzap.dev) | B2B lead generation with verified emails, queue-backed so long jobs don't block requests |

---

## Tech

| | |
|---|---|
| **Languages** | Python, JavaScript, TypeScript, Bash |
| **Backend & APIs** | FastAPI, Flask, Node.js, REST, webhooks, background workers, schema design |
| **Frontend** | React, Next.js, React Query, Tailwind, SEO-aware rendering, performance work |
| **Cloud & edge** | AWS (EC2, S3, CloudFront, Lambda, RDS), Cloudflare (Workers, D1, KV, R2, Queues), Render, Azure |
| **Automation & delivery** | Docker, GitHub Actions, Terraform, Kubernetes, Playwright, cron pipelines |
| **AI engineering** | LLM workflows, MCP, structured outputs, embeddings and semantic search, evaluation |
| **Data** | PostgreSQL, MongoDB, Redis, Supabase, D1 |
| **Operations** | Logging, monitoring, alerting, production debugging, incident response |

---

## Experience

**Service Delivery Engineer**, Persado — Jan 2024 to present
JavaScript platform integrations running in enterprise customer production
environments; APIs and control surfaces governing configuration, observability
and deployment safety.

**Web Software / DevOps Engineer**, Naveen Jindal School of Management (UT Dallas) — Jul 2023 to Dec 2023
AWS infrastructure and CI/CD for internal production platforms.

**Developer Support Engineer**, Microsoft — Sep 2021 to Jun 2023
Supported enterprise customers integrating Edge Chromium and WebView2 into
large-scale production applications.

**Senior Software Engineer**, AXOX Web Solutions — Jan 2015 to Sep 2021
Full-stack applications, backend APIs and AWS deployment automation.

---

## Certifications & education

- AWS Certified Cloud Practitioner (CLF-C01)
- Microsoft Certified: Azure Fundamentals (AZ-900)
- B.S. Computer Science, University of Texas at Dallas
- A.S. Computer Science, Dallas College


