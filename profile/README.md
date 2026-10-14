# Harshil Makhija

AI Systems Engineer · Bengaluru, India

I build the parts of an AI product that sit around the model: the agent loop, retrieval, the API, the queue, and the cloud it all runs on. What I care about most is what happens when something goes wrong.

[Email](mailto:harshilmakhija@outlook.com) · [LinkedIn](https://www.linkedin.com/in/harshil-makhija/) · [X](https://twitter.com/MakhijaHarshil) · [Hugging Face](https://huggingface.co/HarshilMaks)

## What I work on

- **LLM agents and multi-agent systems**
  - Orchestration, tool use and workflows where an agent proposes and a person approves anything that changes the outside world.
- **Retrieval and RAG pipelines**
  - Vector search and retrieval tuned for relevance, with answers that point back to sources you can open and check.
- **Model serving and LLMOps**
  - Models behind APIs, with experiment tracking, deployment and the monitoring needed to keep them healthy.
- **Backend APIs and system design**
  - REST and gRPC services, async workers and event-driven designs, built on PostgreSQL and Redis.
- **Cloud-native architecture**
  - Containerised, reproducible delivery on AWS and GCP, with infrastructure defined as code.
- **Deep learning and computer vision**
  - Model building and fine-tuning in PyTorch, from classification to geospatial imagery.

## How I build

Before an AI feature ships, it has to answer a few questions.

- **What can the agent touch?** Tools are scoped per task, and anything that reads untrusted input gets none.
- **Who approves it?** The agent drafts. A person signs off on anything that leaves the building.
- **What does a retry do?** Writes carry idempotency keys, so a second attempt never sends the email twice.
- **What if the outcome is unknown?** When a provider times out mid-write, a reconciliation job checks what happened instead of guessing.
- **Where did the answer come from?** Every claim links back to the passage that supports it.
- **How would I know it's wrong?** Traces, audit logs and evals, so a mistake shows up on a dashboard and not in a customer's inbox.

## What I build with

| Area | Tools |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **AI / ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat-square) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white) |
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |

## Contact

Email is the fastest way to reach me: [harshilmakhija@outlook.com](mailto:harshilmakhija@outlook.com)

<!--
Owner: Harshil. Last reviewed: 2026-10-14.
Review when: role or employer changes, a new job search starts, a major launch or talk, or the stack list stops matching real work.
Skill badges are static shields.io images (no live data). Pins are set by hand on the profile page.
-->
