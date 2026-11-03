<div align="center">

# Faraz Mubeen Haider

### Software Engineer | Python Backend & Applied AI Systems

I build backend software and AI-powered applications, with a focus on APIs, data-backed services, reliable integrations, and evaluation of intelligent workflows.

**Based in Pakistan · Open to full-time software engineering opportunities in Germany**

[LinkedIn](https://www.linkedin.com/in/faraz369) · [Email](mailto:faraz.outreach8@gmail.com) · [Hugging Face](https://huggingface.co/Faraz618) · [LabLab](https://lablab.ai/u/@Faraz_Mubeen)

</div>

---

## Profile

I'm a Software Engineering graduate focused on **Python backend engineering and applied AI**. My work spans backend services, APIs, data pipelines, and applications that integrate language models with retrieval, external tools, and structured workflows.

Examples of my engineering experience include:

- Developing Python ETL and reporting pipelines for **30+ startup portfolio companies**, using Pandas, SQLAlchemy, and PostgreSQL. The work reduced manual analyst time by approximately **60%** and removed around **12 hours of weekly spreadsheet work**.
- Designing and implementing backend functionality for an AI automation SaaS MVP, including work around document ingestion, LLM routing, and structured output generation using FastAPI.
- Building applied-AI prototypes involving retrieval-augmented generation (RAG), semantic search, LLM integrations, and multi-step agent workflows.
- Teaching Python programming, debugging, and problem-solving as a Stanford Code in Place Section Leader.

I care about the engineering underneath a working product: clear API contracts, understandable data models, testable behavior, failure handling, and systems that can be inspected and improved.

## Engineering Focus

| Area | Technologies and concepts |
|---|---|
| **Backend engineering** | Python, FastAPI, REST APIs |
| **Data and persistence** | PostgreSQL, SQL, SQLAlchemy, Pandas, ETL pipelines |
| **Applied AI** | LLM integrations, RAG, embeddings, semantic search, structured outputs |
| **Agent workflows** | Tool calling, multi-step workflows, LangChain, CrewAI, AutoGen |
| **Evaluation and reliability** | Failure analysis, invariant checks, recovery policies, trace-based evaluation |
| **Application development** | Next.js, Streamlit, Gradio |
| **Development and delivery** | Git, testing, Docker, GitHub Actions, Hugging Face Spaces |

This list reflects technologies I've used across work and projects. It does not imply equal depth or production experience in every item.

---

## Featured Engineering Projects

### 1. [AgentFault Lab](https://github.com/faraz-369/agentfault-lab)

**A reproducible fault-injection and recovery-testing lab for AI agents.**

AgentFault Lab explores how multi-step agent workflows behave when tools fail or return unexpected results. It uses controlled simulated faults, structured execution records, explicit invariants, and recovery-policy comparisons to make failure behavior reproducible and inspectable.

**What it demonstrates**

- A deterministic tool simulator and controlled fault injection for timeouts, exceptions, malformed responses, and repeated-response conditions.
- Explicit invariant checks for workflow outcomes and duplicate operations.
- Comparison of `none`, `retry`, and `state_aware` recovery policies.
- Structured event traces, repeated experiment runs, JSON/JSONL outputs, and SQLite persistence.
- A FastAPI interface, command-line interface, automated tests, Docker configuration, and GitHub Actions workflow.

**Engineering question:** When a tool operation may have succeeded even though its response failed, how should an agent inspect state and recover without repeating an unsafe action?

**Status and scope:** This is an initial working implementation and research prototype using a small deterministic simulator. Its results demonstrate behavior under the defined scenarios; they do not establish production-wide reliability or universal LLM behavior.

**Stack:** Python · FastAPI · Pydantic · SQLite · pytest · Docker · GitHub Actions

[Repository](https://github.com/faraz-369/agentfault-lab) · [Implementation and benchmark methodology](https://github.com/faraz-369/agentfault-lab/tree/main/docs)

### 2. [AdvancedLeadsGeneration-AI](https://github.com/faraz-369/AdvancedLeadsGeneration-AI)

**Multi-agent lead qualification · IBM Granite Generative AI Hackathon winner (Team PolyEns)**

A multi-agent application that evaluates sales leads from different perspectives, surfaces potential risks, and combines findings into a structured assessment informed by historical deal context.

**What it demonstrates**

- Backend API development.
- Multi-agent orchestration and separation of responsibilities.
- Structured evaluation across competing perspectives.
- Integration between AI workflows and a web application.

**Stack:** Next.js · FastAPI · IBM Watson AI · IBM Granite

[Source code](https://github.com/faraz-369/AdvancedLeadsGeneration-AI) · [Hackathon project](https://lablab.ai/ai-hackathons/generative-ai-hackathon-with-ibm-granite/polyens)

### 3. [ComplianceRAG](https://github.com/faraz-369/ComplianceRAG)

**Grounded question answering with retrieval and answer critique**

A RAG application exploring how generated answers can be checked against retrieved source material. The workflow combines document ingestion, semantic retrieval, answer generation, and a groundedness critique step to identify statements that may not be adequately supported by the available evidence.

**What it demonstrates**

- Document ingestion and semantic retrieval.
- Embeddings and vector search.
- LLM-based answer generation.
- Sentence-level groundedness critique and citation validation.

**Stack:** Python · Gradio · FAISS · sentence-transformers · Hugging Face Inference API · PyPDF

[Live demo](https://huggingface.co/spaces/Faraz618/ComplianceRAG) · [Source code](https://github.com/faraz-369/ComplianceRAG)

### 4. [HireMind-AI](https://github.com/faraz-369/HireMind-AI)

**LLM-powered career workflow assistant**

An interactive application that brings several career-preparation workflows into one interface, including job-description analysis, skill-gap identification, resume assistance, cover-letter drafting, interview preparation, and career-related chat.

**What it demonstrates**

- LLM integration in a user-facing application.
- Multi-step workflows and structured outputs.
- Application state management and rapid prototyping.

**Stack:** Python · Streamlit · Groq API · Llama 3.1 · Hugging Face Spaces

[Live demo](https://huggingface.co/spaces/Faraz618/HireMind-AI) · [Source code](https://github.com/faraz-369/HireMind-AI)

### Additional project

**[SafeLite](https://github.com/faraz-369/SafeLite)** — A modular research-oriented project exploring planning, safety reasoning, execution, simulation, and evaluation in software workflows.

---

## Professional Experience

### MUSTER — Founding AI Engineer
*January 2026 – Present · Doha, Qatar*

Working on an AI account-management product for marketing agencies, beginning with automated client reporting and expanding toward client intelligence and agency workflow automation. The venture has been selected for the Qatar Science & Technology Park (QSTP) startup ecosystem.

### 1337 Ventures — Founding Engineer, MVP Development
*June 2025 – September 2025 · Kuala Lumpur, Malaysia*

- Designed the architecture for an AI automation SaaS MVP covering document ingestion, LLM routing, and structured output generation.
- Implemented backend functionality using Python and FastAPI.
- Contributed to delivery of a functional MVP within a six-week accelerator sprint.
- Participated in customer-discovery interviews and presented the product at Demo Day.

### NIC Faisalabad — AI / Data Engineer
*January 2024 – August 2024*

- Built Python ETL pipelines using Pandas, SQLAlchemy, and PostgreSQL for performance reporting across 30+ startup portfolio companies.
- Automated KPI reporting covering cohort, retention, and funding metrics.
- Implemented data-quality checks and reproducible reporting using Jupyter and Papermill.
- Reduced manual analyst time by approximately 60% and eliminated around 12 hours per week of manual spreadsheet work.

### Stanford University — Code in Place Section Leader
*January 2026 – May 2026*

- Selected as a Section Leader for Stanford's Code in Place program.
- Taught Python programming through weekly live sessions.
- Guided learners through programming fundamentals, debugging, and problem-solving.
- Facilitated discussions and provided feedback on assignments.

---

## Recognition & Community

- **IBM Granite Generative AI Hackathon — Winner**, Team PolyEns.
- **Harvard CS50x Puzzle Day 2025 — 1st Place**, reported score: 9/9.
- **Stanford Code in Place — Section Leader**, 2025 and 2026.
- **Qubic Hack the Future Hackathon — Winner.**
- **RAISE YOUR HACK Hackathon — Winner.**
- **BICON Startup Incubation — Selected** for final-year project.
- **Founder Institute Pakistan — Accepted**, Cohort 2025.
- **AlgoVerse Research Program — Accepted** with a reported 45% merit scholarship.
- Participated in **17 international hackathons with 14 submissions**, as listed on my [LabLab profile](https://lablab.ai/u/@Faraz_Mubeen).

## Research & Publications

- *AI-Based Multi-Class Classification of Anterior Segment Eye Diseases Using MobileNetV2.*
- *A Lightweight LLM Agent for Verifiable Language-Conditioned Manipulation.*

## How I Approach Engineering

- **Start with the problem.** Understand the user need and system constraints before choosing a framework or model.
- **Make behavior observable.** Use structured records, clear error handling, and testable outcomes to understand what a system actually did.
- **Test failure paths.** A successful happy-path demo is not enough; retries, malformed responses, partial failures, and unexpected state matter.
- **Evaluate AI outputs.** Retrieval quality, evidence, structured validation, and failure analysis are part of building useful AI applications.
- **Be precise about evidence.** Distinguish measured results from assumptions, simulations, and areas that still need validation.

## Connect

I'm interested in full-time software engineering opportunities involving **Python backend development, APIs, data-backed applications, and applied AI systems**. I'm based in Pakistan and open to relocating to Germany for a suitable engineering role.

- **Email:** [faraz.outreach8@gmail.com](mailto:faraz.outreach8@gmail.com)
- **LinkedIn:** [linkedin.com/in/faraz369](https://www.linkedin.com/in/faraz369)
- **GitHub:** [github.com/faraz-369](https://github.com/faraz-369)
- **Hugging Face:** [huggingface.co/Faraz618](https://huggingface.co/Faraz618)
- **LabLab:** [lablab.ai/u/@Faraz_Mubeen](https://lablab.ai/u/@Faraz_Mubeen)

---

<div align="center">

*Build thoughtfully. Test the failure paths. Improve with evidence.*

</div>
