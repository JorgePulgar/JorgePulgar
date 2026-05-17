<!--
  GitHub profile README for JorgePulgar (English version)
  File location: github.com/JorgePulgar/JorgePulgar
  Place this file as README.md at the root of that repo.
-->

<p align="right"><sub><b>English</b> · <a href="./README.es.md">Español</a></sub></p>

<h1 align="center">Hi, I'm Jorge 👋</h1>

<p align="center">
  <b>Junior AI Engineer</b> · Building LLM-powered applications on Azure<br>
  <sub>Madrid, Spain · Open to Junior AI Engineer roles</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jorge-pulgar-pacho-22b45233b/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="mailto:jorgepulgar.ai@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact-D14836?style=flat&logo=gmail&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/Madrid-Spain-red?style=flat">
  <img alt="Languages" src="https://img.shields.io/badge/ES%20native%20·%20EN%20C1-blue?style=flat">
</p>

---

### About me

I build **production-grade LLM applications** — RAG systems, fine-tuned models, and AI-powered backends — with a strong bias toward retrieval-first architectures that don't hallucinate.

I'm completing a **Professional Master's in AI and Data Engineering** at Tajamar (Madrid) and hold four Azure certifications: **AI-102**, **DP-100**, **DP-300**, and **DP-900**. My most recent role was an AI Application Developer internship at **Datarmony**, where I built a financial statement ingestion app on Google Cloud + Gemini.

Most of what I build sits on the same stack: **Azure AI Foundry + Azure AI Search + FastAPI + React**, orchestrated with Python and the OpenAI SDK.

---

### Featured projects

#### [RAG Assistants Platform](https://github.com/JorgePulgar/Rag-Assistants-Platform) 
Full-stack multi-tenant RAG platform with **structural index isolation** (one Azure AI Search index per assistant), conversational memory, LLM-based query rewriting, and verifiable citations. Hard "I don't know" fallback when retrieval is empty — no hallucinations by design. **~2.6k LOC Python + ~1.5k LOC TypeScript, 56 unit tests, built in 7 days.**
> `Azure AI Foundry` · `Azure AI Search` · `FastAPI` · `React` · `TypeScript` · `Hybrid Search` · `Semantic Reranking`

#### [Sales Receptivity CNN](https://github.com/JorgePulgar/sales-receptivity-cnn) — *[live web demo](https://jorgepulgar.github.io/sales-receptivity-cnn/)*
Real-time facial-emotion analyzer for sales calls. Two CNN architectures benchmarked end-to-end (custom 4-block CNN vs fine-tuned MobileNetV2, 63 % test accuracy) feeding a **rolling receptivity index** as a coaching signal. Live in the browser via **TensorFlow.js** — no install, runs on phone or laptop. FastAPI service + Streamlit demo share one inference module. **4 pedagogical notebooks documenting every training failure and fix.**
> `Deep Learning` · `Computer Vision` · `TensorFlow` · `TensorFlow.js` · `CNN` · `Transfer Learning` · `FastAPI` · `Streamlit`

#### [FinBot — Fine-Tuning on Azure AI Foundry](https://github.com/JorgePulgar/FinBot-Fine-Tuning-with-Azure-AI-Foundry)
Fine-tuned `gpt-4o-mini` to act as a financial education assistant with **consistent format, tone, and legal disclaimers**. Custom JSONL dataset, overfitting analysis, multi-client behavior debugging.
> `Fine-tuning` · `Azure AI Foundry` · `gpt-4o-mini` · `JSONL` · `Evaluation`

#### [OCR + ML Pipeline for Menu Predictions](https://github.com/JorgePulgar/OCR-and-ML-Pipeline-for-Menu-Predictions)
Full-stack web app combining **Azure Computer Vision OCR** to extract menu data from photos with a **scikit-learn classification model** to predict daily menus. FastAPI backend, Next.js frontend, Supabase persistence.
> `Computer Vision` · `OCR` · `scikit-learn` · `FastAPI` · `Next.js` · `Supabase`

#### [Vector Search with Azure AI Search](https://github.com/JorgePulgar/Embeddings-Vector-Database-with-Azure-AI-Search)
Hands-on lab covering four search modalities (**Vector, Hybrid, Semantic, Semantic Hybrid**) plus Scoring Profiles, built with Azure OpenAI embeddings and the `azure-search-documents` SDK.
> `Vector Search` · `Embeddings` · `Azure AI Search` · `RAG Foundations`

#### [Prompt Engineering & LLM Parameterization](https://github.com/JorgePulgar/AI-Experiments--Prompt-Engineering-and-LLM-Parameterization)
Practical experiments with **6 prompt engineering techniques** and model parameter tuning (temperature, top_p, frequency/presence penalties) on `gpt-4o` via Azure AI Foundry.
> `Prompt Engineering` · `Azure AI Foundry` · `gpt-4o`

---

### Tech stack

**AI / ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D97757?style=flat)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

**Azure**
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Azure AI Foundry](https://img.shields.io/badge/Azure_AI_Foundry-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Azure AI Search](https://img.shields.io/badge/Azure_AI_Search-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)

**Cloud & Tooling**
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat)

---

### Certifications & education

- **[Microsoft Certified: Azure AI Engineer Associate (AI-102)](https://learn.microsoft.com/api/credentials/share/en-us/JorgePulgar-9810/2BD1A342A22AC3A?sharingId=F046BF4AE8A23760)**
- **[Microsoft Certified: Azure Data Scientist Associate (DP-100)](https://learn.microsoft.com/api/credentials/share/en-us/JorgePulgar-9810/C7A2A6093EDD14D1?sharingId=F046BF4AE8A23760)**
- **[Microsoft Certified: Azure Database Administrator Associate (DP-300)](https://learn.microsoft.com/api/credentials/share/en-us/JorgePulgar-9810/C985862E6849BE86?sharingId=F046BF4AE8A23760)**
- **[Microsoft Certified: Azure Data Fundamentals (DP-900)](https://www.credly.com/badges/948b56df-4c7d-416d-90a3-c808ae797612)**
- **Professional Master's in AI and Data Engineering** — Tajamar, Madrid *(2025–)*
- **Web Application Development** — IES Pío Baroja, Madrid *(2023–2025)*
- **Cambridge English: C1 Advanced**

---

### Currently

**TFM @ Integra — Public tender analysis system** *(team of 3, private repo)*
Building an AI-powered system that parses public tender documents (*licitaciones*), extracts structured data, summarizes them in plain language, and helps the company draft stronger bid proposals. **My role:** backend + AI implementation on **Azure AI Foundry** with a RAG pipeline over tender corpora.
> `RAG` · `Azure AI Foundry` · `Document Analysis` · `FastAPI` · `Team project`

Also:
- Designing a multi-agent system for automated job application management
- **Open to Junior AI Engineer roles** in Madrid or remote 

---

### Let's talk

**Hiring a Junior AI Engineer?** I'm available for full-time roles in Madrid or remote, building production LLM and ML systems on Azure that solve real business problems — not just demos. Reach me by [email](mailto:jorgepulgar.ai@gmail.com) or [LinkedIn](https://www.linkedin.com/in/jorge-pulgar-pacho-22b45233b/) — I reply within 24h.

---

<p align="center">
  <a href="https://github.com/JorgePulgar"><img src="https://github-readme-stats.vercel.app/api?username=JorgePulgar&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=default" alt="GitHub stats"></a>
  <a href="https://github.com/JorgePulgar"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JorgePulgar&layout=compact&hide_border=true&theme=default" alt="Top languages"></a>
</p>
