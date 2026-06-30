# Applied ML for Cybersecurity — Hybrid Blog Project Series

**Hybrid Approach:**

- **Integrated posts** mid-series: combine early projects into cohesive pipelines
- **Capstone posts** at the end: full end-to-end solution

Each **Project** = one blog post or portfolio article around a real security problem  
Each **Part** = one section, milestone, or technical step within that project  
Each project post produces **code, visuals, and insight**

---

## Current Status

This repository is being built manually as a staged ML-for-cyber learning project. The current work has moved from small legacy `system.log` examples to macOS Unified Logs, because Unified Logs provide richer process, subsystem, error/fault, security, and activity signals for downstream analysis.

### Project Flow

- **Project 1 - Data Pipeline:** owns raw log collection, parsing, normalization, SQLite loading, and enriched feature datasets.
- **Project 2 - Statistics & Bayesian Scoring:** consumes the enriched Project 1 dataset to build statistical baselines and simple probabilistic risk scoring.
- **Project 3 - Unsupervised Learning:** starts from the enriched dataset and will focus on feature exploration, clustering, anomaly scoring, and interpretation.

### Done So Far

- Created the repository structure for the full applied ML-for-cyber series.
- Built initial macOS `system.log` parsing and enrichment as the first learning pass.
- Added Unified Log parsing in the data pipeline using `unified_1m.log`.
- Created processed and enriched Unified Log datasets for downstream notebooks.
- Refreshed the statistics/Bayesian notebook to use the enriched Unified Log dataset.

### Next Manual Work

- Continue feature exploration in `03_unsupervised_learning`.
- Build unsupervised baselines on the enriched Unified Log features.
- Add clustering, anomaly scoring, visualization, and defender-focused interpretation.

---

## 🔹 PROJECT 1: Building a Security Data Pipeline on macOS

**(Weeks 1–2)**  
_“From Raw Logs to Analysis-Ready Data”_

### Project Sections

#### Part 1 – Setting Up a Mac-Based ML Security Lab

- Homebrew, Python (pyenv or uv), Jupyter, VS Code
- Virtual environments, Dataset folder structure

#### Part 2 – Python for Security Data & pandas

- Lists, dicts, comprehensions, reading logs, timestamps
- DataFrames, filtering, grouping, feature creation

#### Part 3 – Querying & Enriching Security Data

- SQLite basics, SQL joins, aggregations
- JSON / NoSQL logs, flattening nested data
- Web scraping threat intelligence

### Output

- Reusable ingestion pipeline
- Parsed and enriched macOS Unified Log datasets
- Blog-ready diagrams
- Clean datasets for later projects

---

## 🔹 PROJECT 2: Statistics & Bayesian Threat Scoring

**(Weeks 3–4)**  
_“Turning Uncertainty Into Signal”_

### Project Sections

#### Part 4 – Statistics SOC Analysts Actually Use

- Mean, median, variance, outliers
- Visualizations: histograms, scatter plots, time series

#### Part 5 – Probability & Bayes for Security Decisions

- Conditional probability, false positives
- Bayes theorem, prior vs posterior
- Bayesian login risk engine

#### Part 6 – Signal Processing for Threat Hunting

- FFT intuition, beacon detection, periodic traffic

### Output

- Bayesian threat scoring notebook
- Signal-based detector
- Visual SOC artifacts

---

## 🔹 INTEGRATED POST 1: Data Pipeline + Exploratory Analysis

**(Weeks 5)**  
_“From Raw Logs to ML-Ready Features”_

- Combine Projects 1–2 into **one cohesive pipeline**
- Includes:
  - Raw log ingestion
  - Data cleaning & normalization
  - Feature engineering
  - Exploratory visualization
  - Feature preparation for preliminary anomaly detection
- **Goal:** Demonstrate a working pipeline for downstream unsupervised ML

---

## 🔹 PROJECT 3: Unsupervised Learning for Threat Hunting

**(Weeks 5–7)**  
_“Finding Attacks Without Labels”_

### Project Sections

This project consumes `01_data_pipeline/datasets/enriched/unified_logs_enriched.csv` as the ML-ready starting point.

#### Part 7 – Why Unsupervised ML Matters in Security

- Conceptual introduction
- No labels, unknown threats

#### Part 8 – Clustering User Behavior with K-Means & PCA

- Feature engineering, cluster interpretation, dimensionality reduction

#### Part 9 – DBSCAN for Beaconing & Lateral Movement

- Density-based clustering, anomaly detection

#### Part 10 – Decision Trees & Random Forests

- Explainability, ensemble logic, trade-offs

### Output

- Threat hunting notebook
- Cluster-based anomaly detector
- SOC-ready visuals

---

## 🔹 PROJECT 4: Supervised Learning & Neural Networks

**(Weeks 8–9)**  
_“Teaching Machines What ‘Bad’ Looks Like”_

### Project Sections

#### Part 11 – Regression & Forecasting for Security Metrics

- Trend analysis, capacity planning

#### Part 12 – Loss Functions & Why Models Fail

- Overfitting, evaluation metrics

#### Part 13 – Building Neural Networks for Phishing Detection

- Dense layers, feature extraction, model training
- Precision, recall, confusion matrices

#### Part 14 – Real-Time Network Classification

- Streaming data, live inference

### Output

- Phishing classifier
- Network protocol model
- Performance evaluation framework

---

## 🔹 PROJECT 5: Deep Learning for Detection (CNNs & Autoencoders)

**(Weeks 10–11)**  
_“Detection Without Signatures”_

### Project Sections

#### Part 15 – CNNs for Security (Beyond Images)

- Filters, feature maps, text/malware intuition

#### Part 16 – Embeddings & CNN-Based Text Classification

- Tokenization, embeddings, zero-day detection

#### Part 17 – Autoencoders for Log Anomaly Detection

- Reconstruction loss, training on normal data

#### Part 18 – Ensemble Autoencoders for Scale

- Reducing noise, improving detection

### Output

- Signature-less anomaly engine
- Deep learning portfolio artifacts

---

## 🔹 PROJECT 6: Advanced ML Thinking (CNNs + Genetic Algorithms)

**(Weeks 12–13)**  
_“Solving the Problem You Actually Have”_

### Project Sections

#### Part 19 – Framing ML Problems for Security

- Reframing detection tasks, problem-solving mindset

#### Part 20 – CNNs with TensorFlow Functional API

- Multi-input models, graph thinking

#### Part 21 – Genetic Algorithms for Security Optimization

- Evolutionary search, feature tuning

### Output

- Advanced CNN model
- Genetic optimization demo

---

## 🔹 CAPSTONE: A Public ML-for-Security Portfolio

**(Weeks 14–16)**  
_“From Student to Practitioner”_

### Capstone Sections

#### Part 22 – Problem Definition & Data Selection

#### Part 23 – Full Data Pipeline (Integrated from earlier posts)

#### Part 24 – Modeling & Results (Unsupervised + Supervised + Deep Learning)

#### Part 25 – Evaluation & Failure Analysis

#### Part 26 – Operational Lessons & Defender Takeaways

#### Part 27 – Building an Agentic SOC Analyst for ML-Driven Threat Hunting

**Goal:** Demonstrate the **entire end-to-end workflow**, polished for portfolio and practical use.
