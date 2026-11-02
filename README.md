# Jesús Daniel Gómez Hernández
### Product Engineer | Backend & AI | Node.js / TypeScript

📍 Dijon, France · 8+ years building production software · **Open to new opportunities**

[LinkedIn](https://www.linkedin.com/in/jdanielgh9412/) · jesus.gomezher@gmail.com

---

I build backend systems and full-stack products end to end — from requirements to production support — across logistics, fintech, insurance and media. Lately I've been applying that same rigor to AI: RAG systems, LLM applications, and agentic development workflows.

### Projects

**[WhatsApp Memory Search](https://github.com/jdanielgh/whatsapp-memory-search) — Open-source RAG assistant**

Archives a WhatsApp conversation as immutable evidence, indexes it, and answers natural-language questions — every answer cites the messages that support it, and it says so when the evidence isn't enough.

- RAG backend on Node.js/TypeScript, PostgreSQL + pgvector and Drizzle: literal, date, timeline, topic, statistics and semantic search, with AI-extracted entities, events and topics.
- Verifiable answers: the model returns claims tied to evidence indexes, and a deterministic check flags any claim citing evidence that doesn't exist. The archived messages are read-only at the database-role level.
- Swappable AI behind a provider abstraction — the Anthropic API or Claude Code through a subscription (no API spend), Voyage AI for embeddings — with idempotent, cost-reporting runs and a 100-question regression suite that tracks grounding, intent, latency and cost.
- Generic by design: categories, analysis dimensions and prompt context come from a configurable domain profile. CI runs typecheck, unit and integration tests against an ephemeral Postgres.

**AI Job — Claude Code job-search assistant (extended open-source framework)**

A job-search workflow built on Claude Code: it scrapes portals, ranks postings against my profile, and drafts tailored CVs and cover letters with a reviewer agent. I forked the open-source *ai-job-search* framework and extended it for my own search.

- Added portals: LinkedIn, Himalayas, Jobicy and Freelancermap, storing location, employment type, contract note and employer country per posting.
- Built a local ranking dashboard to review and tick ranked postings, with a History tab over my application tracker, plus a sync to a hosted dashboard that drafts applications for accepted postings.

**CodeLens AI — AI Pull Request reviewer** *(in development, private repo)*

Combines deterministic static analysis, repository-aware RAG and specialized LangGraph agents to produce evidence-backed review findings, with human approval before anything is published to GitHub.

- Foundation in progress: TypeScript monorepo (pnpm + Turborepo), Zod domain contracts for findings and evidence, PostgreSQL + pgvector and Redis in Docker Compose, Drizzle migrations with mandatory reverse scripts, and CI running lint, typecheck, tests and a Postgres integration job.
- Next: LangGraph JS workflow, GitHub App ingestion, Semgrep/ts-morph analysis and repository RAG.

**[Music Wave Mark](https://musicwavemark.jdgh.dev) — Founder & Sole Developer**

A web application for creating smart bookmarks on audio content. Users can upload an audio file, visualize and navigate its waveform, play specific sections, and save exact moments with timestamps, comments, and bookmark types for quick reference.

Designed for creators, editors, and teams reviewing or collaborating on audio content. Currently in closed beta with a small group of users ahead of its public launch.

- Designed, built, and operated the product end to end using React, TypeScript, Supabase/PostgreSQL, and Cloudflare Workers, with a privacy-first architecture where audio remains on the user's device and only metadata is synchronized.

*Repo private — pre-launch.*

**[Create Claude Base](https://github.com/jdanielgh/create-claude-base)** — a reusable Claude Code base (rules, agents, hooks, MCP presets) for new projects, with presets for web, mobile, backend and RAG.

### Stack

`Node.js` `TypeScript` `Express` `NestJS` `React` `PostgreSQL` `MongoDB` `Redis` `Docker` `Kafka` `Azure` `GCP` `AWS`
`RAG` `pgvector` `LangGraph` `LLM applications` `Claude Code / agentic development`

### Currently

Product Engineer at **Limestone Digital**, on a last-mile logistics platform (OneRail) — Node.js/TypeScript microservices, OpenAPI-first APIs, Azure.

---

Open to **Product Engineer** and **Backend & AI** roles. Reach out on [LinkedIn](https://www.linkedin.com/in/jdanielgh9412/).
