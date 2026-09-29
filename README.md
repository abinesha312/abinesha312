# Abinesh Haridoss

Software engineer based in Irving / Dallas, TX. Most of my recent work is on **LLM applications**, **multi-agent systems**, and **RAG quality tooling**, with earlier experience in backend services, data platforms, and full-stack product work.

**[Website](https://abineshharidoss.web.app/)** · **[LinkedIn](https://linkedin.com/in/aharido/)** · **[Email](mailto:abinesha312@gmail.com)**

---

## About

I design and ship systems that call models in production-shaped ways: planning and routing across agents, retrieval and grounding checks, eval-style gates in CI, and the APIs and infra around them. I also build lower-level tools when the problem needs it (Rust SIP/HTTP voice, durable queues, MCP security stubs).

I care about clear READMEs, claims that match the code, and packages you can install and run.

---

## Experience

| Role | Org | When |
| --- | --- | --- |
| Lead Assistant Manager | EXL | Dec 2025 – Present |
| LLM Trainer | Turing | Sep 2025 – Feb 2026 |
| AI Engineer | University of North Texas | Oct 2023 – May 2025 |
| Associate Software Developer | TransUnion | Feb 2023 – Jul 2023 |
| Software Engineer | Mindtree | Oct 2021 – Feb 2023 |
| Full Stack Developer | Tanishq | Aug 2020 – Sep 2021 |

**EXL** — Lead work on applied AI / engineering for client delivery (agents, orchestration, reliability). Day-to-day is shipping Python services, wiring models and tools, and keeping pipelines honest under real load.

**Turing** — LLM training / evaluation work: reviewing model outputs, writing clear task criteria, and improving instruction quality for production training loops.

**UNT (AI Engineer)** — Built and ran a multi-agent GenAI assistant on the university GPU cluster ([UNTGenAI](https://github.com/abinesha312/UNTGenAI)): Chainlit UI, Gemma via vLLM, planner/router that decomposes work across specialized agents, tested on H100s.

**TransUnion / Mindtree / Tanishq** — Software engineering across credit/data platforms and product features: APIs, services, and full-stack delivery in enterprise environments.

---

## Skills

**Languages**  
Python · Rust · TypeScript / JavaScript · SQL · Swift · Kotlin · Bash

**AI / ML application**  
Multi-agent orchestration · RAG (retrieve, audit, ground) · Prompting & eval harnesses · vLLM / OpenAI-compatible servers · Embeddings & vector stores · LoRA fine-tune tooling · MCP (Model Context Protocol)

**Backend & systems**  
FastAPI · Docker / Compose · REST APIs · Durable queues · SIP / realtime voice (HTTP→SIP) · pytest / CI gates

**Mobile**  
SwiftUI + HealthKit · Jetpack Compose + Health Connect

**Cloud & data (used in roles / projects)**  
GPU inference stacks · FAISS / local vector DBs · GitHub Actions-style CI · relational + document stores as needed by the service

**Practices**  
Clear ownership of metrics · honest docs · installable packages · prefer interviews over volume when applying

---

## Selected open source

### GenAI & agents
- **[UNTGenAI](https://github.com/abinesha312/UNTGenAI)** — Multi-agent campus assistant (plan → route → execute → merge) on Gemma + vLLM + Chainlit
- **[spanbind](https://github.com/abinesha312/spanbind)** — Bind LLM/RAG sentences to source spans; fail CI on unbound claims
- **[verirag](https://github.com/abinesha312/verirag)** — Post-retrieval audit trail and verdicts for scientific summaries
- **[mcpsec](https://github.com/abinesha312/mcpsec)** — Local CI gate for a subset of MCPSecBench-style MCP risks
- **[agentx](https://github.com/abinesha312/agentx)** · **[arag](https://github.com/abinesha312/arag)** · **[gradrag](https://github.com/abinesha312/gradrag)** · **[mcpmark](https://github.com/abinesha312/mcpmark)** · **[docforge](https://github.com/abinesha312/docforge)** — Small, runnable paper-leftover starters (no paid API required for demos)
- **[pragma-poc](https://github.com/abinesha312/pragma-poc)** — CPU-slice POC related to [PRAGMA](https://arxiv.org/abs/2511.06345)
- **[mcp-unified](https://github.com/abinesha312/mcp-unified)** — MCP server wiring for Gmail / LinkedIn-style connections

### Systems & product
- **[sipcall](https://github.com/abinesha312/sipcall)** / **[httpvoice](https://github.com/abinesha312/httpvoice)** / **[httpcall](https://github.com/abinesha312/httpcall)** — SIP phone and Twilio-shaped HTTP calling (bring your own trunk; not a robocaller)
- **[httplora](https://github.com/abinesha312/httplora)** — HTTP in, durable queue, LoRa/Meshtastic out (mock radio supported)
- **[forgefit-ios](https://github.com/abinesha312/forgefit-ios)** / **[forgefit-android](https://github.com/abinesha312/forgefit-android)** — Gym tracker with HealthKit / Health Connect

---

## Looking for

Roles where I can own **Applied / Agentic AI**, **ML platform / LLM serving**, or **backend systems** work end to end — from design through production.

If you are hiring or want to collaborate on any of the repos above, email works best: **abinesha312@gmail.com**.
