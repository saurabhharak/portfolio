---
layout: default
title: AI & GenAI Projects
description: Enterprise RAG platforms, LLM evaluation systems, and agentic AI
---

<div class="project-grid">

  <div class="project-card project-card--featured">
    <div class="project-card__header">
      <span class="featured-badge">Enterprise</span>
      <h3>Mila Chat — Multi-Tenant Enterprise RAG Platform</h3>
      <p class="project-card__subtitle">TechnoMile | Production System</p>
    </div>
    <p class="project-card__desc">Core AI engineer on a multi-tenant GenAI platform supporting federal enterprise clients across document intelligence and conversational AI use cases, deployed on Kubernetes with horizontal pod scaling. Designed production-grade retrieval and ingestion architecture using Azure OpenAI, Azure Document Intelligence, PostgreSQL, Qdrant, and S3, with asynchronous orchestration through AWS SQS and Step Functions.</p>
    <p class="project-card__desc">Implemented strict multi-tenant isolation at every layer — database queries filtered by client/org/user IDs with compound indexes, Qdrant metadata filters on all vector searches, and conversation context scoped per tenant. Architected the chat pipeline with parallel RAG + Text2SQL execution, singleton-cached clients for throughput, and per-interaction cost tracking.</p>
    <div class="project-card__metrics">
      <div class="metric">
        <span class="metric__value">3s</span>
        <span class="metric__label">p95 Latency</span>
      </div>
      <div class="metric">
        <span class="metric__value">$0.015</span>
        <span class="metric__label">Per Question</span>
      </div>
    </div>
    <div class="project-card__tech">
      <span class="tech-badge">Azure OpenAI</span>
      <span class="tech-badge">Qdrant</span>
      <span class="tech-badge">PostgreSQL</span>
      <span class="tech-badge">AWS SQS</span>
      <span class="tech-badge">Step Functions</span>
      <span class="tech-badge">Kubernetes</span>
      <span class="tech-badge">Azure Doc Intelligence</span>
      <span class="tech-badge">asyncio</span>
    </div>
  </div>

  <div class="project-card project-card--featured">
    <div class="project-card__header">
      <span class="featured-badge">Sole Architect</span>
      <h3>Unified AI Evaluation Platform</h3>
      <p class="project-card__subtitle">TechnoMile | LLM-as-Judge Evaluation System</p>
    </div>
    <p class="project-card__desc">Sole architect and developer of a multi-paradigm AI evaluation platform that consolidated 3 independent evaluation codebases (~3,000+ lines of duplicated, untestable code) into a single YAML-configurable system evaluating 3 enterprise AI products (Mila Chat, Transform Copilot, NoticesIQ). Reduced new product onboarding from 2-3 weeks and 1,200+ lines of Python to under 4 hours and zero code.</p>
    <p class="project-card__desc">Designed a pluggable LLM-as-Judge evaluation engine using Azure OpenAI (GPT-4.1) with versioned Jinja2 prompt templates, evaluating across 5 LLM-based metrics (Semantic Correctness, Completeness, Faithfulness, Relevancy, Clarity) and 3 deterministic metrics (F1/Precision/Recall). Fully integrated into Azure Pipelines CI/CD with regression gating. Built a 7-page Streamlit/Plotly evaluation dashboard with run explorer and cross-product metric comparison.</p>
    <div class="project-card__metrics">
      <div class="metric">
        <span class="metric__value">4hrs</span>
        <span class="metric__label">Onboarding (was 3 wks)</span>
      </div>
      <div class="metric">
        <span class="metric__value">80%+</span>
        <span class="metric__label">Test Coverage (from 0%)</span>
      </div>
      <div class="metric">
        <span class="metric__value">70%</span>
        <span class="metric__label">Effort Reduction</span>
      </div>
      <div class="metric">
        <span class="metric__value">8</span>
        <span class="metric__label">Eval Metrics</span>
      </div>
    </div>
    <div class="project-card__tech">
      <span class="tech-badge">GPT-4.1</span>
      <span class="tech-badge">LLM-as-Judge</span>
      <span class="tech-badge">Jinja2</span>
      <span class="tech-badge">YAML</span>
      <span class="tech-badge">Streamlit</span>
      <span class="tech-badge">Plotly</span>
      <span class="tech-badge">PostgreSQL/JSONB</span>
      <span class="tech-badge">Azure Pipelines</span>
      <span class="tech-badge">Pytest</span>
    </div>
  </div>

  <div class="project-card project-card--featured">
    <div class="project-card__header">
      <span class="featured-badge">Open Source</span>
      <h3>Creator GraphRAG</h3>
      <p class="project-card__subtitle">Multilingual Book-to-Video Knowledge System</p>
    </div>
    <p class="project-card__desc">Production-grade system that ingests multilingual books (Marathi, Hindi, English) via Sarvam AI OCR, builds a Knowledge Graph (Neo4j) + Vector Store (Qdrant), and generates citation-enforced video content packages. Hybrid retrieval combining Neo4j graph traversal with Qdrant vector similarity search using 4,096-dimensional embeddings via Qwen3-Embedding-8B.</p>
    <div class="project-card__metrics">
      <div class="metric">
        <span class="metric__value">71/71</span>
        <span class="metric__label">Tests Passing</span>
      </div>
      <div class="metric">
        <span class="metric__value">5,654</span>
        <span class="metric__label">Concept Nodes</span>
      </div>
      <div class="metric">
        <span class="metric__value">973</span>
        <span class="metric__label">Indexed Chunks</span>
      </div>
    </div>
    <div class="project-card__tech">
      <span class="tech-badge">FastAPI</span>
      <span class="tech-badge">Neo4j 5</span>
      <span class="tech-badge">Qdrant</span>
      <span class="tech-badge">React 19</span>
      <span class="tech-badge">Celery</span>
      <span class="tech-badge">PostgreSQL</span>
      <span class="tech-badge">MinIO</span>
      <span class="tech-badge">OpenTelemetry</span>
      <span class="tech-badge">JWT RS256</span>
    </div>
    <div class="project-card__links">
      <a href="https://github.com/saurabhharak/creator-graphrag" target="_blank" rel="noopener"><i class="fab fa-github" aria-hidden="true"></i> View on GitHub</a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card__header">
      <h3>LLM Fine-Tuning Pipeline</h3>
      <p class="project-card__subtitle">LoRA/PEFT for Llama2 & Llama3</p>
    </div>
    <p class="project-card__desc">End-to-end LoRA fine-tuning pipeline for Llama2 (7B) and Llama3 using HuggingFace Transformers and PEFT. Improved domain-specific task accuracy by 20% with substantially reduced compute cost vs full fine-tuning. Includes configurable training datasets, domain evaluation scripts, and GGUF export for local inference.</p>
    <div class="project-card__metrics">
      <div class="metric">
        <span class="metric__value">20%</span>
        <span class="metric__label">Accuracy Improvement</span>
      </div>
    </div>
    <div class="project-card__tech">
      <span class="tech-badge">Llama2/3</span>
      <span class="tech-badge">LoRA</span>
      <span class="tech-badge">PEFT</span>
      <span class="tech-badge">HuggingFace</span>
      <span class="tech-badge">GGUF</span>
      <span class="tech-badge">Cloud GPU</span>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card__header">
      <h3>Intelligent Document Query Bot</h3>
      <p class="project-card__subtitle">Microsoft Teams RAG Bot</p>
    </div>
    <p class="project-card__desc">Intelligent bot for Microsoft Teams that uses advanced language models and document retrieval to provide context-aware answers from enterprise documents. Built with Bot Builder Library and Azure Bot Services, with FastAPI backend interfacing with OpenAI and LangChain for optimized retrieval. Integrated ChromaDB for efficient document vector storage.</p>
    <div class="project-card__tech">
      <span class="tech-badge">OpenAI</span>
      <span class="tech-badge">LangChain</span>
      <span class="tech-badge">ChromaDB</span>
      <span class="tech-badge">FastAPI</span>
      <span class="tech-badge">Azure Bot Services</span>
      <span class="tech-badge">MS Teams</span>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card__header">
      <h3>Commercial LLM Fine-Tuning</h3>
      <p class="project-card__subtitle">OpenAI Davinci & GPT-3.5 Turbo</p>
    </div>
    <p class="project-card__desc">Fine-tuned OpenAI models (Davinci-002, GPT-3.5 Turbo) for domain-specific conversational support using the OpenAI Fine-Tuning API. Built multi-turn conversation data preparation pipelines, evaluation harnesses using scikit-learn metrics, and deployed interactive Streamlit chat applications for real-time inference.</p>
    <div class="project-card__tech">
      <span class="tech-badge">GPT-3.5 Turbo</span>
      <span class="tech-badge">Davinci-002</span>
      <span class="tech-badge">OpenAI Fine-Tuning API</span>
      <span class="tech-badge">Streamlit</span>
      <span class="tech-badge">scikit-learn</span>
    </div>
  </div>

</div>
