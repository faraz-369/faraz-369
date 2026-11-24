<div align="center">

# Faraz Mubeen Haider

### Applied AI Engineer

**I build the Python backends behind AI features, and I test how those features fail.**

Python · FastAPI · PostgreSQL · LLM evaluation and reliability

[Portfolio](https://faraz369.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/faraz369) · [Email](mailto:faraz.outreach8@gmail.com) · [Hugging Face](https://huggingface.co/Faraz618)

</div>

---

## About

I build the backend around AI features: APIs, data models, retrieval pipelines and agent workflows, with tests and evaluation, so that AI-enabled products behave predictably.

I start from the real problem, choose the simplest architecture that solves it, build it with tests, and measure whether it works. I treat AI components as parts of a system that need validation and failure handling, not as black boxes.

- **Now:** Full Stack Agentic AI Engineer at Techloset
- **Building next:** an invoice-to-payment agent scenario for AgentFault Lab, to measure extraction errors, duplicate actions and recovery policies on real models
- **Based in:** Faisalabad, Pakistan. Open to relocating to Germany (visa sponsorship needed)

## What I work on

| Backend and data | AI systems reliability |
|---|---|
| API design with FastAPI and Pydantic | Controlled failure injection |
| Authentication and role-based access | Structured execution traces |
| PostgreSQL modelling, constraints, migrations | Invariant checks |
| Validated data ingestion | Recovery-policy comparison |
| Automated tests and CI | Reproducible evaluation |

## Featured projects

### AgentFault Lab

A testing harness for failure and recovery behaviour in multi-step agent workflows.

**Problem:** agents call tools that time out, throw errors or return malformed data. A naive retry can repeat a side effect or report a task as done when it is not, and these failures are hard to compare without controlled, repeatable experiments.

- Injects timeouts, exceptions and malformed responses into workflow steps
- Records structured execution traces and workflow state (JSONL and SQLite)
- Checks explicit invariants, such as "no duplicated operation" and "no false completion"
- Compares no-recovery, blind-retry and state-aware recovery policies
- Runs reproducible experiments through a FastAPI service, a CLI and a web dashboard

**Stack:** Python · FastAPI · Pydantic · SQLite · Pytest · Docker · Next.js

**Status:** research prototype with a documented 45-run simulated baseline. In the simulator, blind retry duplicated a state-changing update that state-aware recovery avoided. It is not proof of production-wide agent reliability; the benchmark methodology and limits are in `docs/`.

[Repository](https://github.com/faraz-369/agentfault-lab-Web) · [Live demo](https://agentfault-lab-web.vercel.app/)

### PortfolioPulse

A multi-tenant reporting backend focused on data integrity.

**Problem:** reporting data for several tenants has to stay separated, validated and auditable.

- Tenant-aware data separation
- JWT authentication and role-based access
- Validated CSV ingestion
- PostgreSQL constraints and relational modelling, with versioned Alembic migrations
- Approval workflow and audit records

**Stack:** Python · FastAPI · PostgreSQL · SQLAlchemy · Alembic · Docker · Pytest

**Status:** working application on synthetic data. 34 tests passed in a local run on 10 November 2026, including five PostgreSQL integration tests. Not deployed and not security-audited.

[Repository](https://github.com/faraz-369/portfoliopulse)

### More repositories

| Project | What it is | Stack |
|---|---|---|
| [RAG Agent Failure Catalog](https://github.com/faraz-369/rag-agent-failure-catalog) | Reproducible failure modes in RAG and agent workflows (ungrounded answers, retrieval misses, tool loops, premature termination), with detection and mitigation examples | Python, Pytest |
| [ComplianceRAG](https://github.com/faraz-369/ComplianceRAG) | Multi-agent RAG application in which a critic agent checks answers for citation support and groundedness | Python, FAISS, Sentence Transformers, Gradio |
| [Data Quality & Anomaly Detection](https://github.com/faraz-369/data-quality-pipeline) | CSV validation and anomaly detection (Isolation Forest, z-score) with downloadable reports. [Live demo](https://huggingface.co/spaces/Faraz618/data-quality-pipeline) | Python, Pandas, scikit-learn, Gradio |
| [Advanced Leads Generation AI](https://github.com/faraz-369/AdvancedLeadsGeneration-AI) | Multi-agent lead assessment with historical deal context. Team project for the IBM Granite Generative AI Hackathon | Python |

## Technical toolkit

| Area | Tools and practices |
|---|---|
| Backend | Python, FastAPI, Pydantic, REST APIs, JWT authentication, role-based access |
| Data | PostgreSQL, SQL, SQLAlchemy, Alembic, SQLite, Pandas |
| Applied AI | LLM API integration (Groq, Hugging Face), RAG with FAISS and Sentence Transformers, multi-agent workflows, LangChain, scikit-learn |
| Quality and evaluation | Pytest, failure injection, structured traces, invariant checks, reproducible experiments |
| Delivery | Docker, Docker Compose, GitHub Actions, Git |

**Learning now:** tracing and evals on real agent frameworks, TypeScript, cloud deployment and monitoring, AI security and prompt injection.

## Experience

| Organisation | Role | Period |
|---|---|---|
| Techloset | Full Stack Agentic AI Engineer | Nov 2026 – Present |
| MUSTER (Qatar-based startup) | Product Engineer | Jan 2026 – Oct 2026 |
| 1337 Ventures accelerator | Backend Developer, startup team (six-week sprint) | 2025 |
| NIC Faisalabad | Data Analytics Intern | Jan 2024 – Aug 2024 |
| Stanford Code in Place | Section Leader (volunteer) | 2026 |

Details are on [LinkedIn](https://www.linkedin.com/in/faraz369) and in my [CV](https://faraz369.vercel.app/Faraz_Mubeen_Haider_CV.pdf).

**Education:** BS Software Engineering, National University of Modern Languages (NUML), Faisalabad, 2026.

**Hackathons:** AI prototypes built in 13+ international online hackathons on lablab.ai, 2024–2026.

---

<div align="center">

**Open to conversations about applied AI engineering, backend roles and reliable agent systems.**

[Email](mailto:faraz.outreach8@gmail.com) · [LinkedIn](https://www.linkedin.com/in/faraz369) · [Portfolio](https://faraz369.vercel.app/)

</div>
