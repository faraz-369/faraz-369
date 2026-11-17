<div align="center">

  <!-- PROFILE BANNER -->
  <img
    src="https://capsule-render.vercel.app/api?type=rect&color=0:101B27,100:0F766E&height=220&section=header&text=Faraz%20Mubeen%20Haider&fontSize=44&fontColor=F1F5F9&fontAlignY=38&desc=BACKEND%20ENGINEER%20%C2%B7%20AI%20SYSTEMS&descSize=19&descColor=5EEAD4&descAlignY=62"
    width="100%"
    alt="Faraz Mubeen Haider — Backend Engineer, AI Systems"
  />

  <br/>

  **Python · FastAPI · PostgreSQL** &nbsp;·&nbsp; **LLM & agent workflows** &nbsp;·&nbsp; **Testing & evaluation**

  <br/>

  *I make AI systems secure, reliable, and resilient.*

  <br/><br/>

  <a href="https://www.linkedin.com/in/faraz369">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0F766E?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://faraz369.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Explore-0F766E?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://github.com/faraz-369">
    <img src="https://img.shields.io/badge/GitHub-Profile-334155?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://huggingface.co/Faraz618">
    <img src="https://img.shields.io/badge/Hugging_Face-Profile-334155?style=flat-square&logo=huggingface&logoColor=white" alt="Hugging Face"/>
  </a>

</div>

---

## About Me

I build the backend software around LLM features, and I make it testable, reliable, and measurable.

I work mainly with Python, FastAPI, and PostgreSQL. My projects focus on database-backed services, retrieval-augmented generation (RAG), and multi-step agent workflows, each with automated tests or explicit checks.

I currently work as a Full Stack Agentic AI Engineer at Techloset. Before that, I worked on data-processing automation at NIC Faisalabad, product prototypes at MUSTER, and backend components at 1337 Ventures.

## What I Focus On

| Area | Focus |
|---|---|
| **Backend Engineering** | API design, application logic, authentication, integrations, and maintainable services |
| **Applied AI** | RAG applications, agent workflows, LLM integrations, structured outputs |
| **Testing & Evaluation** | Automated tests, invariant checks, failure injection, and reproducible evaluation |
| **Data Engineering** | Data extraction, transformation, validation, ETL workflows, and reporting |
| **Database Engineering** | PostgreSQL, relational modelling, migrations, and data integrity |

---

## Featured Engineering Projects

### 01. PortfolioPulse

**A multi-tenant portfolio reporting application demonstrating backend application engineering.**

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `JWT` `Docker` `Pytest`

[Repository](https://github.com/faraz-369/portfoliopulse)

PortfolioPulse models a reporting workflow in which organisations manage companies, reporting periods, structured submissions, reviews, and portfolio analytics.

**Engineering implementation**

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

### 02. AgentFault Lab

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

**Evaluation:** A documented 45-run baseline across three scenarios and three recovery policies using deterministic simulated tools. Methodology and results are linked above.

**Engineering question:** How should a multi-step workflow detect failures, preserve state, and recover without violating its intended execution rules?

*Scope: This is a controlled engineering and research prototype. Its results do not establish production-wide AI-agent reliability.*

---

### 03. RAG Agent Failure Catalog

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

### 04. Data Quality & Anomaly Detection Pipeline

**A data-processing prototype for validating datasets and identifying anomalous records.**

`Python` `Pandas` `Scikit-learn` `Gradio`

[Repository](https://github.com/faraz-369/data-quality-pipeline) · [Live Demo](https://huggingface.co/spaces/Faraz618/data-quality-pipeline)

A data-processing application that accepts CSV files, evaluates data quality, identifies anomalous records using Isolation Forest and Z-score methods, and generates downloadable reports.

It explores data validation, missing-value analysis, duplicate detection, anomaly detection, risk classification, and reporting using synthetic transaction data.

---

## Professional Experience

### Techloset — Full Stack Agentic AI Engineer
*November 2026 – Present*

Translating client business requirements into AI-powered software solutions.

- Analysing client challenges and turning business needs into technical requirements.
- Working with engineering teams on LLM-integrated workflows, from solution development through delivery.

### MUSTER — Product Engineer
*January 2026 – October 2026*

Defined and prototyped an AI-powered lead-qualification workflow for real-estate brokers.

- Mapped real-estate workflows (lead qualification, follow-ups, property-viewing coordination) and turned user needs into product functionality.
- Designed and developed prototypes demonstrating automated lead qualification.
- Ran product demos with prospective users to validate use cases and gather feedback.
- Researched and mapped prospects across Qatar, Pakistan, and selected GCC markets, and drafted ideal-customer-profile criteria to prioritise them.

MUSTER was selected into the Qatar Science & Technology Park (QSTP) startup ecosystem.

### lablab.ai — Applied AI Developer
*August 2024 – August 2026*

Built and demonstrated AI prototypes under hackathon deadlines, including as part of the winning team at the IBM Granite Generative AI Hackathon.

- Implemented retrieval-augmented generation workflows using document retrieval, embeddings, and semantic search.
- Integrated LLM capabilities into application prototypes built with Python, FastAPI, and REST APIs.
- Built multi-step agent workflows with task decomposition, structured outputs, and tool integration.

### Stanford Code in Place — Section Leader
*2025 and 2026 programmes*

Led weekly live Python sessions for beginner cohorts, guiding learners through exercises, debugging, and problem-solving, and giving feedback on assignments.

### 1337 Ventures — Backend Developer
*June 2025 – September 2025*

Contributed backend components to an AI automation SaaS MVP during a six-week accelerator sprint.

- Implemented backend functionality in Python and FastAPI for the MVP's AI automation features.
- Contributed to application workflows for document ingestion and structured-output generation.
- Worked with the startup team through product development and iteration.

### NIC Faisalabad — AI / Data Engineer
*January 2024 – August 2024*

Automated KPI reporting for a portfolio of 30+ startups.

- Built ETL workflows in Python, Pandas, SQLAlchemy, and PostgreSQL to process portfolio performance data.
- Automated recurring cohort, retention, and funding reports.
- Added data-quality checks to keep reporting outputs consistent and reliable.
- Used Jupyter and Papermill to make reports reproducible.

**Reported impact:** Associated with about 60% less manual analyst time and about 12 hours a week of repetitive spreadsheet work. These figures are self-reported estimates, not independently audited measurements.

---

## Recognition

| Programme / Competition | Achievement |
|---|---|
| **IBM Granite Generative AI Hackathon** | Winning team — PolyEns |
| **CS50 Puzzle Day** | Team Cipher Cracker solved all 9 puzzles and was listed among the winning teams |
| **Stanford Code in Place** | Selected as Section Leader in 2025 and 2026 |
| **BICON Accelerator, NUML** | BillBachao selected and continued into incubation |
| **AlgoVerse Research Program — EOE.ai × Omdena** | Accepted participant; 45% merit scholarship |

**Evidence**

- [IBM Granite Hackathon — PolyEns team and submission](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)
- [CS50 Puzzle Day — Team Cipher Cracker result](https://lnkd.in/p/dniXjMSN)
- [Code in Place 2026 — Section Leader selection](https://www.linkedin.com/feed/update/urn%3Ali%3Aactivity%3A7450596499068960769/)
- [BillBachao — BICON Accelerator selection and incubation](https://lnkd.in/p/dHW92p6b)
- [Additional professional recognitions](https://www.linkedin.com/in/faraz369)

*Team achievements are identified as team results; individual selections are described separately.*

---

## Additional Projects & Technical Exploration

| Project | Focus |
|---|---|
| [ComplianceRAG](https://github.com/faraz-369/ComplianceRAG) | Document ingestion, vector retrieval, and source-grounded question answering |
| [HireMind-AI](https://github.com/faraz-369/HireMind-AI) | Job-description analysis, resume feedback, and interview-preparation prototype |
| [SafeLite](https://github.com/faraz-369/SafeLite) | Language-conditioned robotic manipulation research in simulation |
| [AdvancedLeadsGeneration-AI](https://github.com/faraz-369/AdvancedLeadsGeneration-AI) | Multi-agent lead evaluation; IBM Granite Hackathon winning team project |

---

## Technical Toolkit

**Languages**

![Python](https://img.shields.io/badge/Python-334155?style=flat-square&logo=python&logoColor=5EEAD4)
![SQL](https://img.shields.io/badge/SQL-334155?style=flat-square&logo=postgresql&logoColor=5EEAD4)
![JavaScript](https://img.shields.io/badge/JavaScript-334155?style=flat-square&logo=javascript&logoColor=FACC15)

**Backend & API Development**

![FastAPI](https://img.shields.io/badge/FastAPI-334155?style=flat-square&logo=fastapi&logoColor=5EEAD4)
![REST APIs](https://img.shields.io/badge/REST_APIs-334155?style=flat-square)
![Pydantic](https://img.shields.io/badge/Pydantic-334155?style=flat-square)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-334155?style=flat-square&logo=sqlalchemy&logoColor=5EEAD4)

**Databases & Data Engineering**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-334155?style=flat-square&logo=postgresql&logoColor=5EEAD4)
![SQLite](https://img.shields.io/badge/SQLite-334155?style=flat-square&logo=sqlite&logoColor=5EEAD4)
![Pandas](https://img.shields.io/badge/Pandas-334155?style=flat-square&logo=pandas&logoColor=5EEAD4)
![FAISS](https://img.shields.io/badge/FAISS-334155?style=flat-square)

**Applied AI**

![Hugging Face](https://img.shields.io/badge/Hugging_Face-334155?style=flat-square&logo=huggingface&logoColor=5EEAD4)
![Sentence Transformers](https://img.shields.io/badge/Sentence_Transformers-334155?style=flat-square)
![Groq](https://img.shields.io/badge/Groq_API-334155?style=flat-square)

**Testing & Code Quality**

![Pytest](https://img.shields.io/badge/Pytest-334155?style=flat-square&logo=pytest&logoColor=5EEAD4)
![HTTPX](https://img.shields.io/badge/HTTPX-334155?style=flat-square)
![Ruff](https://img.shields.io/badge/Ruff-334155?style=flat-square)

**Development & Delivery**

![Git](https://img.shields.io/badge/Git-334155?style=flat-square&logo=git&logoColor=5EEAD4)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-334155?style=flat-square&logo=githubactions&logoColor=5EEAD4)
![Docker](https://img.shields.io/badge/Docker-334155?style=flat-square&logo=docker&logoColor=5EEAD4)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-334155?style=flat-square&logo=docker&logoColor=5EEAD4)

**Additional Technical Exposure**

- LangChain
- Next.js
- Streamlit
- Gradio

---

## Education

**BS Software Engineering**  
National University of Modern Languages (NUML)  
2022–2026

---

## Currently Deepening

- Evaluating LLM and agent workflows with measurable, reproducible tests.
- PostgreSQL transactions, indexing, and database design.
- Authentication, authorisation, and application security.
- Asynchronous processing and background jobs.
- Logging, monitoring, and observability.
- Distributed-systems fundamentals and service communication.

---

## Connect

I am looking for remote backend and AI-systems engineering roles, especially with teams in Europe.

<div align="center">

  <a href="mailto:faraz.outreach8@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-0F766E?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.linkedin.com/in/faraz369">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0F766E?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://faraz369.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Explore-0F766E?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>

  <br/><br/>

  <a href="https://github.com/faraz-369">
    <img src="https://img.shields.io/badge/GitHub-faraz--369-334155?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://huggingface.co/Faraz618">
    <img src="https://img.shields.io/badge/Hugging_Face-Faraz618-334155?style=flat-square&logo=huggingface&logoColor=white" alt="Hugging Face"/>
  </a>
  <a href="https://lablab.ai/u/@Faraz_Mubeen">
    <img src="https://img.shields.io/badge/LabLab-Faraz_Mubeen-334155?style=flat-square" alt="LabLab"/>
  </a>

  <br/><br/>

  *I engineer intelligent systems that continuously create measurable value.*

</div>
