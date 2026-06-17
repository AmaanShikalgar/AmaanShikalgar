<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,16&height=150&section=header" width="100%"/>

<h1>Amaan Shikalgar</h1>
<h3>Backend & Full Stack Developer</h3>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=8B5CF6&center=true&vCenter=true&width=600&lines=Backend+%26+Full+Stack+Developer;REST+API+%7C+RAG+%7C+Auth+Systems;Node.js+%7C+FastAPI+%7C+Python+%7C+React;Building+scalable+backend+systems" alt="Typing SVG" /></a>

<br/><br/>

![Location](https://img.shields.io/badge/📍_Pune,_India-6d28d9?style=for-the-badge&logoColor=white)
![Open To Work](https://img.shields.io/badge/Open%20To%20Work-10b981?style=for-the-badge&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-6d28d9?style=for-the-badge&logo=vercel&logoColor=white)](https://matrix-portfolio-lovat.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amaan-shikalgar/)
[![Email](https://img.shields.io/badge/Email-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amaanshikalgar2003@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AmaanShikalgar)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=AmaanShikalgar&color=6d28d9&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/AmaanShikalgar?style=for-the-badge&color=6d28d9&label=FOLLOWERS)

</div>

---

## 🧑‍💻 About Me

```yaml
name        : Amaan Shikalgar
role        : Backend & Full Stack Developer
location    : Pune, Maharashtra, India
education   : B.E. Computer Engineering — Dr. D.Y. Patil IEMR (2021–2025)
experience  : Software Engineer Intern @ Sayu Softtech (Feb–May 2024)
```

Backend-focused developer with hands-on experience building production-ready REST APIs, authentication systems, and scalable web applications. Skilled across the full stack — from designing PostgreSQL schemas and MongoDB data models to shipping React frontends. Recently expanded into applied AI, building RAG pipelines with FAISS and LLM integration from scratch.

I care about systems that are reliable, well-structured, and actually deployed — not just running locally.

**Open To:** Backend Engineer · Full Stack Developer · API Developer · Junior Software Engineer

---

## 🛠 Tech Stack

<div align="center">

### Languages
[![My Skills](https://skillicons.dev/icons?i=python,js,cpp,typescript&theme=dark)](https://skillicons.dev)

### Frontend
[![My Skills](https://skillicons.dev/icons?i=react,html,css&theme=dark)](https://skillicons.dev)

### Backend & Databases
[![My Skills](https://skillicons.dev/icons?i=nodejs,express,fastapi,django,mongodb,postgresql,mysql&theme=dark)](https://skillicons.dev)

### Cloud, DevOps & Tooling
[![My Skills](https://skillicons.dev/icons?i=git,github,docker,linux,postman,vercel&theme=dark)](https://skillicons.dev)

</div>

---

## 🤖 AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|--------|-------------|---------|
| Retrieval-Augmented Generation (RAG) | ⭐⭐⭐⭐ | FAISS vector indexing, semantic chunking, retrieval-grounded prompting |
| Vector Search | ⭐⭐⭐⭐ | FAISS nearest-neighbour retrieval, embedding generation |
| LLM Integration | ⭐⭐⭐⭐ | Groq API, LLaMA 3, prompt engineering for factual grounding |
| Sentence Transformers | ⭐⭐⭐ | Semantic embeddings, similarity search |
| AI System Design | ⭐⭐⭐⭐ | End-to-end pipeline design, hallucination reduction |

</div>

---

## 🚀 Featured Projects

<details>
<summary><b>DocuMind AI — RAG-based Document Q&A System</b></summary>

<br/>

Semantic document intelligence system that enables natural language querying across large PDF documents with page-level citations. Built on a full RAG pipeline engineered from scratch.

| Attribute | Details |
|-----------|---------|
| **Stack** | Python, FAISS, Sentence Transformers, LLaMA 3, Groq API, Streamlit |
| **Scale** | 50+ page documents, thousands of vector chunks |
| **Performance** | Millisecond vector retrieval via FAISS nearest-neighbour search |
| **Security** | Environment-based API key management, no data persistence |
| **Impact** | Zero hallucination design — system refuses to answer if context is absent |
| **Repository** | [GitHub](https://github.com/AmaanShikalgar/rag-pdf-chatbot) · [Live](https://rag-pdf-chatbot-amaan.streamlit.app/) |

**Pipeline:** PDF → Text Extraction → Chunking → Sentence Embeddings → FAISS Index → Query Embedding → Top-K Retrieval → LLaMA 3 → Grounded Answer + Page Citations

The retrieval-grounded prompting architecture ensures the LLM operates exclusively on retrieved document context, eliminating hallucination at the source rather than filtering it downstream.

</details>

<details>
<summary><b>StockFlow — Full Stack Inventory Management System</b></summary>

<br/>

Production-grade inventory management platform with a FastAPI backend, React frontend, and PostgreSQL persistence. Features JWT authentication, optimized query performance, and full cloud deployment.

| Attribute | Details |
|-----------|---------|
| **Stack** | FastAPI, PostgreSQL, React, JWT, Render, Neon, Vercel |
| **Scale** | 10+ REST API endpoints, multi-user role support |
| **Performance** | Query optimization reduced API latency from 320ms → 230ms |
| **Security** | JWT-based authentication, environment-based secrets |
| **Impact** | End-to-end full stack deployment across three cloud platforms |
| **Repository** | [GitHub](https://github.com/AmaanShikalgar/StockFlow) · [Live](https://stock-flow-api.vercel.app) |

Architected with a clean separation between the API layer and data layer. Database query profiling was used to identify and eliminate N+1 patterns, yielding a measurable 28% reduction in average response latency.

</details>

<details>
<summary><b>DevScan API — GitHub Profile Intelligence API</b></summary>

<br/>

REST API backend that fetches, analyzes, and persists public GitHub profile data using the GitHub REST API. Features intelligent UPSERT logic and authenticated rate limit scaling.

| Attribute | Details |
|-----------|---------|
| **Stack** | Node.js, Express.js, MySQL, Railway |
| **Scale** | 3 REST endpoints, persistent profile storage |
| **Performance** | Rate limit scaled from 60 → 5000 req/hr via GitHub token auth |
| **Security** | Environment-based config, GitHub token management |
| **Impact** | UPSERT logic prevents duplicates and supports re-analysis workflows |
| **Repository** | [GitHub](https://github.com/AmaanShikalgar/github-profile-analyzer-api) · [Live](https://github-profile-analyzer-api-9622.up.railway.app) |

Designed around idempotent data operations — repeated analysis of the same profile updates existing records rather than creating duplicates, making it safe for scheduled or event-driven execution.

</details>

<details>
<summary><b>CourseHub LMS — Backend API for Course Platform</b></summary>

<br/>

Secure backend REST API for a course-selling platform with multi-role authentication, MongoDB data modeling, and protected route architecture.

| Attribute | Details |
|-----------|---------|
| **Stack** | Node.js, Express.js, MongoDB, Mongoose, JWT |
| **Scale** | 10+ REST endpoints across user, admin, and course routes |
| **Performance** | Mongoose schema optimization for efficient document queries |
| **Security** | Role-based JWT with separate token secrets per role |
| **Impact** | Custom middleware architecture cleanly separates auth from business logic |
| **Repository** | [GitHub](https://github.com/AmaanShikalgar/Course-Selling-App) |

Implemented dual-secret JWT architecture — user and admin tokens are signed with independent secrets, meaning a compromised user token cannot be escalated to admin access under any circumstance.

</details>

---

## 💼 Experience

### Software Engineer Intern — Sayu Softtech (OPC) Pvt. Ltd.
**Feb 2024 – May 2024 · Ahmednagar, Maharashtra, India**

Contributed across the full software development lifecycle at a software product company, working directly with senior engineers on real application codebases.

- Participated in application development, testing, debugging, and technical documentation across the SDLC
- Translated user requirements into technical solutions, collaborating with senior engineers to investigate and resolve software issues hands-on
- Gained practical exposure to professional software engineering workflows, version control practices, and team-based development

![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![SDLC](https://img.shields.io/badge/SDLC-6d28d9?style=flat-square&logoColor=white)
![Debugging](https://img.shields.io/badge/Debugging-7c3aed?style=flat-square&logoColor=white)
![Documentation](https://img.shields.io/badge/Documentation-4f46e5?style=flat-square&logoColor=white)

---

## 🏆 Achievements

<div align="center">

| Recognition | Details |
|-------------|---------|
| 🥇 President, Coders Club | Led 50+ member technical community, organized coding events and workshops |
| 🏅 Smart India Hackathon | Selected among Top 15 teams out of 100+ participating teams |
| 🌐 GDG Cloud Pune | Active contributor to Google Developer Group Cloud Pune chapter |
| 🎓 GDG On Campus WOW | Core member of GDG On Campus technical event organization team |

</div>

---

## 🎯 Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-ffa116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/AmaanShikalgar/)
[![HackerRank](https://img.shields.io/badge/HackerRank-00ea64?style=for-the-badge&logo=hackerrank&logoColor=black)](https://www.hackerrank.com/profile/amaanshikalgar21)

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AmaanShikalgar&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d0d1a&title_color=8b5cf6&icon_color=7c3aed&text_color=c4b5fd" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=AmaanShikalgar&theme=tokyonight&hide_border=true&background=0d0d1a&ring=8b5cf6&fire=7c3aed&currStreakLabel=c4b5fd" width="49%"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AmaanShikalgar&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d0d1a&title_color=8b5cf6&text_color=c4b5fd" width="40%"/>

</div>

---

## 🏅 GitHub Stats Summary

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AmaanShikalgar&theme=tokyonight" width="100%"/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=AmaanShikalgar&theme=tokyonight" width="32%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=AmaanShikalgar&theme=tokyonight" width="32%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=AmaanShikalgar&theme=tokyonight" width="32%"/>

</div>

---

## 📈 Contribution Activity

<div align="center">

[![Amaan's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=AmaanShikalgar&theme=tokyo-night&hide_border=true&bg_color=0d0d1a&color=8b5cf6&line=7c3aed&point=c4b5fd)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🐍 Contribution Snake

<div align="center">

![Snake animation](https://github.com/AmaanShikalgar/AmaanShikalgar/blob/output/github-contribution-grid-snake-dark.svg)

</div>

---

## 🎯 Current Focus

```yaml
learning:
  - Advanced system design patterns
  - Distributed systems fundamentals
  - AI/ML pipeline engineering

building:
  - Job discovery automation with AI scoring
  - Open source backend tooling

exploring:
  - Vector databases beyond FAISS
  - LLM fine-tuning vs RAG tradeoffs
  - Event-driven architecture with message queues

open_to:
  - Backend Engineer roles
  - Full Stack Developer positions
  - Startup engineering teams
  - Remote opportunities
```

---

## 🤝 Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amaanshikalgar2003@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amaan-shikalgar/)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AmaanShikalgar)
[![Portfolio](https://img.shields.io/badge/Portfolio-6d28d9?style=for-the-badge&logo=vercel&logoColor=white)](https://matrix-portfolio-lovat.vercel.app/)

</div>

---

<div align="center">

*"Good systems are built twice — once in planning, once in code."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,16&height=120&section=footer" width="100%"/>

</div>
