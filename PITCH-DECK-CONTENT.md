# Jawabid — RFP Management System | Pitch Deck Content

---

## Slide 1: Title

**Badge:** Arabic-First AI Enterprise Software

**Headline:** RFP Management System

**Tagline:** The first Arabic-first RFP platform — powered by GPT-5.2 and QWEN 3.5 to analyze, generate, and optimize proposals across the MENA region.

**Key Stats:**
| Metric | Value |
|--------|-------|
| AI Agents | 13 |
| Source Files | 515+ |
| Language | عربي (Arabic-First) |
| LLM Engines | 2 (GPT-5.2 + QWEN 3.5) |

---

## Slide 2: The Problem

**Headline:** RFP Response Is Broken
**Subhead:** MENA enterprises lose millions from slow, manual, English-only proposal processes.

**Pain Points:**

1. **Manual Document Analysis** — Teams spend 20–40 hours reading and extracting requirements from complex RFP documents before even starting.

2. **Fragmented Collaboration** — Questions assigned via email chains and spreadsheets. SMEs lose context, deadlines slip, responses lack consistency.

3. **No Arabic-Native AI Tools** — Existing RFP tools are built for English markets. Arabic proposals require manual translation, losing nuance and cultural context.

4. **Compliance Gaps** — Missing requirements discovered last minute — non-compliant submissions and disqualified bids worth millions.

**Callout:** Average enterprise spends **$2,500–$35,000** per RFP response — with a win rate under **5%**.

---

## Slide 3: The Solution

**Headline:** Arabic-First AI That Wins Proposals
**Subhead:** Dual-LLM engine: GPT-5.2 for reasoning + QWEN 3.5 for native Arabic understanding.

**6-Step Pipeline:**
1. Upload RFP
2. AI Analysis
3. Auto-Generate Questions
4. Smart Assign
5. RAG Answers
6. Proposal Generation

**Key Capabilities (Left Column):**
- **Instant RFP parsing** — PDF, DOCX, Excel, TXT analyzed in seconds
- **Knowledge-powered answers** — RAG on company docs to draft responses
- **Real-time collaboration** — WebSocket live editing + notifications

**Key Capabilities (Right Column):**
- **Go/No-Go intelligence** — AI recommends which RFPs to pursue
- **Compliance checking** — Never miss a requirement again
- **Arabic-first, not translated** — QWEN 3.5 thinks in Arabic natively

---

## Slide 4: AI Agents

**Headline:** 13 AI Agents, 5 Capabilities
**Subhead:** GPT-5.2 for reasoning + QWEN 3.5 for native Arabic — orchestrated across the full RFP lifecycle.

### Capability 1: Intelligent RFP Analysis [3 agents]
- Extracts requirements, deadlines, budgets & evaluation criteria
- Pulls metadata from Arabic & English documents
- Scores relevancy against company capabilities

### Capability 2: Smart Go/No-Go Decision Engine [1 agent]
- Analyzes win probability, strategic value & resource fit
- Assesses competition level and risk factors
- Delivers clear GO/NO-GO recommendation with reasoning

### Capability 3: AI Question Generation & Routing [3 agents]
- Generates targeted questions covering every RFP requirement
- Auto-categorizes and routes to the right business unit & experts
- AI drafts answers using company knowledge base (RAG)

### Capability 4: Automated Proposal Generation [4 agents]
- Plan → Map → Write → Fill pipeline
- Synthesizes raw answers into professional narrative prose
- Fills branded templates preserving Arabic & English formatting

### Capability 5: AI Quality Assurance [2 agents: Document Reviewer + Compliance Checker]
- Reviews for wrong-section content, broken text & duplicates
- Checks compliance against all RFP requirements
- Optimizes for clarity, persuasiveness, and differentiation

---

## Slide 5: Product Features

**Headline:** Enterprise-Ready Feature Set

| Feature | Description |
|---------|-------------|
| **Knowledge Wizard** | Upload docs, scrape websites, build a vector knowledge base for RAG-powered answers |
| **Team Collaboration** | Assign questions to SMEs, track progress real-time, automated notifications and deadlines |
| **Proposal Analyzer** | AI-powered analysis of past proposals — scoring, gap detection, and improvement recommendations |
| **Outlook Integration** | Auto-ingest RFPs from email via Microsoft Graph API for seamless inbox monitoring |
| **Zoho CRM Sync** | Bi-directional CRM integration — pull opportunities, push statuses, unified pipeline |
| **Multi-Tenant & RBAC** | Full multi-tenancy with role-based access, business unit isolation, audit logging |

---

## Slide 6: Architecture

**Headline:** Production-Grade Stack

### Application Layer
| Component | Stack |
|-----------|-------|
| **Frontend** | React 18 + Tailwind CSS, shadcn/ui + RTL-first i18n |
| **Backend API** | FastAPI + SQLAlchemy, Celery + WebSockets |
| **AI Services** | GPT-5.2 + QWEN 3.5, Dual-LLM / 13 Agents |

### Data & Integration Layer
| Component | Stack |
|-----------|-------|
| **Vector DB** | ChromaDB, RAG Knowledge Store |
| **PostgreSQL + Redis** | Primary DB + Cache, Session & Queue Store |
| **Integrations** | Zoho CRM + Outlook, Microsoft Graph API |

### Infrastructure
GPT-5.2, QWEN 3.5, Docker, Nginx, GitHub Actions CI/CD, Alembic Migrations, Circuit Breaker, Prometheus Metrics

---

## Slide 7: Market Opportunity

**Headline:** The Market Opportunity

**Market Size:**
| Metric | Value |
|--------|-------|
| Global Proposal Management Market by 2030 | **$7.1B** |
| CAGR Growth | **14.2%** |
| Firms Planning AI Adoption | **72%** |

**Why Now:**
1. **Dual-LLM maturity** — GPT-5.2 + QWEN 3.5 make Arabic document analysis viable at enterprise quality
2. **RAG revolution** — Vector databases enable Arabic company-specific knowledge retrieval at scale
3. **MENA digital push** — Saudi Vision 2030 and UAE programs driving Arabic-first B2B SaaS adoption
4. **No Arabic-native competitor** — Every existing RFP tool is English-first with bolted-on translation

---

## Slide 8: Competitive Edge

**Headline:** Our Competitive Edge

| Capability | RFP Management System | Legacy (Loopio, RFPIO) | Generic AI (ChatGPT) |
|------------|----------------------|----------------------|---------------------|
| **AI Engine** | Dual-LLM / 13 agents in 5 capabilities | Basic keyword matching | Single model, generic |
| **Arabic Understanding** | QWEN 3.5 native Arabic NLU | English only | Translated, loses nuance |
| **Knowledge RAG** | ChromaDB + Arabic embeddings | Content library (manual) | No persistent memory |
| **CRM Integration** | Zoho + Outlook native | Salesforce only | None |
| **Compliance Check** | Automated AI audit (AR/EN) | Manual checklists | None |

---

## Slide 9: Business Model

**Headline:** SaaS Revenue Engine

### Pricing Tiers

| | Starter | Professional (Recommended) | Enterprise |
|--|---------|---------------------------|------------|
| **Price** | $499/mo per team | $1,499/mo per team | Custom (annual) |
| **Users** | Up to 10 | Up to 50 | Unlimited |
| **RFPs** | 50/month | Unlimited | Unlimited |
| **AI Agents** | 5 | All 13 | All 13 |
| **Integrations** | — | CRM + Outlook | Custom integrations |
| **Support** | Email | Priority | Dedicated success manager |
| **Deployment** | Cloud | Cloud | On-premise / white-label |

**Callout:** Target ACV: **$18K–$50K** per enterprise | Gross margin: **~80%** (SaaS + AI compute)

---

## Slide 10: Roadmap

**Headline:** Growth Trajectory

| Quarter | Status | Milestones |
|---------|--------|------------|
| **Q1 2026** | COMPLETED | Core platform built, GPT-5.2 + QWEN 3.5 integrated, CRM + Outlook connected, Arabic-first UX shipped |
| **Q2 2026** | CURRENT | Beta with 5 MENA pilots, Arabic RFP training data, SOC 2 compliance, QWEN 3.5 fine-tuning |
| **Q3 2026** | NEXT | Public launch, Salesforce integration, Analytics dashboard, Mobile companion app |
| **Q4 2026** | FUTURE | Series A target, Multi-region deployment, Template marketplace, Government vertical |

**Callout:** The product is **already built** — 515+ files, 13 AI agents, 265+ endpoints. We're raising to accelerate GTM.

---

## Slide 11: Traction

**Headline:** Built, Not Pitched
**Subhead:** What's already shipped and operational.

### Technical Stats
| Metric | Value |
|--------|-------|
| Production Files | **515+** |
| Backend Services | **30** |
| API Endpoints | **265+** |
| DB Tables | **40** |

### Operational Capabilities

1. **Full CI/CD Pipeline** — GitHub Actions with automated testing, building, deployment. Docker-containerized for any cloud.

2. **Enterprise Security** — JWT auth, RBAC, audit logging, error sanitization, circuit breaker, profanity filtering.

3. **Real-time Infrastructure** — WebSocket PubSub for live collaboration, Redis caching, Celery async, notification system.

4. **Arabic-First UX** — RTL-native interface, Arabic-first content flow, QWEN 3.5 for Arabic NLU across all AI features.

---

## Slide 12: The Ask

**Headline:** The Arabic-First RFP Revolution Starts Here

**Description:** Raising a seed round to own the Arabic RFP market — dual-LLM engine, 20 enterprise pilots, MENA-wide expansion.

### Funding
| Metric | Value |
|--------|-------|
| Seed Round Target | **$1.5M** |
| Runway | **18 months** |

### Use of Funds
| Allocation | Percentage |
|-----------|------------|
| Engineering & AI | 40% |
| Sales & GTM | 30% |
| Operations | 20% |
| Infrastructure | 10% |

### Contact
- **Demo:** dali@siyadatech.com
- **WhatsApp:** +966 56 571 7661

---

## Technical Reference

### Repository
- **GitHub:** https://github.com/siyaida/rfpforked
- **Live Deck:** https://rfp-pitch-deck.netlify.app

### Tech Stack Summary
- **Frontend:** React 18, Tailwind CSS, shadcn/ui, React Router, Recharts, i18n (AR/EN with RTL)
- **Backend:** FastAPI (Python), SQLAlchemy ORM, Celery (async tasks), WebSocket PubSub
- **AI:** GPT-5.2 (reasoning/generation), QWEN 3.5 (Arabic NLU), 13 specialized agents in 5 capability groups
- **Data:** PostgreSQL (40 tables), Redis (cache/queue), ChromaDB (vector/RAG)
- **Integrations:** Zoho CRM (bi-directional), Microsoft Outlook (Graph API), Email notifications
- **Infrastructure:** Docker, Nginx, GitHub Actions CI/CD, Alembic migrations, Prometheus metrics
- **Security:** JWT auth, RBAC, audit logs, circuit breaker, error sanitizer, profanity filter

### File Structure (515+ files)
```
backend/
  app/
    api/endpoints/       — 25+ API endpoint modules
    services/            — 30 backend services
    models/              — 25+ SQLAlchemy models
    schemas/             — 15+ Pydantic schemas
    core/                — Auth, Redis, Celery, WebSocket, metrics
  alembic/versions/      — 15+ DB migrations
rfp-frontend/
  src/
    pages/               — 20+ page components
    components/          — 15+ shared components + shadcn/ui library
    contexts/            — Auth, Language, Network, Notification, Onboarding, WebSocket
    hooks/               — Custom React hooks
    i18n/locales/        — ar.json + en.json
    utils/               — Translation utilities
scripts/                 — Deploy, backup, test, build scripts
.github/workflows/       — CI/CD pipeline
```

### 13 AI Agents Breakdown
| # | Agent | Capability Group | LLM |
|---|-------|-----------------|-----|
| 1 | Requirement Extractor | Intelligent RFP Analysis | GPT-5.2 + QWEN 3.5 |
| 2 | Metadata Extractor | Intelligent RFP Analysis | GPT-5.2 + QWEN 3.5 |
| 3 | Relevancy Scorer | Intelligent RFP Analysis | GPT-5.2 |
| 4 | Go/No-Go Advisor | Smart Go/No-Go Engine | GPT-5.2 |
| 5 | Question Generator | AI Question Gen & Routing | GPT-5.2 + QWEN 3.5 |
| 6 | Question Categorizer | AI Question Gen & Routing | GPT-5.2 |
| 7 | RAG Answer Drafter | AI Question Gen & Routing | GPT-5.2 + QWEN 3.5 |
| 8 | Proposal Planner | Automated Proposal Gen | GPT-5.2 |
| 9 | Template Mapper | Automated Proposal Gen | GPT-5.2 |
| 10 | Narrative Writer | Automated Proposal Gen | GPT-5.2 + QWEN 3.5 |
| 11 | Template Filler | Automated Proposal Gen | GPT-5.2 |
| 12 | Document Reviewer | AI Quality Assurance | GPT-5.2 + QWEN 3.5 |
| 13 | Compliance Checker | AI Quality Assurance | GPT-5.2 + QWEN 3.5 |

### Supported File Formats
PDF, DOCX, Excel (.xlsx/.xls), TXT

### Key Database Tables (40 total)
Users, Companies, RFPs, RFP Questions, Proposals, Proposal Analysis, Proposal Templates, Documents, Business Units, Stakeholders, Workflow, Notifications, User Notification Preferences, Audit Logs, Error Logs, AI Chat, AI Operations, Refresh Tokens, Integration Settings, Outlook Connections, Outlook Subscriptions, Incoming RFP Emails, Email Attachments, Website Scrapes, User Invitations, Company Settings, User Business Unit Mappings, and more.
