---
layout: default
title: Applied ML & Data Engineering Foundations
label: AI FOUNDATIONS & DATA ENGINEERING
description: Large-scale data pipelines, applied ML workflows, and distributed data processing systems that built the foundation for my current GenAI engineering work.
---

<p class="section__subtitle" style="margin-top: 0; margin-bottom: var(--space-8);">This work reflects my background in large-scale ETL, data transformation, and applied analytics, which now informs how I design robust AI systems and retrieval pipelines.</p>

<div class="project-grid">

  <div class="project-card">
    <div class="project-card__header">
      <h3>Government Data Processing — India Data Portal</h3>
      <p class="project-card__subtitle">ISB Hyderabad | Large-Scale ETL</p>
    </div>
    <p class="project-card__desc">Processed and transformed 500GB+ of public-sector data from multiple government portals, including MNREGA physical, financial, and mandays datasets.</p>
    <p class="project-card__desc">Built end-to-end ETL workflows using PySpark for distributed processing and Pandas for downstream transformation, including long-to-wide restructuring for portal integration.</p>
    <p class="project-card__desc">Stored processed outputs in Parquet format on cloud object storage to support reliable large-scale data access and downstream analytics.</p>
    <div class="project-card__metrics">
      <div class="metric">
        <span class="metric__value">500GB+</span>
        <span class="metric__label">Data Processed</span>
      </div>
      <div class="metric">
        <span class="metric__value">20+</span>
        <span class="metric__label">Datasets Built</span>
      </div>
      <div class="metric">
        <span class="metric__value">30%</span>
        <span class="metric__label">Efficiency Gain</span>
      </div>
    </div>
    <div class="project-card__tech">
      <span class="tech-badge">PySpark</span>
      <span class="tech-badge">Pandas</span>
      <span class="tech-badge">Selenium</span>
      <span class="tech-badge">BeautifulSoup</span>
      <span class="tech-badge">Parquet</span>
      <span class="tech-badge">Wasabi</span>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card__header">
      <h3>Import Export Data — National Trade ETL Pipeline</h3>
      <p class="project-card__subtitle">ISB Hyderabad | 16-Year Dataset</p>
    </div>
    <p class="project-card__desc">Built an ETL pipeline extracting import-export data from the Trade Statistics portal of the Ministry of Commerce, Government of India. Produced a 100GB+ dataset spanning 16 years of monthly trade data at the country level. Implemented ThreadPoolExecutor for parallel data processing, significantly reducing execution time.</p>
    <div class="project-card__metrics">
      <div class="metric">
        <span class="metric__value">100GB+</span>
        <span class="metric__label">Dataset Size</span>
      </div>
      <div class="metric">
        <span class="metric__value">16yrs</span>
        <span class="metric__label">Data Span</span>
      </div>
    </div>
    <div class="project-card__tech">
      <span class="tech-badge">Python</span>
      <span class="tech-badge">Pandas</span>
      <span class="tech-badge">ThreadPoolExecutor</span>
      <span class="tech-badge">boto3</span>
      <span class="tech-badge">Wasabi</span>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card__header">
      <h3>Real-Time Stock Market Data with Kafka</h3>
      <p class="project-card__subtitle">Streaming Data Engineering</p>
    </div>
    <p class="project-card__desc">Built a real-time stock market data system using Apache Kafka for streaming ingestion. Leveraged AWS Glue for schema management and Athena for SQL-based analytics on streaming data. Implemented performance optimization and error handling for reliable real-time processing.</p>
    <div class="project-card__tech">
      <span class="tech-badge">Apache Kafka</span>
      <span class="tech-badge">AWS Glue</span>
      <span class="tech-badge">AWS Athena</span>
      <span class="tech-badge">Python</span>
      <span class="tech-badge">SQL</span>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card__header">
      <h3>Drone Detection Model</h3>
      <p class="project-card__subtitle">Defense Sector | YOLOv3 Computer Vision</p>
    </div>
    <p class="project-card__desc">Designed and trained a real-time drone detection model for defense applications using YOLOv3 with PTZ camera and sensor integration. Built the image dataset via automated web scraping, integrated the detection system with jammer hardware, and reduced PTZ system cost by one-third versus alternatives.</p>
    <div class="project-card__metrics">
      <div class="metric">
        <span class="metric__value">35%</span>
        <span class="metric__label">Jammer Enhancement</span>
      </div>
    </div>
    <div class="project-card__tech">
      <span class="tech-badge">YOLOv3</span>
      <span class="tech-badge">OpenCV</span>
      <span class="tech-badge">Python</span>
      <span class="tech-badge">NumPy</span>
      <span class="tech-badge">PTZ Camera</span>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card__header">
      <h3>Melanoma Detection</h3>
      <p class="project-card__subtitle">Medical AI | CNN Classification</p>
    </div>
    <p class="project-card__desc">Built a CNN-based melanoma detection model from skin images using TensorFlow. Implemented multiclass classification with custom architecture, handled class imbalance through targeted sampling, and evaluated using ROC-AUC and confusion matrices.</p>
    <div class="project-card__tech">
      <span class="tech-badge">TensorFlow</span>
      <span class="tech-badge">CNN</span>
      <span class="tech-badge">Python</span>
      <span class="tech-badge">ROC-AUC</span>
    </div>
    <div class="project-card__links">
      <a href="https://github.com/saurabhharak/Melanoma-Detection" target="_blank" rel="noopener"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card__header">
      <h3>Automatic Ticket Classification</h3>
      <p class="project-card__subtitle">NLP | Multi-Algorithm Comparison</p>
    </div>
    <p class="project-card__desc">Built an NLP classification system for automatic customer complaint routing. Implemented and compared RNN, LSTM, GRU, Random Forest, and SVM with word2vec and GloVe embeddings. Delivered 91.2% accuracy with a preprocessing pipeline including multilingual translation and lemmatization.</p>
    <div class="project-card__metrics">
      <div class="metric">
        <span class="metric__value">91.2%</span>
        <span class="metric__label">Accuracy</span>
      </div>
    </div>
    <div class="project-card__tech">
      <span class="tech-badge">RNN</span>
      <span class="tech-badge">LSTM</span>
      <span class="tech-badge">Word2Vec</span>
      <span class="tech-badge">GloVe</span>
      <span class="tech-badge">NLP</span>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card__header">
      <h3>Image Captioning with Transformers</h3>
      <p class="project-card__subtitle">Vision + Language | Streamlit App</p>
    </div>
    <p class="project-card__desc">Built a transformer-based image captioning system using VisionEncoderDecoderModel. Deployed as an interactive Streamlit application on HuggingFace Spaces with ViTImageProcessor and AutoTokenizer for preprocessing.</p>
    <div class="project-card__tech">
      <span class="tech-badge">Transformers</span>
      <span class="tech-badge">ViT</span>
      <span class="tech-badge">Streamlit</span>
      <span class="tech-badge">HuggingFace</span>
    </div>
    <div class="project-card__links">
      <a href="https://huggingface.co/spaces/saurabhharak/image-captioning-streamlit" target="_blank" rel="noopener"><i class="fas fa-external-link-alt" aria-hidden="true"></i> Live Demo</a>
    </div>
  </div>

</div>
