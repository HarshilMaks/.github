<div align="center">

<img src="https://raw.githubusercontent.com/HarshilMaks/.github/main/profile/assets/banner.svg" alt="Harshil Makhija, AI Systems Engineer. Agents that ask before they act. Answers that show their work." width="100%">

<br>

[![Email Harshil](https://img.shields.io/badge/Email-7C3AED?style=for-the-badge)](mailto:harshilmakhija@outlook.com)
[![LinkedIn profile](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/harshil-makhija/)
[![X profile](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/MakhijaHarshil)
[![Hugging Face profile](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/HarshilMaks)

</div>

<img src="https://raw.githubusercontent.com/HarshilMaks/.github/main/profile/assets/divider.svg" alt="" width="100%">

## The short version

I'm an AI systems engineer in Bengaluru. I build the parts of an AI product that sit around the model: the agent loop, retrieval, the API, the queue, and the cloud it all runs on.

What I care about most is what happens when something goes wrong. Models time out, providers return half an answer, a person approves the wrong thing. I design for those days first.

| Field | Detail |
| :--- | :--- |
| **Role** | AI Systems Engineer |
| **Works on** | LLM agents, retrieval-augmented generation (RAG), model serving, backend APIs, cloud delivery |
| **Languages** | Python, TypeScript, Go, C++, SQL |
| **Location** | Bengaluru, India |

<img src="https://raw.githubusercontent.com/HarshilMaks/.github/main/profile/assets/divider.svg" alt="" width="100%">

## Pre-ship checklist

Every AI feature I build has to answer these before it goes out.

- [x] **What can this agent touch?** Tools are scoped per task, and anything that reads untrusted input gets none.
- [x] **Who approves it?** The agent drafts. A person signs off on anything that leaves the building.
- [x] **What does a retry do?** Writes carry idempotency keys, so a second attempt never sends the email twice.
- [x] **What if the outcome is unknown?** When a provider times out mid-write, a reconciliation job checks what happened instead of guessing.
- [x] **Where did this answer come from?** Every claim links back to the passage that supports it.
- [x] **How would I know it's wrong?** Traces, audit logs and evals, so a mistake shows up on a dashboard and not in a customer's inbox.

<img src="https://raw.githubusercontent.com/HarshilMaks/.github/main/profile/assets/divider.svg" alt="" width="100%">

## Where I can help

- **"The demo works. Production doesn't."**
  - I turn a prototype into a service: proper APIs, a real data layer, deployment, and monitoring you can read at 2 a.m.
- **"The agent has too much power."**
  - Scoped tools, approval steps for anything irreversible, and an audit trail of what it did and why.
- **"Nobody trusts the answers."**
  - Retrieval that cites the passage behind every claim, plus evaluation so quality is measured and not assumed.
- **"The backend falls over under load."**
  - Async workers, queues, caching, and service boundaries that stay clean as the system grows.
- **"Only one person knows how to run it."**
  - Containers, infrastructure as code and runbooks on AWS or GCP.

<img src="https://raw.githubusercontent.com/HarshilMaks/.github/main/profile/assets/divider.svg" alt="" width="100%">

## How a project moves

```mermaid
flowchart LR
    A(["Define the problem"]) --> B(["Design the system"]) --> C(["Build and evaluate"]) --> D(["Deploy"]) --> E(["Observe and improve"])
    E -.->|"next round"| B
    classDef c1 fill:#0ea5e9,stroke:#0369a1,color:#ffffff
    classDef c2 fill:#8b5cf6,stroke:#6d28d9,color:#ffffff
    classDef c3 fill:#ec4899,stroke:#be185d,color:#ffffff
    classDef c4 fill:#f59e0b,stroke:#b45309,color:#111827
    classDef c5 fill:#10b981,stroke:#047857,color:#ffffff
    class A c1
    class B c2
    class C c3
    class D c4
    class E c5
```

In words: define the problem, design the system, build and evaluate it, deploy, then observe and improve. What I learn in the last step feeds the next round of design.

<img src="https://raw.githubusercontent.com/HarshilMaks/.github/main/profile/assets/divider.svg" alt="" width="100%">

## What I build with

| Area | Tools |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **AI / ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat-square) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white) |
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |

<img src="https://raw.githubusercontent.com/HarshilMaks/.github/main/profile/assets/divider.svg" alt="" width="100%">

## Get in touch

> [!TIP]
> Email is the fastest way to reach me: [harshilmakhija@outlook.com](mailto:harshilmakhija@outlook.com)

<!--
Owner: Harshil. Last reviewed: 2026-10-14.
Review when: role or employer changes, a new job search starts, a major launch or talk, or the stack list stops matching real work.
Badges are static shields.io images (no live data). Banner and dividers are profile/assets/*.svg. Pins are set by hand on the profile page.
-->
