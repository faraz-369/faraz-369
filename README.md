<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:070d18,55:0e2034,100:2bb3a8&height=190&section=header&text=Faraz%20Mubeen%20Haider&fontColor=f1f6fa&fontSize=40&fontAlignY=38&desc=Backend%20Software%20Engineer%20%E2%80%A2%20Python%20%E2%80%A2%20APIs%20%E2%80%A2%20Data%20Systems&descColor=8db4c6&descSize=16&descAlignY=63" width="100%" alt="Faraz Mubeen Haider — Backend Software Engineer" />

### Backend Software Engineer

**Python · FastAPI · PostgreSQL · REST APIs · Data-Driven Backend Systems**

I build reliable APIs, backend services and data-driven software systems for modern digital products —
with an emphasis on sound data modelling, explicit error handling, reproducible testing and maintainable architecture.

📍 Pakistan · Open to remote roles with international teams

<a href="mailto:faraz.outreach8@gmail.com"><img src="https://img.shields.io/badge/Email-faraz.outreach8%40gmail.com-0e2034?style=flat-square&logo=gmail&logoColor=5ED6E8" alt="Email" /></a>
<a href="https://linkedin.com/in/faraz369"><img src="https://img.shields.io/badge/Linkedin-Connect-0e2034?style=flat-square&logo=linkedin&logoColor=5ED6E8" alt="LinkedIn" /></a>
<a href="https://github.com/faraz-369"><img src="https://img.shields.io/badge/GitHub-faraz--369-0e2034?style=flat-square&logo=github&logoColor=5ED6E8" alt="GitHub" /></a>
<a href="https://huggingface.co/Faraz618"><img src="https://img.shields.io/badge/Hugging_Face-Spaces-0e2034?style=flat-square&logo=huggingface&logoColor=5ED6E8" alt="Hugging Face" /></a>
<a href="https://lablab.ai/u/@Faraz_Mubeen"><img src="https://img.shields.io/badge/LabLab-Hackathons-0e2034?style=flat-square&logoColor=5ED6E8" alt="LabLab" /></a>

</div>

---

## About Me

I'm a software engineer focused on the backend: application logic, APIs, relational data, integrations and the reliability work that keeps systems predictable under failure.

My path spans professional data-engineering work (ETL and KPI reporting across 30+ portfolio companies at NIC Faisalabad), startup product engineering (MUSTER, selected for the Qatar Science & Technology Park ecosystem), a backend contribution for an early-stage startup via 1337 Ventures, and teaching Python fundamentals as a Stanford Code in Place Section Leader.

Alongside backend work, I build applied AI systems — retrieval pipelines, agent workflows and evaluation harnesses — where my main interest is the engineering around the model: grounding, validation, failure detection and regression testing.

**How I work:** Understand → Design → Implement → Test → Evaluate → Improve

---

## Selected Engineering Projects

Projects are presented with their engineering context, evidence links and stated limitations. I prioritise work where the implementation, tests and trade-offs can be inspected.

### 1 · AgentFault Lab — Fault-Injection & Recovery Testing for Agent Workflows

`Python` `FastAPI` `SQLite` `Docker` `GitHub Actions`

A local-first laboratory for **controlled fault injection and recovery experiments** in multi-step agent workflows. Define a workflow and its invariants, inject a known failure at a controlled point, record structured execution events, compare recovery policies (`none` / `retry` / `state_aware`), and export scenarios as regression tests.

- Deterministic simulator with timeout, exception, malformed-response and repeated-response faults — no LLM or paid API required
- Append-only JSONL event traces + SQLite run store; invariant checker and failure analyser
- FastAPI service (`/runs`, `/experiments`, `/scenarios`) plus CLI; unit, API, integration, regression and execution-bound tests
- Dockerfile, Docker Compose, CI across Python 3.10–3.12, threat model and benchmark methodology docs

**Status:** research prototype with a deterministic simulator — results demonstrate harness behaviour, not production-wide reliability (stated in-repo).

<a href="https://github.com/faraz-369/agentfault-lab"><img src="https://img.shields.io/badge/Source_Code-GitHub-0e2034?style=flat-square&logo=github&logoColor=5ED6E8" alt="Source code" /></a>

### 2 · SQLSense — Safe, Self-Correcting Natural-Language-to-SQL

`Python` `FastAPI` `SQLAlchemy` `sqlglot` `Evals`

A natural-language-to-SQL assistant built **evals-first**: a question is planned by an LLM, passed through a **deterministic safety guard** (sqlglot AST validation, SELECT-only enforcement), executed read-only, and self-corrected from execution feedback (max 2 attempts).

- Deterministic guard means safety does not depend on prompt behaviour
- Golden-set evaluation harness (`22/22` on the current deterministic set) run as part of development
- Architecture decision records (ADRs) documenting safety, provider and eval-first choices
- Honest scope: small golden set, not a large-scale benchmark (e.g. BIRD); stated in-repo

<a href="https://github.com/faraz-369/sqlsense"><img src="https://img.shields.io/badge/Source_Code-GitHub-0e2034?style=flat-square&logo=github&logoColor=5ED6E8" alt="Source code" /></a>

### 3 · Spotter Fuel Route API — Django Backend Assessment

`Python` `Django` `Django REST Framework` `OSRM` `Shapely`

A Django REST API that computes the **cost-optimal fuel stops** for a US driving route: geocodes start/finish (Nominatim), routes via OSRM, filters ~6,000 stations to a 5-mile corridor with Shapely, and runs a greedy fill-strategy optimizer under tank/range constraints.

- Clean service-layer separation: `geocoding.py` / `routing.py` / `optimization.py`
- Custom `import_fuel` management command for CSV ingestion (6,092 stations imported, duplicates collapsed)
- Documents assumptions and production limitations (single routing provider, Nominatim rate limits)

<a href="https://github.com/faraz-369/spotter-assessment"><img src="https://img.shields.io/badge/Source_Code-GitHub-0e2034?style=flat-square&logo=github&logoColor=5ED6E8" alt="Source code" /></a>

### 4 · Data Quality & Anomaly Detection Pipeline

`Python` `Pandas` `scikit-learn` `Gradio` `Hugging Face Spaces`

A data-processing pipeline: CSV ingestion → data-quality report (missing values, duplicates, imputation) → **dual-method anomaly detection** (IsolationForest for structural outliers + Z-score for statistical outliers) → per-record plain-English explanations → cleaned data, flagged records and a timestamped compliance report.

- Consensus risk tiering (HIGH / MEDIUM / CLEAN) to control false positives
- Audit-ready outputs with UTC timestamps and method attribution
- Single-file, copy-paste deployable; live demo below

<a href="https://github.com/faraz-369/data-quality-pipeline"><img src="https://img.shields.io/badge/Source_Code-GitHub-0e2034?style=flat-square&logo=github&logoColor=5ED6E8" alt="Source code" /></a>
<a href="https://huggingface.co/spaces/Faraz618/data-quality-pipeline"><img src="https://img.shields.io/badge/Live_Demo-Hugging_Face_Space-2BB3A8?style=flat-square&logo=huggingface&logoColor=white" alt="Live demo" /></a>

<details>
<summary><b>Applied AI & LLM Projects</b> — supporting evidence of AI integration into backend applications</summary>
<br/>

**AdvancedLeadsGeneration-AI — Multi-Agent Lead Qualification** · *IBM Granite Hackathon Winner (Team PolyEns, Feb 2025)*
Multi-agent debate architecture (advocate vs. risk surfaces, reconciled against historical deal data) with a FastAPI backend exposing the workflow as REST APIs and a Next.js frontend, built on IBM Watsonx.ai with IBM Granite models.
<a href="https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens">Hackathon project page</a> · Evidence of the win on the <a href="https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite">official recap</a>

**ComplianceRAG — Retrieval with a Groundedness Critic**
Three-stage pipeline (Retrieval → Generation → independent Critic agent) that scores answer groundedness, validates citations and flags low-confidence output for human review. FAISS + sentence-transformers, deployed on Hugging Face Spaces.
<a href="https://github.com/faraz-369/ComplianceRAG">Source code</a> · <a href="https://huggingface.co/spaces/Faraz618/ComplianceRAG">Live demo</a>

**RAG & Agent Failure Catalog — `rag-agent-failure-catalog`**
A catalog of ten silent failure modes in RAG/agent systems (ungrounded answers, citation drift, tool-calling loops, silent tool failure…), each with a minimal reproduction, a detector and a mitigation. Offline-first, tested, MIT-licensed.
<a href="https://github.com/faraz-369/rag-agent-failure-catalog">Source code</a>

**HireMind-AI — Career Workflow Assistant** · Streamlit application integrating LLMs (Groq / LLaMA 3.1) for multi-step resume analysis, ATS scoring, cover-letter generation and interview preparation. Live on Hugging Face Spaces.
<a href="https://github.com/faraz-369/HireMind-AI">Source code</a> · <a href="https://huggingface.co/spaces/Faraz618/HireMind-AI">Live demo</a>

</details>

---

## Professional Experience

| Period | Role & Organisation | Focus |
| --- | --- | --- |
| 2026 — present | **Startup Founder & Product Engineering — MUSTER** (selected for the Qatar Science & Technology Park ecosystem) | Product direction, technical planning, backend architecture and software development. Venture selection and shipped product capability are separate claims — product progress is documented as it is established. |
| Jan – Aug 2024 | **AI / Data Engineering Intern — NIC Faisalabad** | Python ETL pipelines (Pandas, SQLAlchemy, PostgreSQL), KPI reporting and reporting automation across a portfolio of 30+ companies. Reported outcome: ~60% reduction in manual analyst time (~12 hours/week); these figures are self-reported historical outcomes. Company data remains confidential. |
| Jun – Sep 2025 | **Project-Based Backend Contribution — 1337 Ventures** (early-stage startup project) | Backend-oriented implementation in an MVP/accelerator environment. My contribution covered the tasks I was assigned, not ownership of the full product. |
| 2025 & 2026 | **Section Leader — Stanford Code in Place** | Teaching Python fundamentals through weekly live sessions: debugging support, problem-solving guidance and technical feedback for a global learner cohort. |

---

## Recognition

- 🏆 **IBM Granite Generative AI Hackathon — Winner** (Team PolyEns, February 2025) — verified on lablab.ai
- 🎓 **Stanford Code in Place — Section Leader**, selected 2025 and 2026
- 🧩 Harvard CS50x Puzzle Day 2025 — perfect score (9/9), as reported
- 🔬 AlgoVerse Research Program (EOE.ai × Omdena) — accepted with a reported 45% merit scholarship
- 🚀 BICON Startup Incubation — selected for a final-year project
- 🌍 Multiple international hackathon participations on lablab.ai — <a href="https://lablab.ai/u/@Faraz_Mubeen">profile</a>

---

## Technical Skills

| Category | Technologies & concepts |
| --- | --- |
| Languages | Python, SQL, TypeScript |
| Backend | FastAPI, Django / Django REST Framework, REST API design, application architecture |
| Databases | PostgreSQL, SQLite, SQLAlchemy, relational data modelling |
| Data processing | Pandas, ETL pipelines, data validation, anomaly detection |
| Testing & reliability | pytest, regression testing, evaluation harnesses, invariant checking, fault injection |
| AI integration | RAG (FAISS, sentence-transformers), LLM APIs (Groq, Hugging Face, IBM Watsonx), multi-agent workflows, groundedness evaluation |
| DevOps | Docker, Docker Compose, GitHub Actions CI, Hugging Face Spaces |

*Used across the projects linked above; depth varies by project and is documented per-repository.*

---

## Engineering Principles

1. **Understand the problem before choosing the technology.** Software should solve an actual problem, not demonstrate a framework.
2. **Treat data as a first-class engineering responsibility.** Validation, consistent models and predictable transformations.
3. **Design for failure.** Errors should be handled explicitly; integrations and retries need bounds and invariants.
4. **Test actual behaviour, not assumptions.** Meaningful tests and reproducible evaluation over demo-driven claims.
5. **Document decisions and limitations.** Architecture, trade-offs and scope should be readable by another engineer.

---

## Currently Engineering

Maintainable Python backends with FastAPI · PostgreSQL + SQLAlchemy data models · authentication & authorisation · automated testing · background processing and reliable integrations · Docker/CI deployment · and applying the same rigour (grounding, evaluation, failure analysis) to AI-integrated applications.

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=faraz-369&show_icons=true&hide_border=true&bg_color=0A1424&title_color=5ED6E8&icon_color=2BB3A8&text_color=8DB4C6" alt="GitHub statistics" height="150" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=faraz-369&layout=compact&hide_border=true&langs_count=8&bg_color=0A1424&title_color=5ED6E8&text_color=8DB4C6" alt="Most-used languages in public repositories" height="150" />

</div>

---

## Let's Connect

I'm interested in Backend Software Engineering roles involving Python, APIs, relational databases, data-intensive systems and — where relevant — AI capabilities integrated into real backend applications.

✉️ faraz.outreach8@gmail.com · 💼 linkedin.com/in/faraz369 · 🤗 huggingface.co/Faraz618

<div align="center">

*Build reliable software. Solve meaningful problems. Improve through engineering.*

</div>
