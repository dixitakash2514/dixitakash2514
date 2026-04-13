<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=30&duration=3000&pause=1000&color=2E75B6&center=true&vCenter=true&width=700&height=60&lines=Principal+Data+Scientist;GenAI+%26+LLM+Platform+Architect;Building+Multi-Agent+Systems+at+Scale;15%2B+Years+Shipping+AI+to+Production" alt="Typing SVG" />
</p>

<h1 align="center">Hey, I'm Akash Dixit</h1>

<p align="center">
  <a href="https://linkedin.com/in/akash-dixit-187a1a18"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:akashdixit09@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.credly.com/badges/6d6c8ea4-1374-4604-8477-758e3767eebb/public_url"><img src="https://img.shields.io/badge/AWS_Solutions_Architect-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" /></a>
  <a href="https://www.mckinsey.com/capabilities/tech-and-ai/how-we-help-clients/rewiring-the-way-mckinsey-works-with-lilli"><img src="https://img.shields.io/badge/McKinsey_Lilli_Platform-003A70?style=for-the-badge&logo=mckinsey&logoColor=white" /></a>
</p>

---

```yaml
name: Akash Dixit
role: Principal Data Scientist | GenAI & ML Platform Architect
location: New Delhi, India
experience: 15+ years
current: AI Architect @ Thoughtworks
previous: Principal Data Scientist @ McKinsey & Company (QuantumBlack)
speaker: Cypher 2025 (India's largest AI summit) | Thoughtworks XConf
mentor: Former Data Science Mentor @ UpGrad
education: MBA (Finance & Operations) | B.Tech (ECE)
```

---

<h3><img src="https://img.shields.io/badge/-What_I_Build-2E75B6?style=flat-square" height="24" /></h3>

I architect and ship **production-grade AI systems** — from custom LLM training pipelines to multi-agent orchestration platforms serving global enterprises. I don't just build models; I build the **platforms, pipelines, and operational frameworks** that make AI work at scale.

**Two flagship platforms define my career:**

**McKinsey Lilli** — Architected the firm-wide Gen-AI platform spanning 20+ use cases across 60+ global clients. Multi-stage RAG with hybrid search (BM25 + vector, RRF fusion, cross-encoder re-ranking), multi-layer hallucination defence (RAGAS faithfulness scoring, NeMo Guardrails, citation verification), LLMOps with automated evaluation in CI/CD. Led a team of 22.

**Enterprise AI Platform @ Thoughtworks** — Leading AI platform development for a Fortune Global 50 retailer, serving 330K+ employees. Multi-agent supply chain workflows (LangGraph), GenAI-driven COBOL-to-Java legacy modernization via agentic code understanding, and centralized AI governance.

---

<h3><img src="https://img.shields.io/badge/-Technical_Depth-2E75B6?style=flat-square" height="24" /></h3>

<details>
<summary><b>GenAI & LLM Systems (click to expand)</b></summary>
<br>

| Area | Technologies & Techniques |
|------|--------------------------|
| **LLM Training & Fine-Tuning** | LoRA/QLoRA via Unsloth + TRL, DPO/SFT/RLHF alignment, custom Ollama modelfiles with RoPE-scaled context windows (8K to 32K), domain-specific model creation |
| **RAG Architecture** | Multi-stage retrieval (hybrid BM25+vector, RRF fusion), cross-encoder re-ranking, Corrective RAG (CRAG), Agentic RAG, KG-augmented retrieval, query transformation (HyDE, decomposition) |
| **Multi-Agent Systems** | LangGraph (supervisor/hierarchical patterns), MCP server/client (JSON-RPC 2.0), A2A protocol (Agent Cards), ReAct & Plan-and-Execute patterns, circuit breakers, idempotency, state checkpointing |
| **LLM Evaluation** | RAGAS (Faithfulness, Context Precision/Recall, Answer Relevancy), DeepEval in CI/CD, G-Eval, LLM-as-Judge, Recall@K, Precision@K, MRR |
| **Hallucination Defence** | Multi-layer grounding (faithfulness scoring, grounding verification, output guardrails, citation verification, confidence thresholds) |
| **LLM Serving** | vLLM (PagedAttention), SGLang (RadixAttention), speculative decoding, continuous batching, INT4/INT8/FP8 quantization |
| **Cost Optimization** | Semantic caching (Redis), model routing (45% savings), prompt compression, PTU provisioning, token budget management |
| **Observability** | LangFuse, Arize Phoenix, DeepEval — trace-level agent step visibility, token/cost tracking, semantic drift detection |
| **Guardrails & Governance** | NeMo Guardrails, LlamaGuard, Presidio PII protection, AI Red Teaming, prompt injection defence |

</details>

<details>
<summary><b>Classical ML, NLP & Recommendation Engines (click to expand)</b></summary>
<br>

| Project | Technique | Impact |
|---------|-----------|--------|
| **Real-time Flight Recommendations** | Gradient-boosted ranking model, streaming feature computation via Kafka/Flink | <90ms P95 inference, millions of data points/min |
| **Demand Forecasting (CPG)** | Prophet + XGBoost ensemble, multi-SKU optimization | Reduced wastage, expiry, and low-demand errors |
| **Intelligent Email Routing** | Text classification (NLP) on AWS EKS, 8-class routing | 96% accuracy, 3 hrs saved/resource/day |
| **Custom Embeddings for Insurance** | Domain-specific embedding training for accounts payable | 3X faster similarity search on claims |
| **Catastrophe Detection** | Deep learning on satellite imagery, transfer learning (ResNet) | Real-time fraud prevention, saving millions |
| **Sentiment Analysis (Insurance)** | NLP pipeline across multiple dimensions | 3.5X revenue increase over 8 months |
| **Workforce Attrition Prediction** | Predictive model (3-month & 6-month windows) | Early HR intervention, reduced project delays |
| **Document Intelligence** | Entity extraction from vendor PDFs + emails | 12 hours/day saved for 20+ resources |

</details>

<details>
<summary><b>Agentic AI & Reinforcement Learning Environments (click to expand)</b></summary>
<br>

- **Agentic Execution Environments for Supply Chain** — Designing RL training environments with custom graders, action spaces (order quantities, depot selection, route assignment), reward policies (minimize sales loss x maximize truck utilization), and trajectory-based feedback loops for fine-tuning agent behavior against business KPIs
- **Custom MCP Servers for OR Algorithms** — Wrapping operational research solvers (vehicle routing via OR-Tools, picking sequence optimization, bin packing) as typed MCP tools (JSON-RPC 2.0) for agent consumption
- **Custom LLM Configurations** — Building Ollama modelfiles with RoPE-scaled extended context windows, fine-tuning domain models using Unsloth + TRL (QLoRA on Llama-3, DPO preference alignment) for specialized supply chain reasoning
- **Microsoft Collaboration** — Live speech-to-speech transcription system development

</details>

---

<h3><img src="https://img.shields.io/badge/-Tech_Stack-2E75B6?style=flat-square" height="24" /></h3>

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-2E75B6?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-191919?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![Weaviate](https://img.shields.io/badge/Weaviate-6F2DA8?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-FF6B35?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)
![Unsloth](https://img.shields.io/badge/Unsloth-7C3AED?style=flat-square)

</p>

---

<h3><img src="https://img.shields.io/badge/-Certifications,_Speaking_&_Achievements-2E75B6?style=flat-square" height="24" /></h3>

| | |
|---|---|
| **AWS Certified Solutions Architect** | [Verify on Credly](https://www.credly.com/badges/6d6c8ea4-1374-4604-8477-758e3767eebb/public_url) |
| **Speaker — Cypher 2025** | [India's largest AI summit — GenAI-driven legacy modernization](https://www.linkedin.com/feed/update/urn:li:activity:7376201524345090048/) |
| **Speaker — XConf** | Thoughtworks flagship tech conference — Legacy modernization with GenAI |
| **Top 3 — McKinsey Internal Hackathon** | ML solution for slide recommendation |
| **Top 2% — MachineHack Hackathon** | Used cars price prediction challenge |
| **Top 4% — Analytics Vidhya Hackathon** | Health insurance cross-sell recommendation |
| **Data Science Mentor — UpGrad** | Mentored working professionals on ML/AI career paths |

---

<h3><img src="https://img.shields.io/badge/-What_I'm_Working_On-2E75B6?style=flat-square" height="24" /></h3>

- Building **Agentic Execution Environments** with RL-based fine-tuning for supply chain agents
- Creating **custom MCP servers** wrapping OR algorithms (vehicle routing, picking optimization) for agent consumption
- Fine-tuning **domain-specific LLMs** using Unsloth + TRL with RoPE-scaled context windows
- Building a **local RAG benchmarking system** to measure the performance impact of each architectural layer
- Exploring **A2A protocol** for cross-organization agent interoperability

---

<p align="center">
  <i>"I don't just build models — I build the platforms, pipelines, and operational frameworks that make AI work at scale."</i>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=dixitakash2514&color=2E75B6&style=flat-square&label=Profile+Views" />
</p>
