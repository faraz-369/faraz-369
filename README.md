<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:070d18,55:0e2034,100:2bb3a8&height=200&section=header&text=Faraz%20Mubeen%20Haider&fontColor=f1f6fa&fontSize=40&fontAlignY=40&desc=Backend%20Software%20Engineer%20%E2%80%A2%20Python%20%E2%80%A2%20Backend%20Systems&descColor=8db4c6&descSize=16&descAlignY=62" width="100%" alt="Faraz Mubeen Haider — Backend Software Engineer" />

[![Rankistan rank badge](https://img.shields.io/endpoint?url=https%3A%2F%2Frankistan-summary-api.academics-ali.workers.dev%2Fapi%2Fbadge%2Ffaraz-369&style=flat)](https://rankistan.dev/#faraz-369)

</div>

## About Me

I am a Software Engineer specialising in **backend application development**, building reliable APIs, backend services and data-driven software systems for modern digital products.

My primary engineering interests include Python backend development, REST API design, relational databases, application architecture, data processing and software reliability.

I focus on building applications that are understandable, maintainable and practical to operate. My experience includes Python-based backend development, database-backed workflows, ETL pipelines, reporting systems and application integrations.

I also explore applied AI as a supporting engineering area, integrating retrieval systems and LLM-powered workflows into practical software applications.

## Core Engineering Capabilities

| Engineering area | Focus |
|---|---|
| Backend development | Python, FastAPI, REST APIs, application logic |
| Database engineering | PostgreSQL, SQLAlchemy, SQLite, relational data modelling |
| Data processing | Pandas, ETL workflows, data transformation and validation |
| Application architecture | Modular design, service integration and maintainable systems |
| Software reliability | Testing, error handling, failure analysis and reproducible execution |
| Applied AI integration | Retrieval pipelines, LLM applications and groundedness evaluation |

## Recognition & Community

- **Rankistan:** Live ranking in the Pakistani developer leaderboard. The badge above links to my current position; rankings may change as the leaderboard refreshes.
- **Stanford Code in Place:** Selected as a Section Leader for the 2025 and 2026 programs.
- **BICON-NUML:** BillBachao, a final-year project, selected for the BICON accelerator cohort.
- **AlgoVerse Research Program (EOE.ai × Omdena):** Accepted into the research program.
- **IBM Granite Generative AI Hackathon:** Team PolyEns contributor; collaborative project submission: AdvancedLeadsGeneration-AI.
- **LabLab:** Public profile currently lists 17 hackathon events and 12 submissions.

## Selected Engineering Projects

### 1. AgentFault Lab — Backend Systems & Reliability Engineering

**Python · FastAPI · SQLite · Pydantic · Docker · Next.js**

An open-source engineering and research prototype for reproducing failures and evaluating recovery behaviour in multi-step agent workflows.

AgentFault Lab provides a controlled environment for injecting known failures, observing execution behaviour and testing recovery strategies against explicitly defined invariants.

**What it does**

- Defines reproducible workflow scenarios.
- Simulates controlled failures such as timeouts, exceptions and malformed responses.
- Records structured execution events and state transitions.
- Evaluates explicit system invariants.
- Compares no-recovery, retry and state-aware recovery policies.
- Stores experiment summaries, traces and run records.
- Provides a FastAPI interface and command-line execution tools.

**Engineering implementation**

- Modular Python application architecture.
- FastAPI endpoints and CLI.
- Pydantic-based validation.
- SQLite persistence.
- Structured JSON and JSONL experiment records.
- Unit, API, integration and regression tests.
- Docker and Docker Compose.
- GitHub Actions.

**Evaluation and reproducibility**

The repository documents a 45-run baseline across three scenarios and three recovery policies. The implementation uses deterministic simulated tools; results evaluate the controlled experiment harness and are not claims about production-wide AI-agent reliability.

**Project status:** Working research and engineering prototype.

**Explore:**

- [GitHub Repository](https://github.com/faraz-369/agentfault-lab-Web)
- [Project Interface](https://agentfault-lab-web.vercel.app/)
- [Benchmark Methodology](https://github.com/faraz-369/agentfault-lab-Web/blob/main/docs/benchmark-methodology.md)
- [Experiment Results](https://github.com/faraz-369/agentfault-lab-Web/tree/main/results)

### 2. ComplianceRAG — Evidence-Grounded Information Retrieval

**Python · RAG · FAISS · Sentence Transformers · Gradio**

An experimental document question-answering application exploring retrieval-augmented generation with an additional groundedness review stage.

The documented workflow combines document ingestion, semantic retrieval, answer generation and a critic stage intended to identify claims that are insufficiently supported by retrieved evidence.

**Areas explored**

- Document ingestion and chunking.
- Semantic embeddings and vector retrieval.
- FAISS-based similarity search.
- Context-grounded answer generation.
- Citation and groundedness evaluation.
- Human review of questionable outputs.

**Explore:**

- [GitHub Repository](https://github.com/faraz-369/ComplianceRAG)
- [Hugging Face Space](https://huggingface.co/spaces/Faraz618/ComplianceRAG)

**Project status:** Experimental application prototype. The repository entry point and hosted Space configuration should be kept in sync.

## Professional Experience

### MUSTER — Startup Founder & Product Engineering

Building an early-stage software venture focused on practical digital products. My involvement includes product direction, technical planning, backend-oriented development and application engineering.

### NIC Faisalabad — AI / Data Engineering Intern

Worked on Python-based data processing and reporting workflows involving information from more than 30 portfolio companies.

**Engineering contributions**

- Python-based ETL workflows.
- Pandas data transformation.
- SQLAlchemy and PostgreSQL integration.
- Data validation and quality checks.
- KPI reporting and recurring workflow automation.

**Reported historical impact:** Approximately 60% reduction in manual analyst effort and around 12 hours saved per week. These figures are reported project outcomes, not independently published measurements. Original company data and confidential implementation details are not included in this profile.

### 1337 Ventures — Project-Based Backend Engineering Contribution

Contributed to selected backend development tasks within an early-stage startup/MVP environment. This describes my individual contribution, not ownership or independent development of the complete product.

### Stanford Code in Place — Section Leader

Selected as a Section Leader for the 2025 and 2026 programs. Responsibilities included teaching Python fundamentals, conducting live sessions, helping learners debug code, explaining problem-solving approaches and providing technical feedback.

## Additional Research & Application Projects

<details>
<summary><strong>SafeLite — Research-Oriented Robotic Manipulation System</strong></summary>

**Python · LLM Agents · Meta-World · MuJoCo · Simulation**

A research-oriented project exploring structured execution pipelines for language-conditioned robotic manipulation.

Areas of exploration include task planning, safety reasoning, execution, environment simulation, failure detection, self-correction and evaluation.

This is a research and experimentation project, not a primary backend application example.

[Explore SafeLite](https://github.com/faraz-369/SafeLite)

</details>

<details>
<summary><strong>HireMind-AI — Career Workflow Assistant</strong></summary>

**Python · Streamlit · Groq API · LLM Integration**

An LLM-powered application prototype for job-description analysis, skill-gap identification, resume assistance, cover-letter drafting and interview preparation.

The documented implementation uses Streamlit and JSON-based storage; it should not be interpreted as a PostgreSQL-backed service.

[Explore HireMind-AI](https://github.com/faraz-369/HireMind-AI)

</details>

## Technical Toolkit

| Category | Technologies |
|---|---|
| Programming | Python, SQL |
| Backend | FastAPI, REST APIs, Pydantic |
| Databases | PostgreSQL, SQLite, SQLAlchemy |
| Data processing | Pandas, ETL, data transformation and validation |
| Testing and quality | Pytest, HTTPX, Hypothesis, Ruff |
| Infrastructure | Docker, Docker Compose, GitHub Actions |
| AI application integration | Hugging Face Inference API, Groq, LLM application workflows |
| Retrieval | FAISS, sentence-transformers |
| Application development | Gradio, Streamlit, Next.js |

Technologies are listed according to their use across projects and experience. Their inclusion does not imply equal proficiency or production experience in every tool.

## Current Engineering Focus

- Designing maintainable Python backend applications.
- Building well-structured REST APIs with FastAPI.
- Relational database design and reliable data persistence.
- Authentication and authorisation.
- Automated unit and integration testing.
- Background processing and dependable service integrations.
- Data validation and reproducible processing pipelines.
- Docker-based development, CI/CD and deployment.
- Logging, monitoring and application observability.
- Integrating AI capabilities into practical backend applications.

## Engineering Principles

- **Understand before implementing:** Start with the actual problem, requirements and constraints.
- **Design clear interfaces:** Keep APIs, application boundaries and data models understandable.
- **Treat data as an engineering responsibility:** Prioritise validation, consistency and predictable transformations.
- **Design for failure:** Handle integration and background-process failures deliberately.
- **Test actual behaviour:** Prefer reproducible tests and observable results over assumptions.
- **Build maintainable software:** Value readable implementation, appropriate documentation and sensible architecture.

## Education

**Bachelor of Science in Software Engineering**  
National University of Modern Languages (NUML) · 2022–2026

## Contact

- **Email:** [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)
- **LinkedIn:** [linkedin.com/in/faraz369](https://linkedin.com/in/faraz369)
- **Portfolio:** [faraz369.vercel.app](https://faraz369.vercel.app/)
- **Hugging Face:** [huggingface.co/Faraz618](https://huggingface.co/Faraz618)
- **LabLab:** [lablab.ai/u/@Faraz_Mubeen](https://lablab.ai/u/@Faraz_Mubeen)

<div align="center">

---

**Build reliable software. Solve meaningful problems. Improve through engineering.**

</div>
