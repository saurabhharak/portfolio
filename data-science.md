---
layout: default
title: Data Science & Engineering
description: ML models, data pipelines, and large-scale data processing systems
---

<div class="project-grid">

  <div class="project-card">
    <div class="project-card__header">
      <h3>Government Data Processing — India Data Portal</h3>
      <p class="project-card__subtitle">ISB Hyderabad | Large-Scale ETL</p>
    </div>
    <p class="project-card__desc">Processed and cleaned over 500GB of data sourced from government websites including MNREGA Physical, Financial, and Mandays datasets. Built end-to-end pipelines using PySpark for distributed processing and Pandas for data manipulation, with data transformation from long to wide format for integration with the India Data Portal. Stored in Parquet format on Wasabi cloud storage.</p>
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
    <p class="project-card__desc">ETL pipeline extracting import-export data from the Trade Statistics portal of the Ministry of Commerce, Government of India. Created a 100GB+ dataset spanning 16 years of monthly trade data at the country level. Implemented ThreadPoolExecutor for parallel data processing, significantly reducing execution time.</p>
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
    <p class="project-card__desc">Real-time stock market data system using Apache Kafka for streaming ingestion. Leveraged AWS Glue for schema management and Athena for SQL-based analytics on streaming data. Implemented performance optimization and robust error handling for reliable real-time processing.</p>
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
    <p class="project-card__desc">Dynamic drone detection model for defense applications using YOLOv3 (CNN) with PTZ camera and sensor integration. Collected drone image datasets through web scraping, designed and trained the detection system, and integrated with jammer systems. Minimized PTZ system cost by one-third compared to alternatives.</p>
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
    <p class="project-card__desc">CNN-based model for accurate melanoma detection from skin images using TensorFlow. Implemented multiclass classification with custom model architecture, handled imbalanced data through up/down sampling, and evaluated using ROC-AUC score and confusion matrices. Melanoma accounts for 75% of skin cancer deaths — early detection is critical.</p>
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
    <p class="project-card__desc">NLP model to automatically classify customer complaints based on mentioned products and services. Explored multiple approaches — RNN, LSTM, GRU, Random Forest, and SVM — with word2vec and GloVe embeddings. Includes multilingual translation, stop word removal, and lemmatization in the preprocessing pipeline.</p>
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
    <p class="project-card__desc">Transformer-based image captioning system using VisionEncoderDecoderModel to generate contextually rich captions. Leverages ViTImageProcessor and AutoTokenizer for preprocessing, deployed as an interactive Streamlit application on HuggingFace Spaces.</p>
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
