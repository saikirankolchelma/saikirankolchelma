<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7C8CFF,100:22D3EE&height=180&section=header&text=Kolchelma%20Sai%20Kiran&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%2FML%20Engineer%20%7C%20Generative%20AI%20%26%20Agentic%20Systems&descAlignY=55&descSize=18" alt="Kolchelma Sai Kiran — AI/ML Engineer" />

<div align="center">

<a href="https://github.com/saikirankolchelma">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=7C8CFF&center=true&vCenter=true&width=700&lines=Building+agents+that+survive+contact+with+real+tools;Retrieval+that+works+when+the+answer+lives+between+records;Guardrails%2C+evaluation%2C+and+the+parts+nobody+demos" alt="Typing SVG" />
</a>

<br/>

<a href="https://saikiran-kolchelma-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-7C8CFF?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/ksaikiran129/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:Ksaikiran129@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/Hyderabad,%20India-1F2937?style=for-the-badge&logo=googlemaps&logoColor=7C8CFF" alt="Hyderabad, India" />
<img src="https://img.shields.io/badge/Open%20to%20Freelance-10B981?style=for-the-badge&logo=handshake&logoColor=white" alt="Open to freelance" />

</div>

---

## 🧠 About

```python
class SaiKiran:
    role      = "ML Associate @ Avira Digital Technologies"
    focus     = ["Agentic AI", "Graph RAG", "LLM Evaluation", "Guardrails"]
    domain    = ["Pharmaceutical", "Business Intelligence"]
    obsession = "the unglamorous middle of an AI system"
```

I build enterprise **Generative AI, agentic and RAG systems** — currently on an internal agentic platform and client retrieval systems in the pharmaceutical domain.

Most of my work sits where the demos stop: agent orchestration, tool protocols, retrieval that holds up when the answer lives *between* records rather than inside one, safety guardrails, and the evaluation harnesses that tell you whether anything actually improved. 🔍

---

## 🚀 What I'm building

<sub>📖 Full architecture breakdowns for each of these → **[saikiran-kolchelma-portfolio.vercel.app/projects](https://saikiran-kolchelma-portfolio.vercel.app/projects)**</sub>

### 🏗️ &nbsp;Enterprise Agentic Platform
A **provider-agnostic LLM gateway** across OpenAI, IBM watsonx and Meta Llama — model choice becomes configuration, not a rewrite. **MCP servers** over SSE and stdio so every agent reaches tools the same way. **Three-tier agent memory** (short-term, long-term, episodic). **Guardrails** for PII/PHI, jailbreaks, bias and prompt injection. And an **LLM-as-judge harness** scoring responses against a labelled set, because *"the agent got better"* is otherwise just an opinion.

### 🧬 &nbsp;Clinical Knowledge Graph RAG
Started as metadata-aware hybrid retrieval — dense vectors **+** BM25 — over clinical trial, drug and disease data. It nailed lookups and **failed on relationship questions**, because many-to-many drug–disease–dosage links don't survive chunking. Redesigned around **Neo4j**, with agent-driven **NL→Cypher** and **NL→Gremlin** translation so researchers never write query syntax.

### 🕸️ &nbsp;Agentic Data Structuring
**10+ specialised LangGraph agents** under an orchestrator — sentiment analysis, thematic clustering, entity extraction — each with one job and its own failure mode. **MCP schema-introspection tools** let downstream agents generate SQL against the *live* schema instead of a stale snapshot. 🎯

### ⚡ &nbsp;Meta-RAG — Adaptive Routing Gateway &nbsp;`self-directed`
Not every query deserves the biggest model. A **fine-tuned DeBERTa-v3** complexity classifier drives a **three-tier dispatcher** across naive, parent-document and HyDE retrieval. An **LLM judge** scores strategies in shadow mode — off the serving path, so evaluation never costs latency — and **Optuna** tunes the routing thresholds against an accuracy SLA. 💸

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,fastapi,flask&theme=dark" alt="Python, PyTorch, TensorFlow, scikit-learn, FastAPI, Flask" />
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,docker,aws,git&theme=dark" alt="PostgreSQL, MySQL, Redis, Docker, AWS, Git" />

</div>

<br/>

**🤖 Generative AI & Agents**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A5F?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-7C8CFF?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-22D3EE?style=flat-square)
![Graph RAG](https://img.shields.io/badge/Graph%20RAG-22D3EE?style=flat-square)
![Guardrails](https://img.shields.io/badge/Guardrails-EF4444?style=flat-square)
![LLM Evaluation](https://img.shields.io/badge/LLM%20Evaluation-8B5CF6?style=flat-square)
![Fine-Tuning](https://img.shields.io/badge/LLM%20Fine--Tuning-8B5CF6?style=flat-square)

**🔎 Retrieval & Graphs**

![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![AWS Neptune](https://img.shields.io/badge/AWS%20Neptune-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Cypher](https://img.shields.io/badge/Cypher-4581C3?style=flat-square)
![Gremlin](https://img.shields.io/badge/Gremlin-232F3E?style=flat-square&logo=apache&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![BM25](https://img.shields.io/badge/BM25-6B7280?style=flat-square)
![Hybrid Search](https://img.shields.io/badge/Hybrid%20Search-6B7280?style=flat-square)

**⚙️ ML, Data & Ops**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=flat-square&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-2E5C8A?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

---

## 🔬 Currently exploring

> 🧩 **Agent reliability** — planning, memory, and what actually happens when a tool call fails
>
> 🎯 **Retrieval past the naive baseline** — where chunk similarity stops being enough
>
> 📊 **Evaluation infrastructure** — because it's the part that compounds
>
> 💰 **Cost and latency as design constraints** — not afterthoughts

---

## 🎓 Background

🏫 &nbsp;**B.Tech, Computer Science** — Data Science specialisation
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;TKR College of Engineering and Technology · 2021 – 2024

📜 &nbsp;**NPTEL** — Data Science for Engineering *(IIT Madras)* · ML & Deep Learning Fundamentals *(IIT Guwahati)*

🏆 &nbsp;**1st Rank** — AIML EduNext Hackathon

---

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=saikirankolchelma&theme=tokyonight&hide_border=true&background=0D1117&stroke=1D2230&ring=7C8CFF&fire=22D3EE&currStreakLabel=7C8CFF" alt="GitHub streak" />

</div>

---

<div align="center">

### 💼 Open to selected freelance AI/ML projects

**RAG systems** · **AI agents** · **MCP tool servers** · **Natural-language-to-SQL** · **Guardrails** · **LLM evaluation**

<a href="https://saikiran-kolchelma-portfolio.vercel.app/freelance"><img src="https://img.shields.io/badge/View%20Services-7C8CFF?style=for-the-badge&logo=vercel&logoColor=white" alt="Freelance services" /></a>
<a href="mailto:Ksaikiran129@gmail.com"><img src="https://img.shields.io/badge/Let's%20talk-10B981?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Let's talk" /></a>

<br/><br/>

*⚡ Ask me about agent memory, graph retrieval, or why your RAG fails on comparative questions.*

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:22D3EE,100:7C8CFF&height=120&section=footer" alt="" />
