<h1 align="center">Harshdeep Singh</h1>

<p align="center">
  Backend engineer · real-time and asynchronous systems · AI infrastructure<br/>
  TypeScript · Node.js · Redis · MongoDB · PostgreSQL
</p>

<p align="center">
  <a href="https://harshlocham.com">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/harshlocham">LinkedIn</a> ·
  <a href="https://x.com/harsh_locham">X</a>
</p>

---

## Open source: TanStack AI

12 merged pull requests in [TanStack/ai](https://github.com/TanStack/ai), a type-safe, provider-agnostic TypeScript AI SDK. [See all of them](https://github.com/TanStack/ai/pulls?q=is%3Apr+author%3Aharshlocham+is%3Amerged).

- [AG-UI activity messages with an optional `ActivityStore`](https://github.com/TanStack/ai/pull/1323): live snapshot/delta handling, kept out of model input, restored on reload
- [Bedrock Mantle fix for Gemma 4](https://github.com/TanStack/ai/pull/1270): a misleading 401 was really a wrong API path; the path now comes from the model catalog
- [Token-provider auth for OpenAI-compatible adapters](https://github.com/TanStack/ai/pull/1322)
- [29 dangling `.d.ts` imports fixed across 10 packages](https://github.com/TanStack/ai/pull/922), with a CI check so it can't regress
- [Anthropic context-management beta handling](https://github.com/TanStack/ai/pull/1080), [Ollama pre-stream error events](https://github.com/TanStack/ai/pull/862), [Groq summarization adapter](https://github.com/TanStack/ai/pull/837)

---

## Projects

**[Semantask](https://github.com/harshlocham/semantask)** (open source): teams talk, AI extracts the work as suggestions, managers approve and stay in control. Autonomy is optional and policy-gated, not the default.

- Transactional outbox, leased and heartbeated workers, layered idempotency
- Socket.IO kept transport-only, with Redis fan-out and presence that expires stale users
- Suggest-first extraction, manager approvals, tool grants, and audit trails
- Ten documented architecture decisions, starting with [ADR-005](https://github.com/harshlocham/semantask/blob/main/docs/decisions/ADR-005-suggest-first-work-coordination.md)
- No hosted demo; runs locally (see the repo's quick start)

**[Knowledge Workbench](https://github.com/harshlocham/knowledge-workbench)**: a research assistant with hybrid retrieval (Qdrant dense search and Postgres full-text, RRF-fused, LLM-reranked) and citation-grounded answers that link back to the original source.

---

## Open to work

Backend, platform, and AI-infrastructure roles. Full-time or internship, remote welcome.

---

## Tech

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,nextjs,react,express,mongodb,postgres,redis,docker,git,github" />
</p>
