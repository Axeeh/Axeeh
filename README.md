# Hi, I'm Alessio Carnevale

BSc in Data Science and Artificial Intelligence at SUPSI (Switzerland). I build RAG systems, AI agents and web products, and I co-run a small digital studio that brings websites and AI tools to Italian small businesses.

- BSc Data Science and Artificial Intelligence, SUPSI, 2026
- Based in Varese, Italy, studied in Lugano, Switzerland
- Currently weighing a Master's, an internship, or a job as the next step
- Languages: Italian (native), English (B2), German (A2)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

## Bachelor's thesis

**Optimization of a RAG System with a Local LLM for Evidence-Based Medical Guideline Retrieval**
SUPSI, Data Science and Artificial Intelligence, 2026. Supervisor: Vanni Galli. Host company: Alwicom SA.

I built and evaluated a fully local RAG pipeline that answers clinical questions over 44 nephrology and internal medicine guidelines (3,236 PDF pages). The whole system runs locally, with no data sent to external services, since the questions can involve patient information.

- **Serving:** NVIDIA Jetson AGX Orin running qwen3:32b and bge-m3 through Ollama, with PostgreSQL and pgvector on a separate machine
- **Pipeline:** PDF ingestion and chunking with document/page metadata, dense retrieval with guideline routing, a named-document filter, figure OCR, cross-encoder reranking over a deeper candidate pool, focused prompting, and answers with guideline and page citations, plus a web front end
- **Evaluation:** LLM-as-judge across six judge configurations, inter-judge agreement checks, a grounding analysis, an expert clinical review, ablations, and cost/latency measurements
- **Results:** on a 99 question benchmark, 93/99 correct with the local automatic judge and 90/99 with a stricter external judge, with the expected guideline routed correctly in 98/99 cases. Cross-encoder reranking was the single biggest improvement, raising the local score from 66 to 81

## Digitalization and AI for small businesses

I co-run **Plasma**, a small digital studio based in Besnate (VA), together with Matteo Martinelli, helping Italian SMBs (local shops, restaurants, fashion, professionals) get online and adopt AI where it actually helps their business.

- Websites, Next.js apps and booking systems
- Local SEO and Google Business Profile optimization
- Social management, content and branding
- AI/RAG integrations for client-facing tools

My side of the work is mainly development, SEO and Local SEO.

## Skills

**Languages:** Python, TypeScript/JavaScript, SQL, R, C++, C#

**AI/ML:** Machine Learning, Deep Learning, NLP, RAG systems, LangChain, local LLMs (Ollama), Computer Vision, AI agents

**Web & backend:** React, Next.js (App Router), Node.js, FastAPI, Flask, REST APIs

**Data & infrastructure:** PostgreSQL, MongoDB, pgvector, Docker, AWS S3, Supabase (Auth, Realtime, Storage, Edge Functions), Netlify Functions

**Tools:** Git/GitHub, CI/CD, Vercel, Netlify

## Featured projects

**Polymarket Latency Arbitrage Bot**
A Python bot that exploits price lag between Binance/Coinbase and Polymarket. Async architecture, Kelly sizing for position sizing, Telegram alerts.

**TaxAI**
An AI-powered fiscal assistant for the Italian market, grounded in Italian tax law through a RAG pipeline. Built with FastAPI, Next.js, Claude 3.5 Sonnet, pgvector and Supabase.

## GitHub stats

![Alessio's GitHub stats](https://github-readme-stats.vercel.app/api?username=Axeeh&show_icons=true&hide_border=true&theme=default)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Axeeh&layout=compact&hide_border=true&theme=default)

## Get in touch

- Digital studio: [plasmadigital.co](https://plasmadigital.co)
