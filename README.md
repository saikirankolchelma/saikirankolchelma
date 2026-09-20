<h1 align="left">Kolchelma Sai Kiran</h1>

<p align="left">
  <strong>AI/ML Engineer — Generative AI & Agentic Systems</strong><br/>
  Hyderabad, India
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/ksaikiran129/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:Ksaikiran129@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I build enterprise Generative AI, agentic and RAG systems — currently as an **ML Associate at Avira Digital Technologies**, working on an internal agentic AI platform and client retrieval systems in the pharmaceutical domain.

Most of what I work on sits in the unglamorous middle of an AI system: agent orchestration, tool protocols, retrieval that holds up when the answer lives between records rather than inside one, safety guardrails, and the evaluation harnesses that tell you whether any of it actually improved.

---

### What I'm working on

**Enterprise agentic platform** — a provider-agnostic LLM gateway across OpenAI, IBM watsonx and Meta Llama; MCP servers over SSE and stdio so tool access is standardised; short-term, long-term and episodic agent memory; input/output guardrails for PII/PHI, jailbreaks, bias and prompt injection; and an LLM-as-judge harness scoring responses against a labelled dataset.

**Clinical knowledge graph RAG** — started as metadata-aware hybrid retrieval (dense + BM25) over clinical trial, drug and disease data. It worked for lookups and failed on relationship questions, because many-to-many drug–disease–dosage links do not survive chunking. Redesigned around Neo4j with agent-driven natural-language-to-Cypher and NL-to-Gremlin translation.

**Agentic data structuring** — 10+ specialised LangGraph agents under an orchestrator, handling sentiment analysis, thematic clustering and entity extraction, with MCP schema-introspection tools so downstream agents generate SQL against the live schema rather than a stale snapshot.

**Meta-RAG** *(self-directed)* — an adaptive inference gateway that routes queries by complexity. A fine-tuned DeBERTa-v3 classifier drives a three-tier dispatcher across naive, parent-document and HyDE retrieval; an LLM judge scores strategies in shadow mode off the serving path, and Optuna tunes the routing thresholds against an accuracy SLA.

---

### Tech

**Languages** &nbsp;Python · SQL

**Generative AI** &nbsp;LangGraph · LangChain · CrewAI · MCP · Multi-Agent Orchestration · RAG · Graph RAG · LLM Evaluation · Guardrails

**Machine Learning** &nbsp;PyTorch · Transformers · Scikit-learn · TensorFlow · Deep Learning · NLP · Computer Vision · LLM Fine-Tuning

**Data & Retrieval** &nbsp;Neo4j · AWS Neptune · Cypher · Gremlin · PostgreSQL · MySQL · Qdrant · FAISS · Pinecone · BM25 · Hybrid Search

**Backend & Cloud** &nbsp;FastAPI · Docker · AWS (EC2, S3, SageMaker, Bedrock) · Redis · MLflow · Optuna · Git

**Data & BI** &nbsp;NumPy · Pandas · Matplotlib · Power BI · Streamlit

---

### Currently exploring

Agent reliability — planning, memory, and what happens when a tool call fails. Retrieval past the naive baseline. Evaluation infrastructure, because it is the part that compounds. Cost and latency as design constraints rather than afterthoughts.

---

### Background

**B.Tech, Computer Science** (Data Science specialisation) — TKR College of Engineering and Technology, 2021–2024

NPTEL certifications from IIT Madras and IIT Guwahati · 1st place, AIML EduNext Hackathon

---

**Open to selected freelance AI/ML projects** — RAG systems, AI agents, MCP tool servers, natural-language-to-SQL, guardrails and LLM evaluation.

📧 [Ksaikiran129@gmail.com](mailto:Ksaikiran129@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/ksaikiran129/)
