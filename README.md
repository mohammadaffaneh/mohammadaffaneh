<p align="center">
  <img src="https://img.shields.io/badge/Production%20AI%20Systems-FF6B6B?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Multi--Agent%20Orchestration-4ECDC4?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/LLM%20Evaluation%20%26%20Safety-45B7D1?style=for-the-badge&logo=openai&logoColor=white" />
</p>

---

## Building Enterprise AI That Ships

I build **production-grade AI systems** that handle +100K of documents, serve real-time agentic workflows, and survive the transition from notebook to production deployment. My focus: making LLMs reliable enough for enterprises processes.

### What I Solve

**Problem**: Most AI prototypes collapse under production load—inconsistent outputs, ungoverned costs, no observability.  
**My Approach**: Treat LLMs as unreliable components requiring:
- **Structured validation**: Pydantic-enforced schemas, function calling, deterministic post-processing
- **Rigorous evaluation**: Task-grounded metrics (factuality, grounding, latency P90), A/B tests with stat-sig guardrails
- **Production hygiene**: Versioned and optimized prompts/datasets, traces with lineage, cost-per-call monitoring, automated regression tests

---

## Core Capabilities

### **Cloud-Native AI Infrastructure**
Design and deploy secure, cost-aware GenAI systems on **Bedrock/SageMaker** / **Antrhopic** / **OpenAI**. Build hybrid search pipelines combining vector stores (OpenSearch/Pinecone) with keyword ranking, served through async FastAPI endpoints with sub-200ms P95 latency.

### **Multi-Agent Systems in Production**
Orchestrate LangGraph agents or Claude Agent SDK handling parallel tool calls, state checkpointing, and human-in-the-loop interventions. Frontend clients consume SSE streams with proper backpressure handling.

### **LLM Evaluation & Safety**
Own the metrics: pairwise win-rate evals, factuality checks against ground truth. Track cost-per-call, latency, and output quality. SageMaker Experiments/MLflow for versioning.

### **Data Pipelines at Scale**
ETL workflows processing millions of unstructured documents (PDFs/DOCX/emails) through batch AI extraction jobs on SageMaker or Spark/Databricks, loading into PostgreSQL/S3 with schema evolution and backfill strategies. Orchestrate with Airflow/Step Functions; monitor data quality drift.

### **Backend Engineering Discipline**
Production Python services with strong typing, async I/O, comprehensive pytest suites, CI/CD (GitHub Actions/Jenkins), Docker/K8s deployments. Structured logging, OpenTelemetry traces, IaC with CDK/Terraform for reproducible environments.

---

## Tech Stack


- **Daily Drivers**: Python · FastAPI · AWS (Bedrock, DynamoDB, SageMaker, Lambda, EKS, S3) 
- **AI**: Claude Models · Claude Agents SDK · OpenAI · LangChain/LangGraph · Pydantic · Sentence Transformers  
- **Search & Data**: OpenSearch/Elasticsearch · Databricks/Spark · PostgreSQL · Redis · SQL
- **Observability**:  ·Customized Logs · Dashboards · MLflow · OpenTelemetry
- **IaC & Ops**: · Docker  · Kubernetes · Terraform · GitHub Actions

---

## Differentiators

**Evaluation-First Development**: Every AI feature ships with quantitative evals and regression tests—no "vibes-based" deployments  
**Cost-Aware Architecture**: Design for $/request, not just accuracy; implement caching, prompt compression, model routing  
**Reproducibility by Default**: Versioned prompts, deterministic seeds, one-command environment setup  

---

##  Let's Connect

Building something that needs to go from POC to production without the usual AI deployment failures? Let's talk architecture trade-offs.

<p align="center">
  <a href="https://linkedin.com/in/mohammad-affaneh">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>
