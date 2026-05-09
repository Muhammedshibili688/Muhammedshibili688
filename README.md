# Muhammed Shibili P.K
### ML Engineer · Real-Time ML Systems · Fraud & Risk Engineering · MLOps

I enjoy building ML systems that operate under real-world constraints - latency, noisy data, fraud behavior, and operational cost.

Focused on systems that combine **machine learning**, **decision engineering**, and **production MLOps** - not just model training.

---

## 🧠 Featured Projects

### 🛡️ Real-Time Fraud Detection Engine
Streaming fraud decision system using behavioral feature engineering, continuous risk scoring, and cost-aware threshold optimization.

Built a pipeline where transactions flow from event ingestion → feature engineering → hybrid scoring → ALLOW / REVIEW / BLOCK decision - with full MLOps tracking.

**Key engineering choices:**
- Stateful behavioral features via Redis (velocity, device switching, geo anomaly)
- Continuous risk scoring across signal categories (identity, behavioral, velocity, amount)
- Cost-aware threshold optimization - minimizes fraud loss + review cost, not just accuracy
- Dual-threshold decision policy (ALLOW / REVIEW / BLOCK)
- DVC pipeline with S3 parquet data lake and MLflow experiment tracking

`Python` `Redis Streams` `DVC` `MLflow` `AWS S3` `FastAPI` `Docker` `Prometheus`

[View Repository →](https://github.com/Muhammedshibili688/transaction-risk-engine)

---

### 🏦 Credit Risk Scoring System
Probability of Default engine for loan risk assessment with decision thresholding.

- Logistic regression pipeline estimating PD with approve / reject / review tiers
- Feature engineering from demographic and payment history signals
- Production-ready Pipeline + ColumnTransformer structure

`Python` `Scikit-learn` `Pandas` `Plotly`

---

## ⚙️ Stack

**ML & Data** - Python · Scikit-learn · XGBoost · Pandas · NumPy

**MLOps** - DVC · MLflow · DagsHub · Docker · GitHub Actions

**Streaming & Infra** - Redis Streams · FastAPI · AWS S3 · Parquet

**Monitoring** - Prometheus · Grafana

**Databases** - PostgreSQL · MySQL

---

## 📚 Currently Building

- Hybrid ML + heuristic scorer (XGBoost layer on top of rule engine)
- FastAPI real-time scoring endpoint
- Prometheus + Grafana monitoring dashboard
- Model drift detection and alerting

---

## 📌 2026 Goals

- Ship fraud detection system fully end to end
- Master real-time ML serving and monitoring
- Land ML Engineer role working on real-world decision systems

---

## 🌐 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammedshibili001/)

[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discordapps.com/users/1221476951525560450)

---

*Building systems that make decisions - not just predictions.*
