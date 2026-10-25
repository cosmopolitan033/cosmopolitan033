# Hi, I'm Zhaocun Sun (孙兆存)

**AI Agent Engineer · Shenzhen, China**

I build reliable agents for real-world workflows, with a focus on **Agent Harness engineering, Browser Agents, multi-agent orchestration, and context engineering**.

Currently an AI Agent Engineer at **甄才智能**, leading **AiOffer** and **聘聘 (Pinpin)** from business modeling and architecture to core development and production delivery.

[LinkedIn](https://www.linkedin.com/in/zhaocun-sun-9ba414277/) · [Open-source contributions](https://github.com/pulls?q=is%3Apr+author%3Acosmopolitan033+is%3Amerged)

## What I work on

- **Agent runtime and reliability:** state machines, memory and checkpoints, execution leases, durable event replay, recovery for long-running tasks, and human-in-the-loop controls.
- **Browser Agents and tool use:** Playwright, Chrome DevTools Protocol (CDP), dynamic form handling, page-state verification, MCP, Skills, and authorization-aware execution.
- **Multi-agent systems and retrieval:** Eino ADK, DAG orchestration, A2A collaboration, structured outputs, context management, and evidence-grounded RAG.

## Selected projects

### AiOffer — AI Job Search Assistant

**Project Lead · Go / Eino ADK / langoraph / MCP / CDP**

- Connect job discovery, JD-tailored resume optimization, application preparation, cross-site submissions, and mock interviews in one workflow.
- Use multi-stage DAGs, controlled parallel rewriting, schema validation, and shared scoring rubrics for resume optimization.
- Separate session control from worker execution; support checkpoint recovery, lease renewal, durable receipts, and human takeover for long-running browser tasks.
- Build payment, refund, and entitlement workflows with verified callbacks, idempotent commands, transactional Outbox, reconciliation, and failure recovery.

### 聘聘 (Pinpin) — A2A Recruiting & Intelligent Office Platform

**Project Lead · Go / Eino / NATS / PostgreSQL / RAG**

- Coordinate employer and candidate agents through A2A tasks, asynchronous state machines, and traceable evidence for matching decisions.
- Orchestrate recruiting roles with PostgreSQL persistence, NATS JetStream, transactional Outbox, and idempotent consumers.
- Automate recruiting workflows on BOSS and Liepin with isolated browser sessions, durable scheduling, and execution receipts.
- Build enterprise RAG with pgvector, full-text search, reciprocal rank fusion (RRF), and version-aware citations; package office workflows with Skills, MCP, and human approval controls.

## Open source

**3 merged contributions to [OpenClaw](https://github.com/openclaw/openclaw):**

- [CLI: gate exported subcli descriptors](https://github.com/openclaw/openclaw/pull/84519)
- [Diff viewer: continue after card hydration errors](https://github.com/openclaw/openclaw/pull/84775)
- [Cron: clarify best-effort edit delivery behavior](https://github.com/openclaw/openclaw/pull/84526)

## Technical toolkit

| Area | Technologies & practices |
| --- | --- |
| Languages | Go, Python, TypeScript, Java, C |
| Agents & orchestration | Eino ADK, langoraph, LangGraph, LangChain, A2A, ReAct, Plan-and-Execute |
| Browser & tools | Playwright, CDP, MCP, Skills, JSON Schema, HITL |
| Data & retrieval | PostgreSQL / pgvector, MongoDB, Redis, hybrid search, reranking, embeddings |
| Distributed systems | NATS JetStream, RabbitMQ, RocketMQ, Inbox / Outbox, idempotency |
| Delivery & observability | Docker, Kubernetes, Helm, GitHub Actions, Jenkins, AWS, OpenTelemetry, Prometheus / Grafana, E2E, Vitest |

## Background

- **AI Agent Engineer, 甄才智能** — Mar 2026–present
- **Platform Development Engineer, 海雀科技 (Huawei Smart Selection ecosystem)** — Nov 2022–Dec 2023; C SDKs for smart cameras and Go microservices for IoT workflows.
- **Master's in Computer Science, Trinity College Dublin** — Sep 2024–Mar 2026
- **Bachelor's in Computer Science and Technology, Jilin University** — Sep 2019–Jun 2023
