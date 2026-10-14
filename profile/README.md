# Harshil Makhija

**AI Systems Engineer · Backend & Cloud**

I build the systems around language models: agents, retrieval, and the backend services that make them dependable in production.

[Email](mailto:harshilmakhija@outlook.com) · [LinkedIn](https://www.linkedin.com/in/harshil-makhija/) · [X](https://twitter.com/MakhijaHarshil) · [Hugging Face](https://huggingface.co/HarshilMaks) · [Hexel Studio](https://www.hexelstudio.com/?utm_source=github&utm_medium=profile)

---

## Engineering Philosophy

> A model is one component.
> The system around it decides whether it can be trusted.

So I design AI features like any other production system:

- **Consequential actions need a human.** Agents propose, people approve anything that changes the outside world.
- **Answers carry their evidence.** Every claim should trace back to a source someone can open and check.
- **Failure is a normal case.** Calls time out and workflows stop halfway, so retries, idempotency and clear state are designed in early.
- **Isolation by default.** Untrusted code runs in sandboxes and tenants never see each other's data.
- **Behavior is observable.** If I can't see what a system did and why, I can't fix it or trust it.

---

## System Architecture

The layers I work across:

```text
  Product & APIs             REST · gRPC · auth · multi-tenancy
          ▲
  Cloud & Delivery           Docker · AWS · GCP · Terraform · CI/CD
          ▲
  Data Layer                 PostgreSQL · Redis · vector search
          ▲
  Agents & Orchestration     tools · workflows · multi-agent coordination
          ▲
  Retrieval & Context        RAG · embeddings · citations
          ▲
  Models                     LLMs · PyTorch · Transformers · serving
```

---

## What I Work On

| Area | In practice |
| :--- | :--- |
| **Agent Systems** | Orchestration, tool use, human-in-the-loop approval, multi-agent workflows |
| **Knowledge Systems** | RAG pipelines, embeddings, vector search, source citations |
| **Backend & APIs** | FastAPI, NestJS, REST, gRPC, async workers, event-driven services |
| **Model Serving & MLOps** | PyTorch, Transformers, experiment tracking, deployment |
| **Cloud & Infrastructure** | AWS, GCP, Docker, Terraform, Cloudflare |
| **Computer Vision** | Image classification and geospatial imagery with deep learning |

---

## Problems I Care About

1. Keeping an agent inside hard limits on what it can touch
2. Making AI answers traceable back to evidence
3. Recovering cleanly when a workflow fails halfway
4. Serving models with predictable latency and cost
5. Keeping services maintainable as they grow
6. Turning prototypes into systems other teams can run

---

## Stack

| Layer | Tools |
| :--- | :--- |
| **Languages** | Python · TypeScript · Go · C++ · SQL |
| **AI / ML** | PyTorch · Transformers · LangChain · LlamaIndex · RAG · LLM agents · MLflow |
| **Backend** | FastAPI · NestJS · Celery · REST · gRPC · microservices |
| **Data** | PostgreSQL · Redis · Milvus |
| **Cloud** | AWS · GCP · Docker · Terraform · Cloudflare · Vercel |

---

*Always learning. Always building.*

<!--
Owner: Harshil. Last reviewed: 2026-10-14.
Review when: role or employer changes, a new job search starts, a major launch or talk, or the stack list stops matching real work.
Pins are set by hand on the profile page, not in this file.
-->
