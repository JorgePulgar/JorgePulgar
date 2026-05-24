<!--
  GitHub profile README for JorgePulgar (Spanish version)
  File location: github.com/JorgePulgar/JorgePulgar
  Place this file as README.es.md at the root of that repo.
-->

<p align="right"><sub><a href="./README.md">English</a> · <b>Español</b></sub></p>

<h1 align="center">Hola, soy Jorge 👋</h1>

<p align="center">
  <b>Junior AI Engineer</b> · Construyendo aplicaciones con LLMs sobre Azure<br>
  <sub>Con base en Madrid · Abierto a oportunidades en toda Europa (remoto o relocation)</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jorge-pulgar-pacho-22b45233b/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Conectar-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
  <a href="mailto:jorgepulgar.ai@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contacto-D14836?style=flat&logo=gmail&logoColor=white"></a>
  <img alt="Ubicación" src="https://img.shields.io/badge/Madrid-España-red?style=flat">
  <img alt="Idiomas" src="https://img.shields.io/badge/ES%20nativo%20·%20EN%20C1-blue?style=flat">
</p>

---

### Sobre mí

Construyo **aplicaciones LLM listas para producción** — sistemas RAG, modelos fine-tuned y backends potenciados por IA — con un fuerte sesgo hacia arquitecturas *retrieval-first* que no alucinan.

Estoy completando un **Máster en IA e Ingeniería de Datos** en Tajamar (Madrid) y tengo cuatro certificaciones de Azure: **AI-102**, **DP-100**, **DP-300** y **DP-900**. Mi experiencia más reciente fue como AI Application Developer en prácticas en **Datarmony**, donde construí una aplicación de ingesta de estados financieros sobre Google Cloud + Gemini.

La mayor parte de lo que construyo se apoya en el mismo stack: **Azure AI Foundry + Azure AI Search + FastAPI + React**, orquestado con Python y el SDK de OpenAI.

---

### Proyectos destacados

#### [RAG Assistants Platform](https://github.com/JorgePulgar/Rag-Assistants-Platform) — *proyecto principal*
Plataforma RAG multi-tenant full-stack con **aislamiento estructural por índice** (un índice de Azure AI Search por asistente), memoria conversacional, reescritura de queries con LLM y citas verificables. Fallback estricto "no lo sé" cuando el retrieval está vacío — sin alucinaciones por diseño. **~2.6k LOC de Python + ~1.5k LOC de TypeScript, 56 tests unitarios, construido en 7 días.**
> `Azure AI Foundry` · `Azure AI Search` · `FastAPI` · `React` · `TypeScript` · `Hybrid Search` · `Semantic Reranking`

#### [Fraud Autoencoder](https://github.com/JorgePulgar/fraud-autoencoder) — *[demo en el navegador](https://jorgepulgar.github.io/fraud-autoencoder/)*
Detección no supervisada de fraude en tarjetas de crédito mediante autoencoder con error de reconstrucción. **Elegido a sabiendas de que los modelos supervisados puntúan más alto** — refleja el escenario real de producción donde las etiquetas de fraude van por detrás de los patrones de fraude. PR-AUC ~3× el baseline de Isolation Forest, acotado por una Logistic Regression como cota superior. **Exportado a ONNX con verificación numérica <1e-5** y servido desde el mismo archivo de modelo en el navegador. Prevención de data leakage forzada mediante asserts en el código.
> `Deep Learning` · `Anomaly Detection` · `PyTorch` · `ONNX` · `Unsupervised Learning` · `TensorFlow.js` · `React`

#### [Sales Receptivity CNN](https://github.com/JorgePulgar/sales-receptivity-cnn) — *[demo web en vivo](https://jorgepulgar.github.io/sales-receptivity-cnn/)*
Analizador en tiempo real de emociones faciales para llamadas de venta. Dos arquitecturas CNN comparadas end-to-end (CNN custom de 4 bloques vs MobileNetV2 fine-tuned, 63 % de accuracy en test) alimentando un **índice de receptividad** con ventana deslizante como señal de coaching. Ejecutable en el navegador vía **TensorFlow.js** — sin instalación, funciona en móvil o portátil. Servicio FastAPI + demo Streamlit comparten un único módulo de inferencia. **4 notebooks pedagógicos documentando cada fallo de entrenamiento y su solución.**
> `Deep Learning` · `Computer Vision` · `TensorFlow` · `TensorFlow.js` · `CNN` · `Transfer Learning` · `FastAPI` · `Streamlit`

#### [Invoice Insights — AI Invoice Analyzer](https://github.com/JorgePulgar/ai-invoice-analyzer) — *proyecto en equipo*
SaaS full-stack para autónomos y pymes en España. Sube facturas en PDF, ejecuta **extracción estructurada con GPT-4o** vía Azure AI Foundry, valida el JSON y muestra un dashboard con KPIs, evolución mensual, top clientes/proveedores e IVA trimestral. **Construido en una semana con un compañero de equipo.** Diseño deliberado de extracción en una sola llamada (sin agentes) — más fiable, más barato y más fácil de depurar para datos estructurados de facturas.
> `Azure AI Foundry` · `GPT-4o` · `Structured Extraction` · `React` · `TypeScript` · `Node.js` · `Express` · `SQLite`

#### [FinBot — Fine-Tuning en Azure AI Foundry](https://github.com/JorgePulgar/FinBot-Fine-Tuning-with-Azure-AI-Foundry)
Fine-tuning de `gpt-4o-mini` para actuar como asistente de educación financiera con **formato, tono y disclaimers legales consistentes**. Dataset JSONL propio, análisis de overfitting y debugging de comportamiento multi-cliente.
> `Fine-tuning` · `Azure AI Foundry` · `gpt-4o-mini` · `JSONL` · `Evaluación`

#### [OCR + ML Pipeline para Predicción de Menús](https://github.com/JorgePulgar/OCR-and-ML-Pipeline-for-Menu-Predictions)
Aplicación web full-stack que combina **OCR de Azure Computer Vision** para extraer datos de menús a partir de fotos con un **modelo de clasificación scikit-learn** para predecir menús diarios. Backend en FastAPI, frontend en Next.js, persistencia en Supabase.
> `Computer Vision` · `OCR` · `scikit-learn` · `FastAPI` · `Next.js` · `Supabase`

---

### Stack técnico

**IA / ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D97757?style=flat)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)

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

**Cloud y herramientas**
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat)

---

### Certificaciones y formación

- **[Microsoft Certified: Azure AI Engineer Associate (AI-102)](https://learn.microsoft.com/api/credentials/share/es-es/JorgePulgar-9810/2BD1A342A22AC3A?sharingId=F046BF4AE8A23760)**
- **[Microsoft Certified: Azure Data Scientist Associate (DP-100)](https://learn.microsoft.com/api/credentials/share/es-es/JorgePulgar-9810/C7A2A6093EDD14D1?sharingId=F046BF4AE8A23760)**
- **[Microsoft Certified: Azure Database Administrator Associate (DP-300)](https://learn.microsoft.com/api/credentials/share/es-es/JorgePulgar-9810/C985862E6849BE86?sharingId=F046BF4AE8A23760)**
- **[Microsoft Certified: Azure Data Fundamentals (DP-900)](https://www.credly.com/badges/948b56df-4c7d-416d-90a3-c808ae797612)**
- **Máster en IA e Ingeniería de Datos** — Tajamar, Madrid *(2025–)*
- **Desarrollo de Aplicaciones Web** — IES Pío Baroja, Madrid *(2023–2025)*
- **Cambridge English: C1 Advanced**

---

### Actualmente

**TFM @ Integra — Sistema de análisis de licitaciones públicas** *(equipo de 3, repo privado)*
Construyendo un sistema basado en IA que analiza documentos de licitaciones públicas, extrae datos estructurados, los resume en lenguaje claro y ayuda a la empresa a redactar mejores propuestas. **Mi rol:** implementación de backend + IA sobre **Azure AI Foundry** con un pipeline RAG sobre el corpus de licitaciones.
> `RAG` · `Azure AI Foundry` · `Análisis de Documentos` · `FastAPI` · `Proyecto en equipo`

Además:
- Diseñando un sistema multi-agente para automatizar la gestión de candidaturas
- **Abierto a oportunidades como Junior AI Engineer** — en toda Europa, remoto o relocation. Con base en Madrid.

---

### Hablemos

**¿Buscas un Junior AI Engineer?** Estoy en Madrid y disponible para roles full-time en toda Europa — remoto o relocation. Construyo sistemas LLM y ML en producción sobre Azure que resuelven problemas de negocio reales, no solo demos. Contáctame por [email](mailto:jorgepulgar.ai@gmail.com) o [LinkedIn](https://www.linkedin.com/in/jorge-pulgar-pacho-22b45233b/) — respondo en menos de 24h.
