<!--
  ┌─────────────────────────────────────────────────────────────────────┐
  │  THIS IS YOUR GITHUB PROFILE README (draft).                          │
  │  To make it show on your profile, this file must live in a PUBLIC     │
  │  repo named EXACTLY after your username:  sinhasagar507/sinhasagar507 │
  │  GitHub renders the README of that special repo at github.com/        │
  │  sinhasagar507. See the notes at the bottom for the publish steps.    │
  └─────────────────────────────────────────────────────────────────────┘
-->

<h1 align="center">Hi, I'm Sagar Sinha 👋</h1>

<p align="center">
  <b>RAG &amp; LLM | Data Scientist | Data Analyst</b><br/>
  MS Computer Science @ Arizona State University (May 2026)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sagarsinha2000/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:sinhasagar507@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://sinhasagar507.github.io">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=sinhasagar507&style=for-the-badge&label=PROFILE+VIEWS&color=0e75b6" alt="Profile views"/>
</p>

---

## About Me

I build AI systems that turn messy, real-world documents and data into something people can actually use — from offline RAG assistants for 100+ page mortgage packs to LLM-assisted learning tools and production data pipelines.

- 🤖 Focused on **RAG pipelines, LLMs, agentic AI, and applied NLP**
- 🔬 Currently benchmarking **diffusion LLMs vs. autoregressive models** (LLaDA-8B vs. Llama-3-8B)
- 🛠️ Comfortable across the stack: **Python · PyTorch · FastAPI · dbt/Airflow · React/Go**
- 📍 Based in Tempe, Arizona — open to AI/ML & Data roles
- ⚡ Outside of code: building side projects and learning in public

---

## Featured Projects

### 🧠 Reasoning Capabilities in Diffusion LLMs
Compute-parity benchmarking of a discrete diffusion LLM (**LLaDA-8B**) against **Llama-3-8B** on GSM8K, LogiQA, GPQA, and AIME 2025 — including eval harnesses, **SFT LoRA** fine-tuning, and diffusion step-budget sweeps.
<br/>**Stack:** Python · PyTorch · LoRA/PEFT · HuggingFace · LLM Evaluation
<br/>🔗 [Repo](https://github.com/sinhasagar507/Reasoning-Capabilities-in-Diffusion-LLMs)

### 📄 Outamation — Mortgage Document RAG Bot
Offline, document-aware RAG pipeline that turns 100+ page mortgage loan packs into a **cited, chat-style Q&A assistant**. Hybrid retrieval (dense MiniLM + BM25 + cross-encoder reranker) over OCR'd PDFs, served with a local **Mistral-7B**.
<br/>**Results:** Recall@5 **100%** · MRR **1.00** · ~**1.9s** avg latency · 0% error rate
<br/>**Stack:** Python · PyMuPDF/PaddleOCR · Sentence-Transformers · BM25 · Mistral-7B · Gradio
<br/>🔗 [Repo](https://github.com/sinhasagar507/outamation-mortgageRAGBot)

### 🎓 Socrates — LLM-Assisted Learning Platform
A complete chat-based interface for LLM-assisted learning. RAG over your own course material with a **Flask** backend, **React** frontend, local **Ollama (llama3.2)** inference, FAISS retrieval, and live **GPU monitoring**.
<br/>**Stack:** Python · Flask · React · FAISS · Ollama · Docker
<br/>🔗 [Repo](https://github.com/sinhasagar507/Socrates)

### 🚕 NYC Taxi Duration Predictor
End-to-end data engineering platform forecasting NYC taxi trip durations. Airflow-orchestrated ingestion to GCS → BigQuery external tables → **dbt** ELT (staging + marts) → **PySpark** ML model, with a Looker Studio dashboard and GitHub Actions CI.
<br/>**Stack:** dbt · BigQuery · Airflow · PySpark · GCP · Looker Studio
<br/>🔗 [Repo](https://github.com/sinhasagar507/nyc-taxi-duration-predictor)

### 🏦 Distributed Banking System
A scalable electronic banking system with a RESTful API for authentication, transactions, and account operations.
<br/>**Stack:** Go · MongoDB · Docker · REST
<br/>🔗 [Repo](https://github.com/sinhasagar507/distributed-banking-system)

### 🏠 Rental Platform
Full-stack rental property platform — tenant browsing, visit scheduling, lease management, and an admin dashboard.
<br/>**Stack:** React · Node.js · MongoDB
<br/>🔗 [Repo](https://github.com/sinhasagar507/rental-platform)

> 📊 More work: [Analytics Case Studies](https://github.com/sinhasagar507/analytics-case-studies) · [CryptoGuard — GNN Fraud Detection](https://github.com/sinhasagar507/cryptoguard) · [People Pulse — HR Tableau Dashboard](https://github.com/sinhasagar507/people-pulse)

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
<br/>
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sinhasagar507&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sinhasagar507&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sinhasagar507&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

---

<p align="center"><i>Always happy to talk RAG, LLM evaluation, and data systems — reach out on LinkedIn.</i></p>

<!--
  ─────────────────────────── HOW TO PUBLISH ───────────────────────────
  1. Create a NEW public repo on GitHub named exactly: sinhasagar507
     (github.com/new → Repository name: sinhasagar507 → Public → Create)
  2. Add this README.md to that repo's root and push:
        git init
        git add README.md
        git commit -m "Add profile README"
        git branch -M main
        git remote add origin https://github.com/sinhasagar507/sinhasagar507.git
        git push -u origin main
  3. Visit github.com/sinhasagar507 — the README now renders on your profile.

  THINGS TO FILL / VERIFY:
  - Confirm the headline ("AI / ML Engineer") matches the roles you target.
  - The streak-stats widget uses a third-party host that is sometimes down;
    remove that block if it doesn't render.
  - Stats cards count only PUBLIC repos unless you add count_private (already on).
  - Add a graduation month to the ASU line if you want it (e.g. "(May 2026)").
  ───────────────────────────────────────────────────────────────────────
-->
