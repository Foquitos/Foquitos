# Hola, soy Ignacio Otranto 👋

**AI Engineer · Backend Python** — Buenos Aires, Argentina

Construyo sistemas de IA para operaciones reales. Hoy trabajo en un contact center (BPO), donde desarrollé la
plataforma que audita la calidad de las llamadas con LLMs, los chatbots RAG que usan los operadores y el
planificador que pronostica cuánta gente hace falta en cada media hora. Me interesa la parte que viene después
del prototipo: medir si la IA realmente acierta, controlar lo que cuesta y que el sistema aguante en producción.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ignacio--julian--otranto-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ignacio-julian-otranto/)
[![Email](https://img.shields.io/badge/Email-otrantoignacio0%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:otrantoignacio0@gmail.com)

---

## Proyectos destacados

### [Contact Center AI](https://github.com/Foquitos/contact-center-ai)
Plataforma completa de un contact center, en producción. La IA (Gemini) audita audios y chats contra la plantilla de
cada campaña. Incluye un dashboard de calidad, chatbots RAG híbridos (Qdrant + BM25 + reranker), un planificador de
dotación con GBDT y Erlang C/A, y RBAC con jerarquía de roles. Tiene una demo con SQL Server en Docker y ~2.700
tests en CI.
`FastAPI` `Flask` `SQL Server` `Gemini` `LlamaIndex` `Qdrant` `scikit-learn` `Docker`

<a href="https://github.com/Foquitos/contact-center-ai"><img src="https://raw.githubusercontent.com/Foquitos/contact-center-ai/main/docs/img/recorrido.gif" width="720" alt="Recorrido por Contact Center AI"></a>

### [Evaluar a un auditor basado en LLM](https://github.com/Foquitos/llm-eval-case-study)
Caso de estudio sobre cómo medir si un auditor de calidad con LLM realmente acierta. Explica por qué el porcentaje
de acierto engaña, cómo usar kappa de Cohen por atributo y cómo armar un golden set con revisión humana.

### [FinSight AI](https://github.com/Foquitos/FinSight-AI)
Agente conversacional para analistas de fraude. Responde sobre políticas (KYC, AML, PCI DSS) con RAG, convierte
preguntas en SQL, predice fraude con un modelo de ML y recuerda la conversación de cada usuario.
`FastAPI` `LlamaIndex ReAct` `ChromaDB` `scikit-learn`

### [Cuotas Scout](https://github.com/Foquitos/Gestion-finanzas-y-proyectos-scout)
Aplicación web para cobrar campamentos y actividades de un grupo scout desde el celular. Lleva los saldos por
familia, emite comprobantes para compartir por WhatsApp y ordena la rendición del dinero.
`FastAPI` `SQLAlchemy` `Docker` `Azure Container Apps`

### [Análisis de alquileres de Zonaprop](https://github.com/Foquitos/zonaprop)
Scraper resiliente de avisos de alquiler con análisis asistido por LLMs, incluida la revisión de fotos, y un
dashboard interactivo.
`Playwright` `Claude` `Gemini`

---

## Con qué trabajo

**IA y datos:** LLMs (Gemini, Claude), RAG (LlamaIndex, Qdrant, ChromaDB, BM25, rerankers), evaluación de modelos,
scikit-learn, pandas, pronóstico de series de tiempo

**Backend:** Python, FastAPI, Flask, SQLAlchemy, APIs REST, colas y procesos programados

**Datos y entrega:** SQL Server (T-SQL, stored procedures), PostgreSQL, SQLite, Docker, GitHub Actions, pytest

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white)
![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini-8E75B2?logo=googlegemini&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

---

<details>
<summary><b>In English</b></summary>

I'm an AI Engineer and Python backend developer based in Buenos Aires. At a contact center (BPO) I built the
platform that audits call quality with LLMs, the RAG chatbots agents use every day, and the workforce planner
that forecasts calls per half hour. I care about what comes after the prototype: measuring whether the AI is
actually right, keeping costs under control, and making it hold up in production.

Highlights: [Contact Center AI](https://github.com/Foquitos/contact-center-ai) (production platform: LLM quality
audits, hybrid RAG, forecasting) · [LLM evaluation case study](https://github.com/Foquitos/llm-eval-case-study) ·
[FinSight AI](https://github.com/Foquitos/FinSight-AI) (fraud-analyst agent with RAG, text-to-SQL and ML).

</details>
