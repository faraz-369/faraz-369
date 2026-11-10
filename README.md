<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="1200" height="300" role="img" aria-labelledby="t d">
  <title id="t">Faraz Mubeen Haider — Software Engineer</title>
  <desc id="d">Software Engineer specialising in Backend and Distributed Systems, on a midnight navy background with a network-node motif.</desc>
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#061329"/>
      <stop offset="0.6" stop-color="#0B2450"/>
      <stop offset="1" stop-color="#087FE5"/>
    </linearGradient>
    <linearGradient id="accent" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#20B9F5"/>
      <stop offset="1" stop-color="#087FE5"/>
    </linearGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#F4F7FC" stroke-opacity="0.05" stroke-width="1"/>
    </pattern>
    <radialGradient id="glow" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0" stop-color="#20B9F5" stop-opacity="0.35"/>
      <stop offset="1" stop-color="#20B9F5" stop-opacity="0"/>
    </radialGradient>
  </defs>

  <rect width="1200" height="300" fill="url(#bg)"/>
  <rect width="1200" height="300" fill="url(#grid)"/>
  <circle cx="930" cy="150" r="190" fill="url(#glow)"/>

  <!-- Service-topology motif -->
  <g stroke="#20B9F5" stroke-opacity="0.55" stroke-width="1.5" fill="none">
    <path d="M 800 90 L 900 150 L 800 210"/>
    <path d="M 900 150 L 1010 80"/>
    <path d="M 900 150 L 1010 150"/>
    <path d="M 900 150 L 1010 220"/>
    <path d="M 1010 80 L 1110 120"/>
    <path d="M 1010 150 L 1110 120"/>
    <path d="M 1010 150 L 1110 190"/>
    <path d="M 1010 220 L 1110 190"/>
    <path d="M 800 90 L 800 210" stroke-dasharray="4 6"/>
  </g>
  <g fill="#061329" stroke="#20B9F5" stroke-width="2">
    <circle cx="800" cy="90" r="8"/>
    <circle cx="800" cy="210" r="8"/>
    <circle cx="1010" cy="80" r="8"/>
    <circle cx="1010" cy="150" r="8"/>
    <circle cx="1010" cy="220" r="8"/>
    <circle cx="1110" cy="120" r="8"/>
    <circle cx="1110" cy="190" r="8"/>
  </g>
  <circle cx="900" cy="150" r="14" fill="#20B9F5"/>
  <circle cx="900" cy="150" r="5" fill="#061329"/>

  <!-- Text -->
  <rect x="70" y="78" width="56" height="4" rx="2" fill="url(#accent)"/>
  <text x="70" y="150" fill="#F4F7FC" font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="56" font-weight="700" letter-spacing="-1">Faraz Mubeen Haider</text>
  <text x="72" y="196" fill="#20B9F5" font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="26" font-weight="600" letter-spacing="0.5">Software Engineer</text>
  <text x="72" y="232" fill="#F4F7FC" fill-opacity="0.8" font-family="'Segoe UI', 'Helvetica Neue', Arial, sans-serif" font-size="20" letter-spacing="1.5">BACKEND &amp; DISTRIBUTED SYSTEMS</text>
</svg>

<img width="1200" height="300" alt="github-profile-banner" src="https://github.com/user-attachments/assets/4138f3bd-8377-4ecb-8881-50a746b96b6c" />

<br/>

[Email](mailto:faraz.outreach8@gmail.com) · [LinkedIn](https://www.linkedin.com/in/faraz369) · [Portfolio](https://faraz369.vercel.app/) · [Hugging Face](https://huggingface.co/Faraz618)

</div>

<br/>

## About

I'm a Software Engineer who builds backend services in Python and FastAPI: REST APIs, relational data models and data-intensive applications. I care most about data integrity, testing, and how software behaves when its dependencies fail.

I'm early in my career. My work so far includes startup product engineering, a six-week backend sprint on a SaaS MVP, data-pipeline automation, and teaching Python as a Stanford Code in Place Section Leader. I'm now deepening my skills in database design, asynchronous processing and reliability engineering.

**Location:** Pakistan · **Open to:** software engineering roles, remote or international

---

## Selected Projects

### AgentFault Lab — failure injection and recovery-policy evaluation

`Python` `FastAPI` `Pydantic` `SQLite` `Docker` `GitHub Actions` `Next.js`

A prototype harness for reproducing failures in multi-step agent workflows and comparing recovery policies against explicit invariants.

- **Backend:** modular Python package with FastAPI endpoints and a CLI; Pydantic-validated requests and records; SQLite persistence plus structured JSON/JSONL run records.
- **Failure handling:** controlled injection of timeouts, exceptions and malformed responses; retry and state-aware recovery policies compared side by side.
- **Quality:** unit, API, integration and regression tests; Docker Compose setup; CI via GitHub Actions.
- **Evaluation:** a documented 45-run baseline (3 scenarios × 3 recovery policies) using deterministic simulated tools. The results describe this controlled harness only, not production AI-agent reliability.

**Status:** working prototype.
[Repository](https://github.com/faraz-369/agentfault-lab-Web) · [Live interface](https://agentfault-lab-web.vercel.app/) · [Benchmark methodology](https://github.com/faraz-369/agentfault-lab-Web/blob/main/docs/benchmark-methodology.md) · [Results](https://github.com/faraz-369/agentfault-lab-Web/tree/main/results)

### ComplianceRAG — cited answers over compliance documents

`Python` `FAISS` `Sentence Transformers` `Gradio`

A retrieval-augmented question-answering application: document ingestion and chunking, embedding-based retrieval with FAISS, and answers returned with cited sources and confidence scores.

**Status:** experimental prototype, hosted as a Hugging Face Space.
[Repository](https://github.com/faraz-369/ComplianceRAG) · [Demo](https://huggingface.co/spaces/Faraz618/ComplianceRAG)

<details>
<summary>More projects</summary>

<br/>

**HireMind-AI** — Streamlit prototype using the Groq API for job-description analysis, resume feedback and interview preparation; JSON-file storage. [Repository](https://github.com/faraz-369/HireMind-AI)

**SafeLite** — research prototype on language-conditioned robotic manipulation with LLM agents in simulation (Meta-World / MuJoCo). [Repository](https://github.com/faraz-369/SafeLite)

</details>

---

## Experience

**MUSTER — Founder, Product & Engineering** · early-stage venture
Product direction, technical planning and backend-oriented development of an MVP: application structure, data workflows and integrations.

**NIC Faisalabad — AI / Data Engineering Intern**
Built Python data-processing and reporting workflows (Pandas, SQLAlchemy, PostgreSQL) supporting KPI analysis across 30+ portfolio companies, including validation checks and automated recurring reports. *Reported outcome:* roughly 60% less manual analyst effort, about 12 hours saved per week (self-reported, not independently measured).

**1337 Ventures — Backend Contributor** · six-week accelerator sprint, early-stage SaaS MVP
Implemented assigned backend functionality in Python/FastAPI, including document-ingestion and structured-output workflows, as part of a small team.

**Stanford University — Code in Place Section Leader** · 2025, 2026
Led weekly live sections teaching Python fundamentals, guiding learners through debugging and problem-solving.

---

## Technical Stack

| Area | Tools |
|---|---|
| Languages | Python, SQL |
| Backend | FastAPI, REST APIs, Pydantic |
| Data | PostgreSQL, SQLite, SQLAlchemy, Pandas |
| Quality | Pytest, HTTPX, Hypothesis, Ruff |
| Delivery | Docker, Docker Compose, GitHub Actions |
| AI integration | Groq API, Hugging Face, FAISS, Sentence Transformers |
| Interfaces | Next.js, Streamlit, Gradio |

Listed by use in the projects and roles above; depth varies by tool.

---

## Recognition

- **IBM Granite Generative AI Hackathon** — winning team (PolyEns)
- **BICON-NUML accelerator** — final-year project BillBachao selected for the cohort
- **AlgoVerse Research Program (EOE.ai × Omdena)** — accepted participant
- **Harvard CS50x Puzzle Day 2025** — 9/9
- Also active on [LabLab](https://lablab.ai/u/@Faraz_Mubeen) and listed on [Rankistan](https://rankistan.dev/#faraz-369)

---

## Education

**BS Software Engineering** — National University of Modern Languages (NUML), 2022–2026

---

## Currently Strengthening

Database transactions and schema design · authentication and authorisation · asynchronous processing · logging and observability · distributed-systems fundamentals
