# Harsh Rajendra Mankar
### Applied Machine Learning & Forward Deployed AI Engineer

---

## Technical Overview
I am an Applied Machine Learning and Forward Deployed Engineer specializing in production-grade AI infrastructure, LLM-agent orchestration, and classical fraud/risk modeling. I focus on building high-performance, asynchronous systems that integrate deeply with legacy enterprise backends (ERPs, CRMs) to reduce operational latency and drive measurable ROI. My core expertise spans from deploying deterministic multi-agent workflows with strict safety guardrails to engineering mathematically rigorous predictive pipelines for high-stakes financial and ad-tech environments.

---

## Selected Technical Projects

### Application Pilot — Multi-Model Job-Search Triage & Auto-Apply Agent (RPA)
- Engineered a cost-optimized multi-model pipeline routing bulk triage through DeepSeek V4 Pro — applying zero-tolerance visa/clearance/seniority filters, classifying roles into three targeted resume tracks, and scoring 1–10 before handing top matches to Claude Sonnet 4.6 for high-value prefill.
- Built an ATS-resolution layer with ScrapeGraphAI + DeepSeek V4 Flash that converts aggregator/redirect links (ZipRecruiter, Indeed) into direct application URLs (Greenhouse, Lever, Workday, Ashby), backed by a regex fast-path to skip the headless browser when possible.
- Automated Indeed Easy Apply via Playwright with a hard human-in-the-loop guardrail that pauses on any screening question not derivable from the resume — never fabricating personal information.
- Added a SQLite dedup tracker that drops already-applied (company, title) pairs before any LLM call, eliminating wasted API tokens and logging every submission with status, domain, and resume used.

### Enterprise Multi-Agent Orchestration & ERP Integration
- Spearheaded an asynchronous multi-agent orchestration engine handling incoming CRM queues via FastAPI webhooks on Railway.
- Routed workflows through OpenAI GPT-4o with LangSmith tracing and agent safety guardrails to securely automate dynamic NetSuite address updates, order cancellations, and real-time tracking retrievals.
- Optimized accounting operations by deploying GCP-hosted backend pipelines integrating NetSuite APIs, automating financial reconciliation and PDF invoice extraction to flag billing discrepancies and eliminate manual entry.

### Multimodal GenAI & Retail Media ML Pipelines
- Deployed a LangChain-orchestrated Flask/Streamlit pipeline integrating Claude 4.6 Opus and Gemini Veo 3 APIs, analyzing historical campaign databases and applying LLM-as-judge evals to continuously generate high-converting multimodal creatives.
- Orchestrated an ML pipeline processing 3.4M retail records, utilizing GMM clustering and Ollama Qwen-14B product embeddings indexed in pgvector.
- Optimized Real-Time Bidding (RTB) and CTR/CVR prediction, immediately halting ad-spend on discontinued SKUs and surfacing unadvertised inventory matching high-ROAS bestseller profiles.

### Financial Fraud Detection & Transaction Monitoring
- Architected an end-to-end transaction monitoring pipeline on 780K+ Capital One records, executing rigorous feature engineering and applying SMOTE to counter severe class imbalance.
- Trained XGBoost and CatBoost classifiers optimized for real-time scoring, maximizing AUC-ROC and achieving 94% recall through precision-recall curve analysis and threshold tuning.
- Simulated production model monitoring environments to track concept drift across 15+ performance metrics, validating via time-based splits for production realism.

### GridLLM: Agentic AI for Electricity Market Operations
- Developed a LangGraph multi-agent orchestration system to navigate California Independent System Operator (CAISO) regulations, implementing Model Context Protocol (MCP) for consistent state synchronization across coordinated agents.
- Fine-tuned foundation model LLaMA 3.2-3B via Domain-Adaptive Pre-Training on 400 electricity PDFs plus instruction tuning on 2K market samples using QLoRA.
- Mined 2+ years of time-series data via association rule mining, validated through RAGAS evaluations and LangSmith to monitor response quality and cost-per-call.

---

## Core Competencies

- **Programming:** Python (Pandas, NumPy, PyTorch), SQL (PostgreSQL), Go, TypeScript / JavaScript.
- **LLM & Agentic AI:** LangGraph, LangChain, Multi-Agent Orchestration, Model Context Protocol (MCP), RAG Pipelines, Vector Databases (Pinecone, pgvector), QLoRA Fine-Tuning.
- **LLM Ops & Evaluation:** LLM-as-Judge, RAGAS, LangSmith Tracing, Telemetry/Observability, Agent Guardrails & Safety Constraints.
- **Engineering & Cloud:** Terraform (IaC), Airflow, dbt, FastAPI, Webhooks, AWS (EC2, S3), GCP, Docker, CI/CD.
- **ML & Fraud Modeling:** XGBoost, CatBoost, GMM Clustering, SMOTE, AUC-ROC, Precision-Recall Curves, Real-Time Model Monitoring.

---

## Professional Links
- [Technical Portfolio](https://hmankar01.github.io/LLM-Portfolio/Portfolio.pdf)
- [LinkedIn Profile](https://linkedin.com/in/hmankar01)

---
*Newark, NJ (NYC Metro Area)*
