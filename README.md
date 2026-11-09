# Gaurav Yadav

**Final-Year B.Tech CSE ('27) — Software Engineer · Full-Stack AI & Agentic Systems · Applied ML**

[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-0A66C2?style=flat-square)](https://threed-portfolio-msx7.onrender.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gauravdev95-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/gauravdev95/)
[![LeetCode](https://img.shields.io/badge/LeetCode-gauravDevX_(864_Solved)-FFA116?style=flat-square&logo=leetcode)](https://leetcode.com/gauravDevX/)
[![Location](https://img.shields.io/badge/Location-Agra,_India-2ea44f?style=flat-square)]()

I build backend systems, full-stack AI applications, and applied machine learning pipelines using **Python (FastAPI, SQLAlchemy, Scikit-learn/XGBoost)** and **JavaScript/TypeScript (React, Node.js, Express)** backed by **PostgreSQL (`pgvector`)**.

---

### Featured Engineering Systems

| Project | Domain & Stack | Engineering Highlights & Verified Metrics | Links |
| :--- | :--- | :--- | :--- |
| **[Grafted](https://github.com/gauravdev95/AI-powered-career-intelligence-platform)**<br>*(WikiThon 2026 Top 10)* | **Full-Stack AI / RAG**<br>React, Node.js, Express, PostgreSQL (`pgvector`), Groq (`llama-3.3-70b`), Claude fallback | Career memory engine that ingests job descriptions into a queryable knowledge graph. Implements 6-signal memory ranking, **AES-256-GCM (`scrypt`) per-user API key encryption**, SSRF-safe ingestion allowlists, graceful zero-key degradation, and **126 automated backend tests**. | [Repo](https://github.com/gauravdev95/AI-powered-career-intelligence-platform) · [Live Demo](https://ai-powered-career-intelligence-platform-y3cn.onrender.com) |
| **[GroundTruth](https://github.com/gauravdev95/GroundTruth-AI-Recruiter-Intelligence)** | **Backend & Distributed Systems**<br>FastAPI, SQLAlchemy 2.x, `psycopg3`, `pgvector`, Celery, Redis, React, TypeScript, Gemini | Domain-driven hiring verification monorepo (**11 bounded domains**, **10 Alembic migrations**). Features 4 Celery task queues (`extraction`, `verification`, `matching`, `dead_letter`), in-process `BAAI/bge-base-en-v1.5` embeddings, 5-term rank fusion, `slowapi` rate limiting, and **46 backend pytest suites**. | [Repo](https://github.com/gauravdev95/GroundTruth-AI-Recruiter-Intelligence) |
| **[CreditPathAI](https://github.com/gauravdev95/Loan-Recovery-Intelligence-Platform)**<br>*(Infosys Internship)* | **Applied ML & Explainability**<br>Python, XGBoost, Scikit-learn, SHAP, FastAPI, React, TypeScript, Docker, GitHub Actions | End-to-end 2-year delinquency prediction on the 150,000-record *Give Me Some Credit* dataset. Leakage-safe preprocessing, **ROC-AUC 0.865**, **PR-AUC 0.394**, **F1 0.434** ($n = 22,409$ test split), per-borrower SHAP waterfalls, 9 FastAPI endpoints, and **81 automated tests (73 backend pytest + 8 frontend)**. | [Repo](https://github.com/gauravdev95/Loan-Recovery-Intelligence-Platform) |
| **[AI Recruiter Auth Core](https://github.com/gauravdev95/AI-Recruiter-Intelligence-System)** | **Security & Auth Architecture**<br>FastAPI, PostgreSQL, Alembic, SQLAlchemy, React, Vite, Tailwind CSS | Production-style identity foundation implementing `bcrypt-12` hashing, short-lived JWT access tokens (30m), hashed opaque refresh token rotation, `HttpOnly` + double-submit CSRF cookies, role guards, and structured request-ID audit middleware. | [Repo](https://github.com/gauravdev95/AI-Recruiter-Intelligence-System) |
| **[PromptForge Studio](https://github.com/gauravdev95/PromptForge-Studio)** | **Developer Tooling**<br>Python, FastAPI, Vanilla JS, Pytest | Deterministic rule-based prompt compiler that transforms raw user intents ($P_0$) into structured prompts ($P_{\text{final}}$) evaluated against intent-specific trap tests with zero external API cost. | [Repo](https://github.com/gauravdev95/PromptForge-Studio) · [Live Demo](https://promptforge-studio-ubiv.onrender.com/) |
| **[AI Notification Assistant](https://github.com/gauravdev95/AI-Notification-Assistant)** | **Android & On-Device Security**<br>Kotlin, Jetpack Compose, Hilt, Room + SQLCipher, Coroutines/Flow, Gemini | Native Android app (`minSdk 26`, `targetSdk 35`) capturing notifications via `NotificationListenerService`, scoring priority with a deterministic rule engine, storing records in **SQLCipher-encrypted Room storage**, and summarizing via Gemini 2.5 Flash. Automated APK builds via GitHub Actions. | [Repo](https://github.com/gauravdev95/AI-Notification-Assistant) |

#### Additional Shipped Projects & Active Research
- **[TalentForge](https://github.com/gauravdev95/talentforge)** *(Smart India Hackathon Finalist, Sep 2025)* — MERN + FastAPI hiring pipeline with `paraphrase-MiniLM-L3-v2` semantic resume scoring and timed Judge0 coding assessments. ([Live Frontend](https://talentforge-frontend.onrender.com))
- **[VoiceHire](https://github.com/gauravdev95/VoiceHire)** — Adaptive voice technical interview coach built with AssemblyAI Voice Agent WebSockets, FastAPI, and React/TypeScript that quotes candidate transcripts as rubric evidence.
- **[Emergency Blood Donor Finder](https://github.com/gauravdev95/Emergency-Blood-Donor-Finder)** — Donor discovery web app using red-cell compatibility lookup tables, **Dijkstra's algorithm** over an Agra locality road graph, and `heapq` nearest-donor ranking.
- **[Realtime Canvas Board (DrawSync)](https://github.com/gauravdev95/realtime-canvas-board)** — Multi-user collaborative whiteboard built with React and Socket.IO supporting infinite pan/zoom, DPR-scaled rendering, and per-user undo/redo stacks. ([Live Demo](https://realtime-canvas-board-frontend.onrender.com/))
- **[Homophily-Aware GNN Fraud Ring Detection](https://github.com/gauravdev95/Homophily-Aware-GNN-Fraud-Ring-Detection)** *(In Progress)* — Temporal graph analysis on the Bitcoin **Elliptic++** dataset (203,769 nodes, 234,355 edges, 49 timesteps). Verified EDA establishes **5.9x illicit-to-illicit homophily linkage** and zero cross-timestep edges; tabular baselines and GNN training in progress.

---

### Technical Stack

- **Proficient:** Python, JavaScript (ES6+), TypeScript, FastAPI, Node.js, Express.js, React, PostgreSQL (`pgvector`), SQL, REST API Design, Git & GitHub Actions
- **Working Knowledge:** Docker & Docker Compose, SQLAlchemy 2.x, Alembic, Celery, Redis, Scikit-learn, XGBoost, SHAP, MongoDB (Mongoose), Socket.IO / WebRTC, Tailwind CSS
- **Currently Learning / Exploring:** PyTorch & Graph Neural Networks (PyG), Agentic Workflows & Deterministic LLM Evaluation, Kotlin & Jetpack Compose

---

### Experience, Achievements & Problem Solving

- **AI/ML Intern — Infosys Springboard** *(Jun 2026 – Aug 2026)*: Designed, trained, and deployed **CreditPathAI** (XGBoost delinquency model, SHAP explainability service, FastAPI backend, and React/TypeScript dashboard).
- **Top 10 Finalist — WikiThon 2026**: Built **Grafted**, an AI career-intelligence and knowledge-graph memory platform.
- **National Finalist — Smart India Hackathon (SIH)** *(Sep 2025)*: Built **TalentForge** end-to-end automated recruitment and coding assessment platform.
- **Rank 6 — Byte Master 2024**: Competitive programming & engineering challenge.
- **Open Source**: Merged contributor to [`iamabhaydawar/devradar` (PR #1)](https://github.com/iamabhaydawar/devradar/pull/1) — architected the React + Vite + Tailwind frontend and wired live backend API integration.
- **Data Structures & Algorithms**: **864 problems solved** on [LeetCode (`gauravDevX`)](https://leetcode.com/gauravDevX/) — **266 Easy · 445 Medium · 153 Hard** across 343 active days (535 submissions in the past year) · B.Tech CSE CGPA: **7.52 / 10**.
