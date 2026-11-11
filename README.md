 <div align="center">

  <!-- PROFILE BANNER -->
  <img
    src="https://capsule-render.vercel.app/api?type=rect&color=0:101B27,100:0F766E&height=220&section=header&text=Faraz%20Mubeen%20Haider&fontSize=44&fontColor=F1F5F9&fontAlignY=38&desc=SOFTWARE%20ENGINEER&descSize=19&descColor=5EEAD4&descAlignY=62"
    width="100%"
    alt="Faraz Mubeen Haider — Software Engineer"
  />

  <br/>

  **Backend Systems** &nbsp;·&nbsp; **Distributed Systems** &nbsp;·&nbsp; **Applied AI**

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

I am a **Software Engineer** interested in building reliable software systems, developing backend applications, and applying AI to practical engineering problems.

My primary engineering work focuses on Python, FastAPI, PostgreSQL, API development, data processing, and application architecture.

I am particularly interested in the engineering foundations behind modern software products:

- Designing maintainable backend applications and APIs.
- Modelling data and building reliable database-backed services.
- Understanding distributed systems, service communication, and failure handling.
- Integrating AI capabilities into useful software applications.
- Evaluating system behaviour through testing, experimentation, and reproducible workflows.

My work spans independent engineering projects, startup product development, data-processing automation, AI application prototypes, and collaborative technical programmes.

I aim to build software that is understandable, dependable, maintainable, and useful in real-world applications.

## Engineering Focus

| Area | Focus |
|---|---|
| **Backend Engineering** | API design, application logic, authentication, integrations, and maintainable services |
| **Distributed Systems** | Service communication, reliability, failure handling, state management, and system fundamentals |
| **Database Engineering** | PostgreSQL, relational modelling, transactions, migrations, and data integrity |
| **Applied AI** | RAG applications, AI integrations, agent workflows, evaluation, and reliability |
| **Data Engineering** | Data extraction, transformation, validation, ETL workflows, and reporting |
| **Testing & Reliability** | Automated testing, integration testing, error handling, and reproducible evaluation |

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

**Evaluation:** A documented 45-run baseline across three scenarios and three recovery policies using deterministic simulated tools.

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

---

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

**Applied AI & AI Frameworks**

![Hugging Face](https://img.shields.io/badge/Hugging_Face-334155?style=flat-square&logo=huggingface&logoColor=5EEAD4)
![LangChain](https://img.shields.io/badge/LangChain-334155?style=flat-square)
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

- Next.js
- Streamlit
- Gradio

---

## Developer Activity & Community

I use GitHub to build, document, and share engineering projects while participating in developer communities, technical programmes, and collaborative competitions.

<div align="center">

  <a href="https://github.com/faraz-369">
    <img src="https://img.shields.io/github/followers/faraz-369?style=flat-square&label=Followers&color=0F766E" alt="GitHub followers"/>
  </a>
  <a href="https://github.com/faraz-369?tab=repositories">
    <img src="https://img.shields.io/github/stars/faraz-369?style=flat-square&label=Stars&color=0F766E" alt="GitHub stars"/>
  </a>

  <br/><br/>

  <a href="https://rankistan.dev/#faraz-369">
    <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Frankistan-summary-api.academics-ali.workers.dev%2Fapi%2Fbadge%2Ffaraz-369&style=flat-square" alt="Rankistan developer ranking"/>
  </a>
  <a href="https://user-badge.committers.top/pakistan/faraz-369">
    <img src="https://user-badge.committers.top/pakistan/faraz-369.svg" alt="Pakistan GitHub activity ranking"/>
  </a>

  <br/><br/>

  <a href="https://lablab.ai/u/@Faraz_Mubeen">
    <img src="https://img.shields.io/badge/LabLab.ai-Hackathon%20Profile-0F766E?style=flat-square" alt="LabLab profile"/>
  </a>

</div>

*GitHub statistics and rankings are dynamic and reflect activity on their respective platforms. They are not measures of engineering proficiency.*

---

## Education

**BS Software Engineering**  
National University of Modern Languages (NUML)  
2022–2026

---

## Current Engineering Focus

- Backend application architecture and maintainable service design.
- PostgreSQL transactions, indexing, and database design.
- Distributed-systems fundamentals and service communication.
- Authentication, authorisation, and application security.
- Asynchronous processing and background jobs.
- API reliability, testing, and integration patterns.
- Logging, monitoring, and observability.
- Applied AI integration, RAG evaluation, and failure-handling patterns.

---

## Connect

I am interested in software engineering opportunities and collaborating with teams building backend applications, distributed software systems, and AI-enabled products.

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

  **Engineering systems. Understanding complexity. Applying intelligence.**

</div>
