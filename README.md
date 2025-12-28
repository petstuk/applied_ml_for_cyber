# Applied ML for Cybersecurity — Hybrid Blog Project Series

**Hybrid Approach:**

- **Integrated posts** mid-series: combine early projects into cohesive pipelines
- **Capstone posts** at the end: full end-to-end solution

Each **Project** = one real security problem  
Each **Part** = one blog post  
Each blog post produces **code, visuals, and insight**

---

## 🔹 PROJECT 1: Building a Security Data Pipeline on macOS

**(Weeks 1–2)**  
_“From Raw Logs to Analysis-Ready Data”_

### Blog Series

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
- Blog-ready diagrams
- Clean datasets for later projects

---

## 🔹 PROJECT 2: Statistics & Bayesian Threat Scoring

**(Weeks 3–4)**  
_“Turning Uncertainty Into Signal”_

### Blog Series

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
  - Preliminary anomaly detection using K-Means
- **Goal:** Demonstrate a working pipeline for downstream ML

---

## 🔹 PROJECT 3: Unsupervised Learning for Threat Hunting

**(Weeks 5–7)**  
_“Finding Attacks Without Labels”_

### Blog Series

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

### Blog Series

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

### Blog Series

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

### Blog Series

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

### Blog Series

#### Part 22 – Problem Definition & Data Selection

#### Part 23 – Full Data Pipeline (Integrated from earlier posts)

#### Part 24 – Modeling & Results (Unsupervised + Supervised + Deep Learning)

#### Part 25 – Evaluation & Failure Analysis

#### Part 26 – Operational Lessons & Defender Takeaways

**Goal:** Demonstrate the **entire end-to-end workflow**, polished for portfolio and practical use.
