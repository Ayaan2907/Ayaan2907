<div align="center">

# Ayaan Kaifullah

**Full-Stack AI/ML Engineer · New York, NY**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ayaankaif-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/ayaankaif)
[![npm](https://img.shields.io/npm/dw/auto-llm-selector?label=npm%20downloads&color=CB3837&logo=npm)](https://www.npmjs.com/package/auto-llm-selector)
[![WingMic](https://img.shields.io/badge/WingMic-wingmic.xyz-black?style=flat)](https://wingmic.xyz)
[![Email](https://img.shields.io/badge/kaifullah7921%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:kaifullah7921@gmail.com)

</div>

I build production AI systems end-to-end — agents, streaming APIs, infra, and UI. I own the stack, ship the features, and keep the platform running.

---
<!---
<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ayaan2907&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ayaan2907&layout=compact&theme=github_dark&hide_border=true&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=ayaan2907&theme=github-dark-blue&hide_border=true)

</div>

---

### At a glance

| | |
|---|---|
| Commits at AdvanceIQ.ai | 1,100+ |
| Merged PRs | 84 |
| Latency reduction, ARIA chat | 40%+ via single-agent re-arch |
| Token-expiry incidents (VVIP clients) | Zero |
| Power BI measures indexed | 894 DAX measures, 283 bookmarks |
| Logistics companies in prod (Muvik) | 10+ |
| OSS npm weekly downloads | 300+ |

---
--->
### What I'm building

**[WingMic](https://wingmic.xyz)** — you meet 20 people at a conference and forget them all by Monday.
Speak 10–30s after a conversation; the LLM extracts names, companies, context, and follow-ups into a
personal knowledge graph. Ask later: *"who at Acme works on Rust?"* — answer in <500ms.

`Next.js 15` `Bun` `Turborepo` `Drizzle + Turso` `Claude Sonnet` `OpenAI embeddings` `tRPC` `BetterAuth`

---

### Experience

**AdvanceIQ.ai** · Full-Stack AI/ML Engineer · *Oct 2025 – Present · New York, NY*

Sole engineer on a multi-product AI platform for VVIP finance clients. Own the full stack —
architecture, infra, auth, streaming UI, background jobs, admin tooling, and every API route.

- **Power BI embed pipeline** — Azure AD service principal auth, dual-method token generation with automatic fallback, Redis caching with proactive refresh; zero token-expiry incidents across all active sessions
- **ARIA chat** — AI SDK v5 streaming over live dashboards; NL → DAX query translation via a semantic catalog of 894 measures and 283 bookmarks; tool routing across catalog lookup, client-side visual export, and conditional web search; per-user thread persistence, voice dictation, screen region capture
- **Admin platform** — prompt sandbox with model tuning and full round-trip trace observability; user + report management; PostHog analytics; feature access control via Clerk metadata; global notification banners; DAX measure review interface
- **SRI Pricing module** — server-side factor-rate engine (IRR + cash-on-cash matrices) with a three-layer assumption stack: user overrides → admin global → code defaults; Zod-validated, QA'd against source Excel
- **Discover** — daily AI news platform on the same infra; Perplexity Sonar pipeline, Claude editorial selection, admin-controlled query lists and freshness windows, digest emails via QStash, custom story compose panel
- **Email + cron infra** — QStash-backed async email queue with signature verification and automatic retry; Resend for delivery; per-user notification preferences; daily/weekly digest schedules

`Next.js 15` `React 19` `TypeScript` `AI SDK v5` `OpenRouter` `Claude` `Gemini` `Perplexity Sonar`
`Power BI SDK` `PostgreSQL` `Redis` `QStash` `Prisma` `Clerk` `Vercel` `Sentry` `PostHog`

---

**Muvik** · Forward Deployed Engineer *(Founder-Level)* · *Jul – Oct 2025 · New York, NY*

Built a dynamic text-to-workflow engine for logistics — plain English triggers composable workflows
(billing, orders, scheduling, follow-ups, callbacks) constructed and executed at inference time.
Adopted by 10+ companies in production. Flew to conferences, ran on-site onboarding, iterated from
real operator feedback.

`Next.js` `Mastra agents + workflows` `assistant-ui` `TypeScript`

---

**TinyCo.ai** · Software Developer · *Jun – Nov 2023 · Toronto, ON*

Platform scaled 1 → 300K users. Replaced Flatfile with a custom CSV handler, saving $10K+/year.
Owned CI/CD and release ops end-to-end — 99.9% uptime.

`Python` `TypeScript` `React` `PostgreSQL` `GitHub Actions`

---

### Projects

**[Auto LLM Selector](https://www.npmjs.com/package/auto-llm-selector)** · [npm](https://www.npmjs.com/package/auto-llm-selector) · GitHub

Semantic classifier that scores prompts and routes them to the optimal LLM via OpenRouter.
TensorFlow USE embeddings, multi-label classification, 85–92% cache hit rate at <200ms avg.
300+ weekly npm downloads.

`TypeScript` `TensorFlow USE` `OpenRouter` `ESM`

---

**[WingMic](https://wingmic.xyz)** · *In development*

Voice-first networking memory. 10–30s of speech → structured knowledge graph → <500ms NL recall.

`Next.js 15` `Drizzle + Turso` `Claude Sonnet` `OpenAI embeddings` `tRPC`

---

**Video Analysis RAG** · GitHub

End-to-end video ingestion pipeline — Whisper transcription + visual frame analysis in <60s per video.
Vector search across 10K+ embeddings at <2s, 92% precision.

`Python` `Pinecone` `Whisper` `multimodal RAG`

---

### Stack

**Languages** — `TypeScript` `Python` `JavaScript` `SQL` `C++`

**AI / Agents** — `Mastra AI` `Claude` `GPT-4o` `Gemini` `Perplexity Sonar` `LangChain` `MCP`
`Whisper` `TensorFlow` `Pinecone` `OpenRouter` `Vercel AI SDK v5`

**Frontend** — `Next.js 15` `React 19` `Tailwind CSS` `assistant-ui` `SSE / streaming UI`

**Backend** — `Node.js` `FastAPI` `PostgreSQL` `Redis` `QStash` `Drizzle` `Turso` `Prisma`

**Infra** — `Vercel` `Railway` `Kubernetes` `Sentry` `GitHub Actions` `Clerk` `Docker`

---

### Education

**Monroe University** — M.S. Computer Science · Expected Jul 2026 · New York, NY
**University of Michigan** — M.S. Computer Science · Graduate coursework, Sep – Dec 2024
