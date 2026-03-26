---
layout: default
---

<section class="hero-section">
  <div class="hero-content">
    <p class="hero-tagline" style="margin-bottom: 0.75rem; font-size: 0.6875rem; font-weight: 600; letter-spacing: 0.1em; text-transform: uppercase; color: var(--secondary);">Senior Software Engineer</p>
    <h1 class="hero-name">Saurabh Harak</h1>
    <p class="hero-title">AI Platforms Engineering</p>
    <p class="hero-tagline">Building Enterprise RAG, LLM Evaluation & Agentic AI Systems at Scale</p>
    <div class="hero-social">
      <a href="https://linkedin.com/in/saurabh-harak" target="_blank" rel="noopener" aria-label="LinkedIn"><i class="fab fa-linkedin" aria-hidden="true"></i></a>
      <a href="https://github.com/saurabhharak" target="_blank" rel="noopener" aria-label="GitHub"><i class="fab fa-github" aria-hidden="true"></i></a>
      <a href="mailto:jobsforsaurabhharak@gmail.com" aria-label="Email"><i class="fas fa-envelope" aria-hidden="true"></i></a>
    </div>
  </div>
</section>

<!-- Impact Metrics -->
<div class="metric-grid">
  <div class="metric">
    <span class="metric__value">5+</span>
    <span class="metric__label">Years Experience</span>
  </div>
  <div class="metric">
    <span class="metric__value">80%+</span>
    <span class="metric__label">Test Coverage</span>
  </div>
  <div class="metric">
    <span class="metric__value">3s</span>
    <span class="metric__label">p95 Eval Latency</span>
  </div>
  <div class="metric">
    <span class="metric__value">$0.015</span>
    <span class="metric__label">Cost / Evaluation</span>
  </div>
</div>

<!-- About -->
<div class="section">
  <h2 class="section__title">About</h2>
  <p class="section__subtitle">Senior GenAI Engineer building production AI systems</p>
  <p>Currently a core engineer at <strong>TechnoMile</strong>, where I build <strong>Mila Chat</strong> — a multi-tenant enterprise RAG platform serving federal clients — and sole-architected the <strong>Unified AI Evaluation Platform</strong> that consolidated 3 codebases into one YAML-configurable system, cutting onboarding from 3 weeks to under 4 hours.</p>
  <p>Previously fine-tuned Llama2/3 with LoRA/PEFT at Computech Corporation, built spatio-temporal data pipelines at ISB Hyderabad, and led drone autonomy R&D at Jatayu. MSc in Machine Learning & AI from Liverpool John Moores University.</p>
</div>

<!-- Featured Projects -->
<div class="section">
  <h2 class="section__title">Featured Projects</h2>
  <p class="section__subtitle">Enterprise-scale AI systems in production</p>

  <div class="project-grid">
    <div class="project-card project-card--featured">
      <div class="project-card__header">
        <span class="featured-badge">Enterprise</span>
        <h3>Mila Chat</h3>
        <p class="project-card__subtitle">Multi-Tenant Enterprise RAG Platform</p>
      </div>
      <p class="project-card__desc">Core engineer on a production multi-tenant GenAI platform supporting federal enterprise clients across document intelligence and conversational AI. Designed retrieval and ingestion architecture with strict multi-tenant isolation at every layer — database, vector search, and conversation context.</p>
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
      </div>
    </div>

    <div class="project-card project-card--featured">
      <div class="project-card__header">
        <span class="featured-badge">Sole Architect</span>
        <h3>Unified AI Evaluation Platform</h3>
        <p class="project-card__subtitle">LLM-as-Judge Evaluation System</p>
      </div>
      <p class="project-card__desc">Consolidated 3 independent evaluation codebases (~3,000+ lines of duplicated code) into a single YAML-configurable system evaluating 3 enterprise AI products. Pluggable LLM-as-Judge engine with GPT-4.1, 5 LLM metrics + 3 deterministic metrics, fully integrated into Azure Pipelines CI/CD.</p>
      <div class="project-card__metrics">
        <div class="metric">
          <span class="metric__value">4hrs</span>
          <span class="metric__label">Onboarding (was 3 wks)</span>
        </div>
        <div class="metric">
          <span class="metric__value">80%+</span>
          <span class="metric__label">Test Coverage</span>
        </div>
        <div class="metric">
          <span class="metric__value">70%</span>
          <span class="metric__label">Effort Reduction</span>
        </div>
      </div>
      <div class="project-card__tech">
        <span class="tech-badge">GPT-4.1</span>
        <span class="tech-badge">Jinja2</span>
        <span class="tech-badge">Streamlit</span>
        <span class="tech-badge">Plotly</span>
        <span class="tech-badge">PostgreSQL</span>
        <span class="tech-badge">Azure Pipelines</span>
      </div>
    </div>

    <div class="project-card project-card--featured">
      <div class="project-card__header">
        <span class="featured-badge">Open Source</span>
        <h3>Creator GraphRAG</h3>
        <p class="project-card__subtitle">Multilingual Book-to-Video Knowledge System</p>
      </div>
      <p class="project-card__desc">Production-grade system that ingests multilingual books (Marathi, Hindi, English) via Sarvam AI OCR, builds a Knowledge Graph + Vector Store, and generates citation-enforced video content packages. Hybrid retrieval combining Neo4j graph traversal with Qdrant vector similarity search.</p>
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
        <span class="tech-badge">Neo4j</span>
        <span class="tech-badge">Qdrant</span>
        <span class="tech-badge">React 19</span>
        <span class="tech-badge">Celery</span>
        <span class="tech-badge">PostgreSQL</span>
      </div>
      <div class="project-card__links">
        <a href="https://github.com/saurabhharak/creator-graphrag" target="_blank" rel="noopener"><i class="fab fa-github" aria-hidden="true"></i> View on GitHub</a>
      </div>
    </div>
  </div>
</div>

<!-- Skills -->
<div class="section">
  <h2 class="section__title">Technical Skills</h2>
  <p class="section__subtitle">End-to-end AI systems expertise</p>

  <div class="skills-grid">
    <div class="skill-card">
      <h3><i class="fas fa-brain" aria-hidden="true"></i> AI / ML</h3>
      <div class="skill-badges">
        <span class="tech-badge">RAG Systems</span>
        <span class="tech-badge">Agentic AI</span>
        <span class="tech-badge">LLM Evaluation</span>
        <span class="tech-badge">LLM-as-Judge</span>
        <span class="tech-badge">LoRA/PEFT</span>
        <span class="tech-badge">Semantic Search</span>
        <span class="tech-badge">Prompt Engineering</span>
        <span class="tech-badge">LangChain</span>
        <span class="tech-badge">HuggingFace</span>
        <span class="tech-badge">OpenAI</span>
        <span class="tech-badge">Azure OpenAI</span>
      </div>
    </div>
    <div class="skill-card">
      <h3><i class="fas fa-server" aria-hidden="true"></i> Backend</h3>
      <div class="skill-badges">
        <span class="tech-badge">Python 3.11</span>
        <span class="tech-badge">FastAPI</span>
        <span class="tech-badge">Click CLI</span>
        <span class="tech-badge">Microservices</span>
        <span class="tech-badge">REST APIs</span>
        <span class="tech-badge">Async Pipelines</span>
        <span class="tech-badge">System Design</span>
      </div>
    </div>
    <div class="skill-card">
      <h3><i class="fas fa-database" aria-hidden="true"></i> Data & Cloud</h3>
      <div class="skill-badges">
        <span class="tech-badge">PostgreSQL</span>
        <span class="tech-badge">Qdrant</span>
        <span class="tech-badge">Neo4j</span>
        <span class="tech-badge">MongoDB</span>
        <span class="tech-badge">AWS S3/SQS/Lambda</span>
        <span class="tech-badge">Step Functions</span>
        <span class="tech-badge">Azure</span>
      </div>
    </div>
    <div class="skill-card">
      <h3><i class="fas fa-cogs" aria-hidden="true"></i> DevOps & QA</h3>
      <div class="skill-badges">
        <span class="tech-badge">Docker</span>
        <span class="tech-badge">Jenkins</span>
        <span class="tech-badge">Azure Pipelines</span>
        <span class="tech-badge">CI/CD</span>
        <span class="tech-badge">Pytest 80%+</span>
        <span class="tech-badge">Streamlit</span>
        <span class="tech-badge">Plotly</span>
      </div>
    </div>
  </div>
</div>

<!-- Career Timeline -->
<div class="section">
  <h2 class="section__title">Experience</h2>
  <p class="section__subtitle">From drones to enterprise AI platforms</p>

  <div class="timeline">
    <div class="timeline-item">
      <span class="timeline-item__date">Mar 2025 – Present</span>
      <h3 class="timeline-item__title">Senior Software Engineer – AI Platforms</h3>
      <span class="timeline-item__company">TechnoMile</span>
      <p class="timeline-item__desc">Core engineer on Mila Chat (multi-tenant RAG for federal clients). Sole architect of the Unified AI Evaluation Platform — consolidated 3 codebases, cut onboarding from 3 weeks to 4 hours, 80%+ test coverage.</p>
      <div class="project-card__tech">
        <span class="tech-badge">Azure OpenAI</span>
        <span class="tech-badge">Qdrant</span>
        <span class="tech-badge">PostgreSQL</span>
        <span class="tech-badge">Kubernetes</span>
      </div>
    </div>
    <div class="timeline-item">
      <span class="timeline-item__date">Sept 2023 – Mar 2025</span>
      <h3 class="timeline-item__title">Machine Learning Engineer – Conversational AI</h3>
      <span class="timeline-item__company">Computech Corporation</span>
      <p class="timeline-item__desc">Fine-tuned Llama2/3 with LoRA/PEFT, built agentic chatbots with LangChain ReAct patterns, and developed intelligent document query systems for enterprise clients.</p>
      <div class="project-card__tech">
        <span class="tech-badge">LangChain</span>
        <span class="tech-badge">LoRA/PEFT</span>
        <span class="tech-badge">Azure OpenAI</span>
        <span class="tech-badge">FastAPI</span>
      </div>
    </div>
    <div class="timeline-item">
      <span class="timeline-item__date">Nov 2022 – Sept 2023</span>
      <h3 class="timeline-item__title">Data Scientist</h3>
      <span class="timeline-item__company">Indian School of Business, Hyderabad</span>
      <p class="timeline-item__desc">Built large-scale spatio-temporal data pipelines for a national-scale data warehousing initiative. Automated ingestion from 10+ government sources, 30% efficiency improvement.</p>
      <div class="project-card__tech">
        <span class="tech-badge">PySpark</span>
        <span class="tech-badge">Pandas</span>
        <span class="tech-badge">Selenium</span>
        <span class="tech-badge">Wasabi</span>
      </div>
    </div>
    <div class="timeline-item">
      <span class="timeline-item__date">Jan 2021 – Nov 2022</span>
      <h3 class="timeline-item__title">Full Stack Developer / Team Leader</h3>
      <span class="timeline-item__company">Jatayu Unmanned Technology Pvt. Ltd.</span>
      <p class="timeline-item__desc">Led R&D for drone autonomy systems. Drove automation across drone operations achieving 40% effort reduction. Built web applications for drone data monitoring.</p>
      <div class="project-card__tech">
        <span class="tech-badge">Python</span>
        <span class="tech-badge">Django</span>
        <span class="tech-badge">OpenCV</span>
        <span class="tech-badge">YOLOv3</span>
      </div>
    </div>
  </div>
</div>

<!-- Education -->
<div class="section">
  <h2 class="section__title">Education</h2>

  <div class="education-grid">
    <div class="education-card">
      <h4>MSc Machine Learning & AI</h4>
      <p>Liverpool John Moores University</p>
    </div>
    <div class="education-card">
      <h4>PG Diploma ML & AI</h4>
      <p>IIIT Bangalore</p>
    </div>
    <div class="education-card">
      <h4>BE Computer Engineering</h4>
      <p>Pune University</p>
    </div>
  </div>
</div>

<!-- Contact CTA -->
<div class="contact-cta">
  <h2>Let's Build Something Together</h2>
  <p>Open to collaboration, consulting, and new opportunities in AI/ML engineering.</p>
  <div class="contact-buttons">
    <a href="mailto:jobsforsaurabhharak@gmail.com" class="contact-btn--primary"><i class="fas fa-envelope" aria-hidden="true"></i> Get in Touch</a>
    <a href="https://linkedin.com/in/saurabh-harak" target="_blank" rel="noopener"><i class="fab fa-linkedin" aria-hidden="true"></i> LinkedIn</a>
    <a href="https://github.com/saurabhharak" target="_blank" rel="noopener"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
  </div>
</div>
