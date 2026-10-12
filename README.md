# 👋 Muhammad Hasnat | ML Engineer · LLMs, RAG & Evaluation

[![Profile Views](https://komarev.com/ghpvc/?username=hasnat23&label=Profile%20views&color=4f46e5&style=flat)](https://github.com/hasnat23)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Muhammad%20Hasnat-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/hasnat23/)
[![Email](https://img.shields.io/badge/Email-chmuhammadhasnat23%40gmail.com-red?style=flat&logo=gmail)](mailto:chmuhammadhasnat23@gmail.com)

## 🚀 About Me

I build **LLM systems that can be trusted**: retrieval pipelines that correct themselves, agents that fact-check their own output,
and evaluation tools that tell you *which sentence* is hallucinated.

I did my **MSc at the University of Koblenz**, where my thesis benchmarked holistic vs. sentence-level **RLAIF for factual summarization**
(reward modelling with granular credit assignment). Before ML, I was a **full-stack JavaScript developer** (React, Vue, Angular),
so my projects usually ship with a real UI and API, not just a notebook.

### 💡 Core Expertise
- **LLM Evaluation & Factuality**: hallucination detection, NLI-based consistency checking, LLM-as-judge, reward models (RLAIF)
- **RAG & Agentic AI**: LangGraph agents, Corrective RAG / Self-RAG, multi-agent workflows, MCP servers
- **Machine Learning**: PyTorch, Hugging Face Transformers, LightGBM, time-series forecasting, conformal prediction
- **Engineering**: FastAPI, streaming APIs (SSE), Docker, CI/CD, React + TypeScript frontends

---

## 🏆 Featured Projects

### 🔎 [factlens](https://github.com/hasnat23/factlens)
**Sentence-level hallucination detection** for LLM summaries and RAG answers. Each sentence is checked against the source with an NLI model,
labelled *supported / unverified / contradicted*, and aggregated into one score. Comes with a benchmark on human-annotated RAGTruth data and a [live in-browser demo on Hugging Face](https://huggingface.co/spaces/chhasnat23/factlens).

### 🔁 [reflective-rag](https://github.com/hasnat23/reflective-rag)
**Corrective RAG (CRAG) and Self-RAG**, re-implemented with LangGraph from the papers, plus an evaluation harness on HotpotQA with a
*knowledge-gap* setting that tests whether a pipeline can recover when retrieval fails. Runs locally with Ollama.

### 🔭 [paper-scout-mcp](https://github.com/hasnat23/paper-scout-mcp)
**MCP server** that gives Claude Code, Cursor and other agents a research assistant: search arXiv, read papers section by section,
follow citation graphs (Semantic Scholar), and keep a tagged library with BibTeX export. No API keys needed.

### 🧭 [jobpilot](https://github.com/hasnat23/jobpilot)
**Multi-agent job application assistant** (LangGraph + FastAPI + React). Five agents match a CV to a job posting, tailor CV bullets and draft a
cover letter in parallel. A fact-checker, backed by deterministic evidence checks, catches invented claims before you see them.

### More projects

| Project | What it is |
|---|---|
| 💸 [llm-costwatch](https://github.com/hasnat23/llm-costwatch) | Zero-dependency Python library: token & cost tracking across OpenAI, Anthropic, Gemini, Ollama and LangChain, with budgets and per-feature tags |
| ⚡ [grid-load-forecast](https://github.com/hasnat23/grid-load-forecast) | Day-ahead electricity demand forecasting for Germany (LightGBM + Optuna + conformal intervals), benchmarked against the official ENTSO-E forecast |

---

## 📊 GitHub Activity

![GitHub Streak](https://github-readme-streak-stats-eight.vercel.app?user=hasnat23&theme=dark&hide_border=true)

![Commit Activity](https://github-readme-activity-graph.vercel.app/graph?username=hasnat23&theme=react-dark&hide_border=true&area=true)

---

## 🛠️ Technical Stack

### AI/ML
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### LLMs & Agents
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-8A2BE2?style=for-the-badge&logoColor=white)

### Backend & DevOps
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Frontend (Full-Stack)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

---

## 🤝 Let's Connect

I'm interested in roles around **LLM applications, RAG, and evaluation / AI safety tooling**. If you're building in that space, let's talk!

**💼 LinkedIn**: [Muhammad Hasnat](https://www.linkedin.com/in/hasnat23/)  
**📧 Email**: [chmuhammadhasnat23@gmail.com](mailto:chmuhammadhasnat23@gmail.com)

---

*💡 Open to opportunities as an ML / LLM Engineer*
