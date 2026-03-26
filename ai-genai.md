---
layout: default
title: AI & GenAI Projects
description: Production-grade RAG platforms, AI evaluation systems, and agentic workflows for enterprise environments.
---

<p class="section__subtitle" style="margin-top: 0; margin-bottom: var(--space-8);">This section highlights my work across multi-tenant retrieval systems, evaluation infrastructure, and enterprise AI orchestration — with a focus on reliability, scalability, and measurable engineering impact.</p>

<div class="project-grid">

  <div class="project-card project-card--featured">
    <div class="project-card__header">
      <span class="featured-badge">Enterprise</span>
      <h3>Mila Chat — Multi-Tenant Enterprise RAG Platform</h3>
      <p class="project-card__subtitle">TechnoMile | Production System</p>
    </div>
    <p class="project-card__desc">Core AI engineer on a multi-tenant GenAI platform supporting federal enterprise use cases across document intelligence and conversational AI.</p>
    <p class="project-card__desc">Designed the production retrieval and ingestion architecture using Azure OpenAI, Azure Document Intelligence, PostgreSQL, Qdrant, and S3, with asynchronous orchestration via AWS SQS and Step Functions.</p>
    <p class="project-card__desc">Implemented strict tenant isolation across database queries, vector search filters, and conversation context to ensure client-safe retrieval.</p>
    <p class="project-card__desc">Architected the chat execution flow with parallel RAG + Text2SQL processing, singleton-cached clients for throughput, and per-interaction cost tracking for operational visibility.</p>
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
      <span class="tech-badge">S3</span>
      <span class="tech-badge">SQS</span>
      <span class="tech-badge">Step Functions</span>
      <span class="tech-badge">Multi-Tenant</span>
      <span class="tech-badge">RAG</span>
    </div>
  </div>

  <div class="project-card project-card--featured">
    <div class="project-card__header">
      <span class="featured-badge">Sole Architect</span>
      <h3>Unified AI Evaluation Platform — CI/CD Integrated LLM Evaluation System</h3>
      <p class="project-card__subtitle">TechnoMile | Sole Architect</p>
    </div>
    <p class="project-card__desc">Designed and built a centralized evaluation platform that consolidated three separate evaluation systems into one YAML-configurable framework for multiple enterprise AI products.</p>
    <p class="project-card__desc">Implemented LLM-as-Judge evaluation using Azure OpenAI across semantic correctness, completeness, faithfulness, relevancy, and clarity, alongside deterministic extraction metrics.</p>
    <p class="project-card__desc">Integrated evaluation runs into CI/CD pipelines for automated regression checks, improving evaluation reliability and reducing new product onboarding from weeks to hours.</p>
    <p class="project-card__desc">Built dashboard and storage workflows for evaluation tracking, comparison, and artifact management.</p>
    <div class="project-card__metrics">
      <div class="metric">
        <span class="metric__value">3</span>
        <span class="metric__label">Products Unified</span>
      </div>
      <div class="metric">
        <span class="metric__value">80%+</span>
        <span class="metric__label">Test Coverage</span>
      </div>
      <div class="metric">
        <span class="metric__value">3s</span>
        <span class="metric__label">p95 Latency</span>
      </div>
      <div class="metric">
        <span class="metric__value">$0.015</span>
        <span class="metric__label">Per Evaluation</span>
      </div>
    </div>
    <div class="project-card__tech">
      <span class="tech-badge">Azure OpenAI</span>
      <span class="tech-badge">FastAPI</span>
      <span class="tech-badge">PostgreSQL</span>
      <span class="tech-badge">Streamlit</span>
      <span class="tech-badge">CI/CD</span>
      <span class="tech-badge">YAML</span>
      <span class="tech-badge">Evaluation</span>
    </div>
  </div>

  <div class="project-card project-card--featured">
    <div class="project-card__header">
      <span class="featured-badge">Open Source</span>
      <h3>Creator GraphRAG</h3>
      <p class="project-card__subtitle">Multilingual Knowledge + Vector Retrieval System</p>
    </div>
    <p class="project-card__desc">Built a multilingual knowledge system that ingests books across Marathi, Hindi, and English via Sarvam AI OCR, extracts structured concepts into a Neo4j knowledge graph, and combines graph traversal with Qdrant vector similarity search using 4,096-dimensional embeddings for citation-aware content generation.</p>
    <p class="project-card__desc">Designed as a production-style system with FastAPI, PostgreSQL, Qdrant, Neo4j, async processing via Celery, and comprehensive integration testing.</p>
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
    <p class="project-card__desc">Built an end-to-end LoRA fine-tuning pipeline for Llama2 (7B) and Llama3 using HuggingFace Transformers and PEFT. Delivered 20% domain-specific accuracy improvement with substantially reduced compute cost versus full fine-tuning. Includes configurable training datasets, domain evaluation scripts, and GGUF export for local inference.</p>
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
    <p class="project-card__desc">Built a document retrieval bot for Microsoft Teams using OpenAI and LangChain for context-aware question answering over enterprise documents. Implemented FastAPI backend with ChromaDB vector storage and deployed via Azure Bot Services.</p>
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
    <p class="project-card__desc">Fine-tuned OpenAI models (Davinci-002, GPT-3.5 Turbo) for domain-specific conversational support. Built multi-turn conversation data preparation pipelines, evaluation harnesses using scikit-learn metrics, and deployed interactive Streamlit chat applications for inference.</p>
    <div class="project-card__tech">
      <span class="tech-badge">GPT-3.5 Turbo</span>
      <span class="tech-badge">Davinci-002</span>
      <span class="tech-badge">OpenAI Fine-Tuning API</span>
      <span class="tech-badge">Streamlit</span>
      <span class="tech-badge">scikit-learn</span>
    </div>
  </div>

</div>

<!-- Architecture Diagrams -->
<div class="section">
  <h2 class="section__title">Architecture Diagrams</h2>
  <p class="section__subtitle">System-level design thinking behind the featured projects</p>

  <div class="arch-grid">

    <div class="arch-card">
      <h3 class="arch-card__title">Mila Chat — Multi-Tenant RAG Architecture</h3>
      <p class="arch-card__desc">Multi-tenant enterprise retrieval architecture with tenant-scoped query execution, vector search, relational metadata, and async ingestion workflows.</p>

      <div class="arch-diagram">
        <div>
          <p class="arch-label">Query Path</p>
          <div class="arch-row">
            <span class="arch-node">User / Client</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node arch-node--primary">FastAPI Chat Service</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node arch-node--tertiary">Tenant Isolation Layer</span>
          </div>
          <div class="arch-row" style="margin-top: var(--space-3); padding-left: var(--space-8);">
            <div class="arch-group">
              <p class="arch-label" style="margin: 0;">Parallel Execution</p>
              <div class="arch-row">
                <span class="arch-node arch-node--primary">RAG Pipeline</span>
                <span class="arch-connector">|</span>
                <span class="arch-node arch-node--primary">Text2SQL Path</span>
              </div>
            </div>
          </div>
        </div>

        <div>
          <p class="arch-label">Data Layer</p>
          <div class="arch-row">
            <span class="arch-node arch-node--secondary">Qdrant</span>
            <span class="arch-node arch-node--secondary">PostgreSQL</span>
            <span class="arch-node arch-node--secondary">S3</span>
            <span class="arch-node">Azure OpenAI</span>
          </div>
        </div>

        <div>
          <p class="arch-label">Ingestion Path</p>
          <div class="arch-row">
            <span class="arch-node">Documents</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node">Azure Doc Intelligence</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node arch-node--tertiary">AWS SQS</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node arch-node--tertiary">Step Functions</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node arch-node--secondary">Qdrant + S3</span>
          </div>
        </div>
      </div>
    </div>

    <div class="arch-card">
      <h3 class="arch-card__title">Unified AI Evaluation Platform — Evaluation Flow</h3>
      <p class="arch-card__desc">Centralized LLM evaluation workflow with YAML-configured product adapters, judge-based metrics, deterministic metrics, CI/CD integration, and evaluation dashboards.</p>

      <div class="arch-diagram">
        <div>
          <p class="arch-label">Trigger</p>
          <div class="arch-row">
            <span class="arch-node">CI/CD Pipeline</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node arch-node--primary">YAML Config</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node arch-node--primary">Product Adapter</span>
          </div>
        </div>

        <div>
          <p class="arch-label">Evaluation Engine</p>
          <div class="arch-row">
            <span class="arch-node arch-node--primary">Evaluation Runner</span>
            <span class="arch-connector">&rarr;</span>
            <div class="arch-group">
              <p class="arch-label" style="margin: 0;">Metrics</p>
              <div class="arch-row">
                <span class="arch-node arch-node--tertiary">Azure OpenAI Judge</span>
                <span class="arch-connector">|</span>
                <span class="arch-node arch-node--tertiary">Deterministic Metrics</span>
              </div>
            </div>
          </div>
        </div>

        <div>
          <p class="arch-label">Storage & Output</p>
          <div class="arch-row">
            <span class="arch-node arch-node--secondary">PostgreSQL</span>
            <span class="arch-node arch-node--secondary">S3 Artifacts</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node">Streamlit Dashboard</span>
            <span class="arch-connector">&rarr;</span>
            <span class="arch-node">Reports / Comparison</span>
          </div>
        </div>
      </div>
    </div>

  </div>
</div>

<!-- System Design Focus -->
<div class="section">
  <h2 class="section__title">System Design Focus</h2>
  <div class="strengths-strip strengths-strip--inline">
    <span class="strength-item">Multi-Tenant AI Architecture</span>
    <span class="strength-item">Retrieval-Augmented Generation</span>
    <span class="strength-item">Vector Search & Filtering</span>
    <span class="strength-item">Async Ingestion Pipelines</span>
    <span class="strength-item">LLM Cost Optimization</span>
    <span class="strength-item">Evaluation Infrastructure</span>
  </div>
</div>
