
<div align="center">

  <img
    src="https://capsule-render.vercel.app/api?type=rect&color=0:0B1426,100:0CA6E8&height=180&section=header&text=Faraz%20Mubeen%20Haider&fontSize=42&fontColor=ffffff&fontAlignY=55"
    alt="Faraz Mubeen Haider — Software Engineer"
    width="100%"
  />

  <br/>

  <a href="https://www.linkedin.com/in/faraz369">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://faraz369.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://github.com/faraz-369">
    <img src="https://img.shields.io/badge/GitHub-faraz--369-24292F?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://huggingface.co/Faraz618">
    <img src="https://img.shields.io/badge/Hugging_Face-Profile-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  </a>

</div>

---

## Developer Activity & Community

I use GitHub to build, document, and share engineering projects while participating in developer communities, technical programmes, and collaborative competitions.

<p align="center">
  <a href="https://github.com/faraz-369">
    <img src="https://img.shields.io/github/followers/faraz-369?style=for-the-badge&label=GitHub%20Followers" alt="GitHub followers"/>
  </a>
  <a href="https://github.com/faraz-369?tab=repositories">
    <img src="https://img.shields.io/github/stars/faraz-369?style=for-the-badge&label=GitHub%20Stars" alt="GitHub stars"/>
  </a>
</p>

<p align="center">
  <a href="https://rankistan.dev/#faraz-369">
    <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Frankistan-summary-api.academics-ali.workers.dev%2Fapi%2Fbadge%2Ffaraz-369&style=for-the-badge" alt="Rankistan developer ranking"/>
  </a>
  <a href="https://user-badge.committers.top/pakistan/faraz-369">
    <img src="https://user-badge.committers.top/pakistan/faraz-369.svg" alt="Pakistan GitHub activity ranking"/>
  </a>
</p>

<p align="center">
  <a href="https://lablab.ai/u/@Faraz_Mubeen">
    <img src="https://img.shields.io/badge/LabLab.ai-Hackathon%20Profile-6C5CE7?style=for-the-badge" alt="LabLab profile"/>
  </a>
</p>

*GitHub statistics and rankings are dynamic and reflect activity on their respective platforms. They are not measures of engineering proficiency.*

## Recognition & Competitive Achievements

| Programme / Competition | Achievement |
|---|---|
| **IBM Granite Generative AI Hackathon** | Winning team — PolyEns |
| **CALICO Spring 2025 Global Coding Competition** | 96th place — Team Hawkeye |
| **CS50 Puzzle Day** | Team Cipher Cracker solved all 9 puzzles and was listed among the winning teams |
| **Stanford Code in Place** | Selected as Section Leader in 2025 and 2026 |
| **BICON Accelerator, NUML** | BillBachao selected and continued into incubation |
| **AlgoVerse Research Program — EOE.ai × Omdena** | Accepted participant; 45% merit scholarship |

**Achievement evidence**

- [IBM Granite Hackathon — PolyEns team and submission](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)
- [CALICO Spring 2025 — Team Hawkeye result](https://lnkd.in/p/dvSMCMnP)
- [CS50 Puzzle Day — Team Cipher Cracker result](https://lnkd.in/p/dniXjMSN)
- [Code in Place 2026 — Section Leader selection](https://www.linkedin.com/feed/update/urn%3Ali%3Aactivity%3A7450596499068960769/)
- [Code in Place programme and professional profile](https://www.linkedin.com/in/faraz369)
- [BillBachao — BICON Accelerator selection and incubation](https://lnkd.in/p/dHW92p6b)
- [Additional professional recognitions](https://www.linkedin.com/in/faraz369)

*Team achievements are identified as team results; individual selections are described separately.*

## About Me

I am a Software Engineer focused on **backend application development, API engineering, and data-driven software systems**.

I work primarily with Python, FastAPI, PostgreSQL, and related technologies to build application backends, design data workflows, and implement services that support digital products.

My experience spans independent engineering projects, startup product development, data-processing automation, and collaborative technical programmes.

I am particularly interested in the engineering decisions behind dependable software: how application data is modelled and validated, how services interact, how failures are handled, and how systems remain understandable and maintainable as they evolve.

My professional direction is backend engineering, with a growing interest in system reliability and distributed-systems fundamentals.

## Engineering Focus

| Area | What I work on |
|---|---|
| **Backend Application Development** | API design, application logic, validation, authentication, and maintainable services |
| **Database Engineering** | Relational data modelling, PostgreSQL, transactions, migrations, and data integrity |
| **Data Processing** | ETL workflows, CSV ingestion, validation, transformation, and reporting |
| **Testing & Reliability** | Automated testing, failure handling, integration testing, and structured execution |
| **System Design** | Service boundaries, application architecture, and distributed-systems fundamentals |

## Selected Engineering Projects

### 1. AgentFault Lab

**A controlled environment for studying failures and recovery in multi-step agent workflows.**

`Python` `FastAPI` `Pydantic` `SQLite` `Docker` `Pytest` `GitHub Actions`

[Repository](https://github.com/faraz-369/agentfault-lab-Web) · [Live Interface](https://agentfault-lab-web.vercel.app/) · [Benchmark Methodology](https://github.com/faraz-369/agentfault-lab-Web/blob/main/docs/benchmark-methodology.md) · [Results](https://github.com/faraz-369/agentfault-lab-Web/tree/main/results)

**What I built**

- A modular Python backend with FastAPI endpoints and a command-line interface.
- Controlled failure injection for timeouts, exceptions, and malformed responses.
- Structured execution records and SQLite persistence.
- Retry and state-aware recovery policies.
- Explicit workflow invariant checks.
- Automated unit, API, integration, and regression tests.
- Docker Compose development environment and GitHub Actions CI configuration.

**Evaluation:** A documented 45-run baseline across three scenarios and three recovery policies using deterministic simulated tools.

**Engineering question:** How should a multi-step workflow detect failures, preserve state, and recover without violating its intended execution rules?

*Scope: This is a controlled engineering and research prototype. Its results do not establish production-wide AI-agent reliability.*

---

### 2. PortfolioPulse

**A multi-tenant portfolio reporting application demonstrating backend application engineering.**

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `JWT` `Docker` `Pytest`

[Repository](https://github.com/faraz-369/portfoliopulse)

PortfolioPulse models a reporting workflow in which organisations manage companies, reporting periods, structured submissions, reviews, and portfolio analytics.

**Backend engineering**

- Organisation-scoped data models and tenant isolation.
- JWT authentication and role-based access control.
- Password hashing with Argon2.
- Versioned reporting templates and reporting periods.
- CSV ingestion with actionable validation errors.
- Submission review, approval, and resubmission history.
- Idempotent retry handling and PostgreSQL consistency constraints.
- Approval-gated analytics, processing logs, and audit records.
- Database migrations with Alembic.
- Automated tests, Ruff configuration, Docker Compose, and GitHub Actions.

**Verification:** The repository documents 34 tests passing in a local verification run dated 10 November 2026, including five PostgreSQL integration tests.

The project uses synthetic data and is an independent demonstration application, not a deployed NIC Faisalabad system or a production-proven commercial product.

---

### 3. RAG Agent Failure Catalog

**Reproducible examples of silent failures in RAG systems and AI-agent workflows.**

`Python` `Pytest` `LLM Evaluation` `Reliability`

[Repository](https://github.com/faraz-369/rag-agent-failure-catalog)

A structured catalogue of failure patterns that can produce plausible but incorrect, incomplete, or unsupported outputs.

Each failure includes:

- A minimal reproduction.
- A detection approach.
- A mitigation or guardrail.
- An explanation of the failure and its limitations.
- Offline deterministic examples and optional live-model experiments.

The catalogue explores issues such as ungrounded answers, citation drift, retrieval misses, tool-calling loops, premature termination, context pollution, silent tool failures, and numeric or date hallucinations.

---

### 4. Data Quality & Anomaly Detection Pipeline

**A data-processing prototype for validating datasets and identifying anomalous records.**

`Python` `Pandas` `Scikit-learn` `Gradio`

[Repository](https://github.com/faraz-369/data-quality-pipeline) · [Live Demo](https://huggingface.co/spaces/Faraz618/data-quality-pipeline)

A data-processing application that accepts CSV files, evaluates data quality, identifies anomalous records using Isolation Forest and Z-score methods, and generates downloadable reports.

It explores data validation, missing-value analysis, duplicate detection, anomaly detection, risk classification, and reporting using synthetic transaction data.

## Product Engineering & Professional Experience

### MUSTER — Founder, Product & Engineering

Contributing to product direction, technical planning, and application development for an early-stage venture.

My involvement includes:

- Translating product requirements into technical work.
- Working through application structure and backend workflows.
- Contributing to integrations and product implementation.
- Evaluating engineering decisions in the context of product needs.

MUSTER was selected into the Qatar Science & Technology Park (QSTP) startup ecosystem.

### NIC Faisalabad — AI & Data Engineering Intern

Worked on Python-based data-processing and reporting workflows involving information associated with more than 30 portfolio companies.

My work included:

- Data extraction, transformation, and validation.
- Python-based reporting automation.
- Supporting KPI analysis and recurring reporting workflows.
- Reducing repetitive manual analyst tasks.

**Reported impact:** Approximately 60% less manual analyst effort and around 12 hours saved per week. These figures are self-reported estimates, not independently audited measurements.

### 1337 Ventures — Backend Development Contributor

Contributed to backend development during a six-week accelerator sprint for an early-stage SaaS MVP.

The work involved assigned Python/FastAPI backend functionality, including document-ingestion and structured-output workflows, as part of a small team.

### Stanford Code in Place — Section Leader

Selected for the 2025 and 2026 programmes.

Contributed to Python education by:

- Leading weekly learning sections.
- Explaining programming fundamentals and problem decomposition.
- Supporting learners through debugging and problem-solving.
- Helping students build confidence in their first programming experiences.

## Additional Projects & Technical Exploration

| Project | Focus |
|---|---|
| [ComplianceRAG](https://github.com/faraz-369/ComplianceRAG) | Document ingestion, vector retrieval, and source-grounded question answering |
| [HireMind-AI](https://github.com/faraz-369/HireMind-AI) | Job-description analysis, resume feedback, and interview-preparation prototype |
| [SafeLite](https://github.com/faraz-369/SafeLite) | Language-conditioned robotic manipulation research in simulation |
| [AdvancedLeadsGeneration-AI](https://github.com/faraz-369/AdvancedLeadsGeneration-AI) | Multi-agent lead evaluation; IBM Granite Hackathon winning team project |

## Technical Toolkit

**Languages**
- Python
- SQL
- JavaScript

**Backend & API Development**
- FastAPI
- REST APIs
- Pydantic
- SQLAlchemy

**Databases & Data Engineering**
- PostgreSQL
- SQLite
- Pandas
- FAISS

**Testing & Code Quality**
- Pytest
- HTTPX
- Ruff

**Development & Delivery**
- Git
- GitHub Actions
- Docker
- Docker Compose

**Additional Technical Exposure**
- Groq API
- Hugging Face
- Sentence Transformers
- LangChain
- Next.js
- Streamlit
- Gradio

## Education

**BS Software Engineering**  
National University of Modern Languages (NUML)  
2022–2026

## Current Engineering Focus

- PostgreSQL transactions, indexing, and database design.
- Authentication, authorisation, and application security.
- Asynchronous processing and background jobs.
- API reliability and integration testing.
- Logging, monitoring, and observability.
- Distributed-systems fundamentals and failure-handling patterns.

## Connect

I am interested in backend engineering opportunities and collaborating with teams building software products, APIs, and data-intensive applications.

- **Email:** faraz.outreach8@gmail.com
- **LinkedIn:** [linkedin.com/in/faraz369](https://www.linkedin.com/in/faraz369)
- **Portfolio:** [faraz369.vercel.app](https://faraz369.vercel.app/)
- **GitHub:** [github.com/faraz-369](https://github.com/faraz-369)
- **Hugging Face:** [Faraz618](https://huggingface.co/Faraz618)
- **LabLab:** [Faraz Mubeen](https://lablab.ai/u/@Faraz_Mubeen)

---

<div align="center">

**Engineering backend systems. Exploring reliability. Building useful software.**

</div>
