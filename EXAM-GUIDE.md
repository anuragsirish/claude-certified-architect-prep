# CCAR-P Exam Guide — The Essentials

Everything you need to know before sitting the **Claude Certified Architect – Professional (CCAR-P)** exam, condensed into one page. Written in my own words, based on the official exam guide (v1.0, July 2026) and the official prep path — details can change, so always confirm against the [official certification page](https://anthropic-partners.skilljar.com/path/claude-certified-architect-professional) before you register.

## What this certification is

CCAR-P validates that you can **design, build, and deliver production-grade AI solutions on the Claude platform** — model and architecture selection, prompt and context engineering, enterprise integration, evaluation, and the security, compliance, and governance thinking that goes with all of it.

**Who it's for:** mid- to senior-level solution architects, AI/ML engineers, and technical leads who own end-to-end AI systems — not entry-level developers or prompt-only roles.

**Recommended experience** (recommended, not required — there are no mandatory prerequisites):

- A foundation in software engineering best practices
- 3+ years in systems architecture or platform engineering
- 6+ months hands-on with Claude (or comparable LLM systems) in production
- Experience delivering systems end-to-end, from discovery through operations

## Exam at a glance

| | |
|---|---|
| **Exam code** | CCAR-P |
| **Questions** | 63 — multiple-choice and multiple-response (each item tells you how many to select) |
| **Time limit** | 120 minutes |
| **Delivery** | Proctored — online or at a Pearson VUE test center |
| **Passing score** | 720 on a 100–1,000 scaled range |
| **Fee** | $175 USD per attempt |
| **Validity** | 12 months |
| **Results** | Pass/fail with your scaled score, plus percent-correct per domain |

## The blueprint — 7 domains

| # | Domain | Weight | What it actually tests |
|---|--------|:------:|------------------------|
| 1 | Solution Design & Architecture | **17%** | Translating business problems into Claude solutions; workflow vs. agentic patterns; multi-agent orchestration; decomposition; business-value alignment |
| 2 | Claude Models, Prompting & Context Engineering | **13%** | Model selection trade-offs; system prompts and guardrails; zero-/few-shot and chain-of-thought; context-window and token optimization; prompt caching, modular prompts, Skills |
| 3 | Integration | **19%** | Tool scope and capability bloat; authN/authZ gaps; accuracy–latency trade-offs; observability at scale; RAG pipeline, chunking, and retrieval strategy; MCP vs. API/CLI vs. agent-to-agent; progressive discovery vs. monolithic context |
| 4 | Evaluation, Testing & Optimization | **16%** | Metrics; eval datasets and mixed-method test frameworks; A/B testing; diagnosing prompt failures, hallucination, model mismatch; token/latency/cost optimization; logging and observability |
| 5 | Governance, Safety & Risk Management | **14%** | Guardrails and safety controls; failure modes; human-in-the-loop; GDPR / HIPAA / FedRAMP; bias, fairness, transparency |
| 6 | Stakeholder Communication & Lifecycle Management | **14%** | Structured discovery; communicating trade-offs; SLAs and expectation management; architecture documentation; discovery → design → handoff → monitoring → iteration |
| 7 | Developer Productivity & Operational Enablement | **7%** | Configuring Claude tooling for teams (e.g., Claude Code); AI-assisted developer workflows; debugging and operational issue resolution |

Domain 3 (19%), Domain 1 (17%), and Domain 4 (16%) carry more than half the exam between them — budget your study time accordingly.

## The official prep course (free)

Anthropic's official prep path is **free to register** and mirrors the exam blueprint across five lessons (~12 hours total):

| Lesson | Official duration | My video walkthrough |
|--------|:-----------------:|----------------------|
| 1 · Claude Platform & Solution Design | 238 min | [▶️ Watch](https://youtube.com/playlist?list=PLS3h0TTAvZGs) |
| 2 · Enterprise Integration & Production | 158 min | [▶️ Watch](https://youtube.com/playlist?list=PLS3h0TTAvZGs) |
| 3 · Responsible AI, Safety & Risk for Architects | 114 min | [▶️ Watch](https://youtube.com/playlist?list=PLS3h0TTAvZGs) |
| 4 · Stakeholder Engagement, Lifecycle & GTM | 178 min | [▶️ Watch](https://youtube.com/playlist?list=PLS3h0TTAvZGs) |
| 5 · Team Enablement & Operational Productivity | 45 min | [▶️ Watch](https://youtube.com/playlist?list=PLS3h0TTAvZGs) |

👉 **[Register for the official prep path (free)](https://anthropic-partners.skilljar.com/path/claude-certified-architect-professional)** — my video course follows the same five lessons, so you can use the two side by side.

## Scoring, scheduling & policies — the short version

- **Criterion-referenced:** you pass by clearing the 720 cut score, not by beating other candidates. The cut score was set by a formal standard-setting study.
- **Registration:** through the Anthropic Partner Academy, then schedule with Pearson VUE (online proctored or a test center). Partner-tier discounts apply at checkout where applicable.
- **Reschedule/cancel:** free up to 24 hours before your appointment; inside 24 hours (or a no-show) forfeits the fee.
- **Retakes:** waiting periods grow with each failed attempt — 14 days, then 30, then 90 — with a maximum of four attempts in a rolling 12 months. The fee applies to every attempt.
- **Renewal:** the credential lasts 12 months. On-time renewal is a **free, non-proctored** refresher assessment; if it lapses, you retake the full exam at full price.
- **Exam day:** government photo ID matching your registration name exactly, clean workspace, webcam view throughout (if online), and you must accept a confidentiality/NDA agreement before starting. Accommodations must be approved by Pearson VUE *before* you schedule.

## How I'd prepare

This is the approach I used for my own pass — **860 / 1,000** in September 2026 ([credential on Credly](https://www.credly.com/badges/302e4c2a-57f5-40a0-9461-8122d95fdb44)):

1. **Watch the lessons** — [my free video course](https://youtube.com/playlist?list=PLS3h0TTAvZGs) and/or the official path, one lesson at a time.
2. **Self-assess against the blueprint** — read each objective above and honestly grade yourself.
3. **Build something real** — one end-to-end Claude solution with RAG, evals, and observability teaches more than any amount of reading.
4. **Read the official docs** — Claude API, model selection, prompt engineering, MCP, and Skills.
5. **Drill questions** — start with the [20 free samples](sample-questions.md) in this repo (or the [interactive quiz](quiz.html)), then work through the full 300-question bank on Udemy *(link coming soon)*.<!-- TODO: replace with Udemy course URL -->

## Official resources

- [CCAR-P prep path — Anthropic Partner Academy](https://anthropic-partners.skilljar.com/path/claude-certified-architect-professional) (free registration)
- [Pearson VUE — Claude Certification Program](https://www.pearsonvue.com/us/en/anthropic.html) (scheduling, policies, accommodations)
- [Anthropic documentation](https://docs.claude.com)

---

*This is an unofficial summary written for fellow exam candidates. It is not affiliated with or endorsed by Anthropic. Exam facts reflect the official exam guide v1.0 (July 2026) and are subject to change — always verify against the official pages above. Claude and Anthropic are trademarks of Anthropic, PBC.*
