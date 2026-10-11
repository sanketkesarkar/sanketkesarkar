<h1 align="center">👋 Sanket Kesarkar</h1>

<h3 align="center">Software Engineer | AI & LLM Systems | Backend & Cloud</h3>

<p align="center">
  <a href="https://linkedin.com/in/sanketk07"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sanketkusa@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 🎯 About Me

I'm a software engineer who builds **production-grade AI applications**: **RAG pipelines**, **LLM agents**, and **real-time AI services**. I bring **3+ years of backend and cloud experience**, so the AI systems I build are fast, observable, and ready for real traffic, not just demos. MS grad from Northeastern University.

```python
sanket = {
    "location": "Los Angeles, CA",
    "education": "MS Computer Software Engineering @ Northeastern University",
    "seeking": "Full-time AI / ML Engineering & Backend roles",
    "building_with": ["LangChain", "LangGraph", "RAG", "MCP", "pgvector"],
    "interests": ["LLM Agents", "Retrieval Systems", "Real-Time AI", "AI Infrastructure"],
    "current_focus": "Shipping low-latency, reliable LLM-powered systems",
}
```

## 🤖 Featured AI Projects

### 📄 DocMind — RAG Document Intelligence Platform
Production-style PDF question answering with hybrid retrieval and grounded, cited answers

- **Hybrid search:** pgvector cosine similarity + BM25 keyword search merged with **Reciprocal Rank Fusion**
- **Fast:** **10ms p50 / 18ms p95** search latency and **205ms p50** end-to-end retrieval (k6 load tested)
- **Grounded:** SSE-streamed answers with **page-level citations** and **confidence-based abstention** when evidence is weak
- **Scalable ingestion:** async Redis/RQ workers with idempotent chunk deduplication into **3,072-dim embeddings**

**Tech:** Python • FastAPI • LangChain • PostgreSQL + pgvector • Redis/RQ • Docker

### 🎙️ Therapist Copilot — Real-Time AI Service
Live session transcription with LLM-driven risk assessment and crisis alerts

- **Real-time audio:** bidirectional WebSockets streaming to Deepgram with buffering and **automatic provider fallback**
- **LLM reasoning:** async Gemini + LangChain workflows turning live transcripts into **structured JSON risk scores**
- **Safety controls:** configurable crisis alert thresholds and session-level locking to prevent concurrent writes

**Tech:** Python • FastAPI • WebSockets • Deepgram • Gemini • LangChain • Docker

### ☁️ TerraScale — Cloud Infrastructure Automation
The infrastructure side of shipping AI: highly available GCP deployments with **zero-downtime** rolling releases

- **Infrastructure as code:** provisioned the full GCP stack with **Terraform**: Node.js REST APIs, Cloud SQL, and HTTPS load balancing
- **High availability:** regional managed instance groups with **automatic horizontal scaling** across multiple instances
- **Zero-downtime releases:** GitHub Actions pipelines deploying **Packer-built machine images** via rolling updates
- **Safe rollouts:** automated rollback keeps the app available if a production release fails

**Tech:** Node.js • MySQL • GCP • Terraform • Packer • GitHub Actions

## 🛠️ Technical Skills

```yaml
AI & LLM:        LangChain, LangGraph, RAG, Model Context Protocol (MCP), Fine-tuning,
                 GPT-4 / Vision, Google Gemini, Embeddings, Hybrid Search (BM25 + RRF)
Vector & Data:   pgvector, PostgreSQL, Redis, MongoDB, MySQL
Languages:       Python, Java, Go, TypeScript, JavaScript, C, C++, SQL, Bash
Backend:         FastAPI, Node.js, Express, WebSockets, SSE, REST, Microservices
Cloud & DevOps:  AWS, GCP, Azure, Docker, Kubernetes, Terraform, GitHub Actions
Messaging:       RabbitMQ, Redis/RQ, Dead-Letter Queues, Idempotent Processing
```

## 💼 Experience

🔹 **AeroShield Materials** — *Software Engineering Co-Op*
- Built FastAPI + SQL Server workflows for **100+ employees**, cutting report generation from **hours to minutes**
- Secured APIs with RBAC, Azure AD, and OAuth 2.0 / JWT; automated Docker deployments via GitHub Actions

🔹 **Accenture** — *Software Developer*
- Cut API latency from **~800ms to ~200ms** and DB load by **40%** with Redis caching and RabbitMQ
- Recovered **$2K+ monthly revenue** with idempotent payment webhooks and dead-letter queues
- Reduced MTTD from **~2 hours to under 15 minutes** with CloudWatch, X-Ray, and incident runbooks

## 🏅 Certifications

![AWS SAA](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS CCP](https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![CSM](https://img.shields.io/badge/Scrum_Alliance-Certified_ScrumMaster-009FDA?style=for-the-badge&logo=scrumalliance&logoColor=white)

## 🤝 Let's Connect

I'm open to **full-time AI / ML Engineering and Backend opportunities** and happy to talk about:

- RAG and retrieval system design
- LLM agents and tool use (LangGraph, MCP)
- Real-time and streaming AI services
- Deploying and scaling AI in production

📧 **Email:** [sanketkusa@gmail.com](mailto:sanketkusa@gmail.com)

---

<p align="center"><i>"Building AI systems that work in production, not just in notebooks."</i></p>
