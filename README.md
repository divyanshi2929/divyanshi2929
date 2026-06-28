<h1 align="center">Hi 👋, I'm Divyanshi Namdev</h1>
<h3 align="center">AI/ML Engineer Intern · CS Student · Building production-grade LLM & RAG systems</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/divyanshi-namdev" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/divyanshi2929" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

## 💫 About Me

I'm an **AI/ML Engineer Intern** currently building production features on a 10+ service enterprise RAG platform — shipping LLM rate limiting, multi-format document extraction, and image-processing pipelines in a live codebase used by real users.

- 🎓 B.Tech – Computer Science @ **Medicaps University, Indore** (Expected Jul 2026) | **8.5 CGPA**
- 🔭 Currently working at **NimbusNext AITech India** on a microservices RAG platform
- 🌱 Strong in **Python, FastAPI, RAG, vector search, LLMs, Celery, pgvector, and Azure Blob Storage**
- ⚡ I own features end-to-end — from design to tested, deployed code

---

## 🛠️ Tech Stack

**Languages:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

**Backend:**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Databases:**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

**DevOps & Tools:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Azure](https://img.shields.io/badge/Azure_Blob_Storage-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**AI/ML:**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)

---

## 💼 Professional Experience

### 🏢 NimbusNext AITech India Private Limited — *AI/ML Engineer Intern*
**Jan 2026 – Present**

- Contributed to a production-grade microservices RAG platform (**yavi.rag.vector**) spanning 10+ services: document extraction, vector ingestion, RAG retrieval, content generation, and unified agent.
- Refactored the image placeholder system to an **embedded-URI architecture**, improving image fidelity across 3 file formats (PDF, DOCX, PPTX) in Markdown and HTML output; deployed via feature flags for zero-downtime rollout.
- Designed and shipped **image-handling support** for the document extraction pipeline, enabling consistent image rendering across PDF, DOCX, and HTML outputs stored in Azure Blob Storage — unblocking multi-format document export for end users.
- **Parallelized PDF chunk extraction** using Celery and Redis, processing documents in 20-page chunks across 4 concurrent workers via Docling — significantly reducing extraction time for large documents; wrote and maintained unit tests covering extraction edge cases.
- Implemented **token-bucket rate limiting** for LLM and embedding API calls, preventing request rejection under load; added empty-retrieval warnings and structured logging across the RAG query pipeline to improve observability.

---

## 🚀 Featured Projects

### 🔹 [RAG Platform](https://github.com/divyanshi2929) | FastAPI, PostgreSQL/pgvector, SQLAlchemy, Hugging Face | *2025*
- Production-grade custom RAG from scratch (no LangChain): clean layered architecture, **hybrid retrieval** (semantic + lexical), reranking, and OpenTelemetry-ready observability.
- Full ingestion pipeline: chunking, embedding, pgvector storage; query pipeline with top-K hybrid retrieval, LLM answer generation, and structured JSON logging with request-correlation IDs.
- Domain/Application/Service/Infrastructure layering with zero framework leakage into business logic; served via FastAPI REST endpoints.

### 🔹 [AI Fake News Detection & Aggregator](https://github.com/divyanshi2929) | BERT, RoBERTa, Flask, PyTorch | *2025*
- NLP web app classifying news as real vs. fake using fine-tuned **BERT and RoBERTa** with confidence scoring and multi-model admin dashboard for benchmarking.
- Trained BERT locally, integrated Hugging Face RoBERTa; built news scraper (BeautifulSoup, Newspaper3k) with text preprocessing pipeline and secure admin auth.

### 🔹 [QuickTube AI – LLM YouTube Summarizer](https://github.com/divyanshi2929/QuickTube-AI) | Python, LangChain, LLMs, Streamlit | *Apr 2025*
- Multi-agent LLM app converting YouTube videos to structured summaries; **smart caching and token optimization reduced API cost and improved response speed by 40%**.
- Modular agent workflows separating transcript extraction, summarization, and formatting for easy extensibility.

### 🔹 [CareerPath – AI Career Recommendation System](https://github.com/divyanshi2929/CareerPath-project) | Python, ML, Flask, SQLite | *2024*
- ML web app predicting career paths from user skills; full ML lifecycle — preprocessing, model training (joblib), and Flask REST API serving live predictions.

---

## 🏅 Certifications & Training

| Certification | Issuer | Year |
|---|---|---|
| AI LLM Developer (AI & Data) — 240 hrs | HCLTech | Jan–May 2026 |
| Building with Claude API | Anthropic Academy | May 2026 |
| Claude Code in Action | Anthropic Academy | May 2026 |
| Introduction to Agent Skills | Anthropic Academy | May 2026 |
| Introduction to Model Context Protocol | Anthropic Academy | May 2026 |
| CCNA | Cisco | — |
| Python Essentials 2 | Cisco | — |
| OCI Generative AI Professional | Oracle | — |

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=divyanshi2929&show_icons=true&theme=dark&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=divyanshi2929&theme=dark&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=divyanshi2929&layout=compact&theme=dark&hide_border=true" alt="Top Languages" />
</p>

---

<p align="center">⭐ <em>From <a href="https://github.com/divyanshi2929">divyanshi2929</a> — Open to collaborations on LLM, RAG, and AI backend projects!</em></p>
