<h1 align="center">Rujhan Jain</h1>

<p align="center">
  <b>Generative AI Engineer · Agentic Systems · Document Intelligence · Computer Vision</b><br/>
  Building deterministic, production-grade AI systems
</p>

<p align="center">
  <a href="mailto:rujhanjain07@gmail.com">
    <img src="https://img.shields.io/badge/Email-2E7D32?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/rujhanjain07/rujhanjain07/blob/main/Rujhan%20Jain%20CV.pdf">
    <img src="https://img.shields.io/badge/Download_CV-1565C0?style=flat&logo=readthedocs&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/rujhanjain-ai-engineer/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Generative_AI-6A1B9A?style=flat"/>
  <img src="https://img.shields.io/badge/Agentic_AI-C2185B?style=flat"/>
  <img src="https://img.shields.io/badge/Computer_Vision-00838F?style=flat"/>
</p>

---

## Overview

I design **applied AI systems** that operate beyond notebooks and demos — in domains where a wrong answer isn't a bad UX, it's a compliance problem.

Currently a **Generative AI Developer at CGM ARIA**, building document-intelligence pipelines for healthcare revenue-cycle management: OCR + LLM extraction paired with deterministic, rule-based validation to eliminate hallucination risk at scale, in production, across 100+ providers with no shared format standard.

My work sits at the intersection of:
- modern AI models
- real, imperfect data
- system constraints and product requirements

I'm most effective when AI is treated as a **system component**, not a feature — the model proposes, the system disposes.

---

## What I Focus On

### 🧠 Agentic & Generative AI
- LLM-powered extraction and reasoning systems using **RAG, embeddings, and vector databases**
- Multi-step agent workflows with **LangGraph / LangChain**
- Deterministic post-validation layers that keep generative systems auditable in regulated domains
- Async, queue-managed processing (**Celery + Redis**) for production-scale document pipelines
- Intent routing, tool use, memory, and decision loops

### 👁️ Computer Vision Systems
- Visual inspection and defect detection (YOLO-based) — pharmaceutical manufacturing
- Pose estimation and movement analysis (Mediapipe) — real-time healthcare monitoring
- Systems designed with attention to **latency, throughput, and reliability**

### 🏗️ Platforms & Tooling
- Designing internal AI platforms and developer tools
- Full-stack understanding across **AI, backend services, and data pipelines**
- Bridging **open-source ML** with **enterprise-grade platforms** (Azure OpenAI, Azure Document Intelligence)
- Bias toward clarity, maintainability, and inspectable execution

---

## Selected Work

> This is a curated set. Focus is on **problem framing and system design**, not volume.

### 🔹 Patient Payment Extraction & Reconciliation Pipeline · CGM ARIA
Production-beta document-intelligence pipeline extracting structured payment data from scanned, handwritten, and multi-format PDFs — submitted by 100+ healthcare providers with no shared format standard, including single documents with 30+ distinct payments.

- Designed the full extraction architecture: OCR + LLM-based extraction + deterministic post-validation
- Built shape-based document classification and keyed-field extraction to generalize across inconsistent provider layouts
- Async, queue-managed processing (Celery + Redis) against fire-and-forget ingestion APIs
- Structured CSV/JSON output with exception-handling for downstream RPA consumption

### 🔹 Provider Credentialing Automation – CAQH · CGM ARIA
Extraction-to-schema pipeline converting complex, multi-section provider credentialing forms into a validated **60+ field JSON schema** for downstream API integration.

- Prioritized field-level accuracy and deterministic output over generative flexibility
- Built schema-validation controls guaranteeing structurally consistent output for integration partners

### 🔹 Agentic RAG System for Cross-Dataset Analysis & Fraud Detection · Nupeak
An agentic AI system to query and investigate multiple heterogeneous tabular datasets with **no shared keys and inconsistent schemas**, built from scratch (custom retriever and knowledge-base classes, not a framework wrapper).

- Schema-aware retrieval and dataset routing
- SQL generation for single-dataset queries
- Cross-dataset entity resolution via fuzzy matching
- React front-end for interactive investigation

### 🔹 OrchestR-OSS · Agentic Workflow Tooling
A local-first, open-source developer tool for visually designing and validating agentic AI workflows and compiling them into executable Python projects.

- Visual workflow editor with explicit node and edge semantics
- Workflow validation and structural guarantees
- Visual-to-code compilation approach
- Designed for transparency, correctness, and developer control

### 🔹 Agentic AI for HRMS · Product Architecture, Nupeak
AI-powered HRMS SaaS designed for intelligent automation and executive decision support — led solution architecture through pitch stage.

- Architected LLM-based workflows for HR operations: agent roles, logic, and data flow
- Designed enterprise data integration strategy — security, scalability, system boundaries

### 🔹 Real-Time Physiotherapy Monitoring · Computer Vision, Nupeak
Real-time posture and movement-analysis system providing continuous feedback during rehabilitation exercises.

- Pose-estimation and temporal-tracking pipelines (Mediapipe)
- Custom frame-to-frame scoring logic for exercise correctness and progression

---

## Tech Stack (What I Actually Use)

**Languages**
- Python · SQL · JavaScript · HTML5 · CSS3

**AI / ML**
- Azure OpenAI (GPT) · Azure Document Intelligence
- LangChain · LangGraph · RAG · Prompt Engineering · Hugging Face · LlamaIndex
- PyTorch · YOLO · Mediapipe

**Systems**
- FastAPI · Pydantic
- Celery · Redis (async, queue-managed processing)
- Docker · Containerized services
- PostgreSQL · ChromaDB · FAISS · pgvector

**Delivery & Collaboration**
- GitLab · Jira · Confluence
- Solution advisory, client pre-sales, stakeholder alignment

---

## Beyond Engineering

- Promoted within 14 months in my first AI role, taking increasing ownership across Computer Vision, Generative AI, and Agentic AI projects
- Represented enterprise AI solutions at **GITEX Dubai 2025** to global enterprise stakeholders
- Supported solution pitches and POCs across public sector, banking, pharmaceutical, manufacturing, and semiconductor domains — from client discovery through final presentation
- Regularly involved in solution advisory and technical stakeholder discussions

---

## How I Work

- Systems over scripts
- Clarity over cleverness
- Deterministic validation over blind trust in generative output
- Production constraints matter
- Learn fast, adapt faster

If something breaks, I want to understand *why*, not hide it.

---

<sub>This repository is a living portfolio. It reflects how I think and build, not just what I've shipped.</sub>
