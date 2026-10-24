
<div align="center">

# Jasmaine Khale

**Backend Engineer · AI/ML Systems · Distributed Systems**

MS Computer Science @ Northeastern University | May 2026

Ex-EY/Deloitte/Microsoft 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/jasmaine-khale)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:jasmaine.khale48@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/adjascently)
![Open to Work](https://img.shields.io/badge/Open%20to%20Work-Backend%20%7C%20AI%2FML%20Engineer-brightgreen?style=flat)

</div>

---

## About

Software engineer with experience building backend systems, cloud-native applications, and AI-powered solutions across EY, Deloitte, and independent engineering projects. I specialize in **scalable backend infrastructure, distributed systems, and LLM-integrated applications**, including RAG pipelines, event-driven architectures, multi-model verification, and REST APIs.

Actively interviewing for full-time **Software Engineer**, **Backend Engineer**, and **AI/ML Engineer** roles. Available immediately, open to SF Bay Area and remote opportunities.

---

## Projects

### 🔭 AgentScope — AI Agent Observability Platform
> Distributed systems · Python · FastAPI · Apache Kafka · PostgreSQL · Next.js · TypeScript · Docker

Building an event-driven observability platform for collecting, processing, and visualizing AI agent execution traces.

- Architected an asynchronous trace ingestion pipeline using FastAPI, Apache Kafka, and PostgreSQL.
- Implemented a Kafka consumer for processing execution spans and persisting structured metadata in PostgreSQL.
- Built REST APIs for trace ingestion, execution history, and run-level inspection.
- Developed a Next.js dashboard for exploring agent runs, execution spans, and trace details.
- Containerized Kafka and PostgreSQL using Docker Compose for local development.

**Architecture:** `AI Agents → FastAPI → Kafka → Consumer → PostgreSQL → Dashboard`

**Roadmap:** Prometheus metrics, Grafana dashboards, Kubernetes deployment, and advanced latency/token analytics.

**Status:** Active development

---

### 🛂 VisaMate — Verified AI Immigration Assistant
> RAG · Python · FastAPI · MongoDB · ChromaDB · OpenAI · Claude · Gemini

Built an AI-powered immigration guidance system that grounds LLM responses in official USCIS and SEVP policy documentation.

- Engineered a RAG pipeline over **15,000+ policy chunks** with stage-aware semantic retrieval.
- Orchestrated multi-model verification across OpenAI, Claude, and Gemini to improve response reliability.
- Achieved approximately **95% policy-aligned accuracy** across 200 evaluation scenarios.
- Reduced measured hallucination rates to **38.2%**, compared with approximately 55–58% for evaluated baseline models.
- Integrated citation-backed answers and automated policy refresh workflows.

---

### 💳 Smart Personal Finance Tracker
> Serverless AWS · Step Functions · SQS · EventBridge · SNS · Lambda · DynamoDB · RDS · React

Built a serverless personal finance application using an event-driven AWS architecture spanning 15 services across six layers.

- Designed automated bank statement ingestion using Amazon S3 and asynchronous event processing.
- Integrated EventBridge, Step Functions, SQS, and Lambda for transaction processing workflows.
- Used DynamoDB and RDS MySQL for distinct persistence and data-access requirements.
- Incorporated SNS-based threshold alerts, CloudWatch monitoring, and an architecture supporting ML-based transaction categorization.

---

### 📚 PaperSage — AI Research Assistant
> Python · FastAPI · LangChain · OpenAI · FAISS · Ollama

Built a research paper summarization and semantic retrieval microservice designed to streamline academic literature review.

- Developed a modular ingestion pipeline for document chunking, embedding, and indexing.
- Integrated FAISS-based semantic search with LLM-powered summarization and contextual question answering.
- Implemented FastAPI endpoints supporting concurrent multi-document research workflows.
- Designed modular ingestion, retrieval, and inference components.

---

### 🧠 Few-Shot Retinal Disease Classification
> Machine Learning Research · PyTorch · ResNet34 · Prototypical Networks · CLAHE

Developed a few-shot learning framework for retinal disease classification using the RFMiD dataset.

- Implemented Prototypical Networks with ResNet-based feature extraction and episodic learning.
- Applied CLAHE preprocessing, cosine similarity, and temperature scaling to improve feature discrimination.
- Evaluated performance under class imbalance and limited labeled training data.
- Achieved **37.80% average episodic accuracy** and **34.07% average macro-F1** in a three-way, five-shot experimental configuration.

---

## Tech Stack

**Backend & APIs**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)

**Databases & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Cloud, DevOps & Observability**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![GitLab CI/CD](https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=flat&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

---

## Experience

| Company / Organization | Role | Period |
|---|---|---|
| Community Dreams Foundation | Software Engineer & Team Captain (Volunteer) | 2026 – Present |
| Ernst & Young | Software Engineering Intern | Jan – May 2024 |
| Deloitte | Technology Consulting Intern | Jun – Aug 2023 |
| Microsoft | Future Ready Talent Intern | May – Jul 2022 |
| Celebal Technologies | Data & Analytics Intern | May – Aug 2022 |

---

## Education

| Degree | Institution | Year |
|---|---|---|
| MS Computer Science — GPA 3.8/4.0 | Northeastern University, San Jose | May 2026 |
| BTech Computer & Communications | Manipal University Jaipur | Jun 2024 |

---

## Research & Publications

**Balanced Few-Shot Episodic Learning for Accurate Retinal Disease Diagnosis**

Few-shot Learning · Prototypical Networks · PyTorch · Computer Vision · Clinical AI

---

<div align="center">

### Let's Connect

**Open to full-time Backend Engineering, Software Engineering, and AI/ML Engineering opportunities.**

[![LinkedIn](https://img.shields.io/badge/Let's%20connect-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/jasmaine-khale)
[![Email](https://img.shields.io/badge/Email%20me-jasmaine.khale48%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:jasmaine.khale48@gmail.com)

</div>
