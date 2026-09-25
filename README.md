# 🛡️ PS-02 — Real-Time Fraud & Anomaly Detection

> **AI-powered transaction fraud detection system with real-time risk analysis, anomaly detection, explainable decisions, and a Streamlit dashboard.**

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Streamlit](https://img.shields.io/badge/Streamlit-UI-red?logo=streamlit)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?logo=pandas)
![Status](https://img.shields.io/badge/Status-Academic%20Project-success)

---

## 📌 Overview

**PS-02 — Real-Time Fraud & Anomaly Detection** is a machine-learning based fraud detection system designed to analyze financial transactions and identify potentially fraudulent or anomalous activity.

The system combines:

* 🌲 **Random Forest** for supervised fraud classification
* 🌳 **Extra Trees** for model comparison
* 🚨 **Isolation Forest** for anomaly detection
* 📊 **Risk scoring** for transaction-level assessment
* 🧠 **Rule-based explanations** for suspicious transactions
* ⚡ **Inference latency measurement**
* 🖥️ **Streamlit dashboard** for real-time interaction

The project is designed as a simple and understandable implementation suitable for an **academic project, demonstration, and viva presentation**.

---

# ✨ Key Features

### 🔍 Fraud Classification

The system predicts whether a transaction is:

```text
0 → Normal
1 → Fraud
```

The primary classification model is **Random Forest Classifier**.

---

### 🚨 Anomaly Detection

An additional **Isolation Forest** model detects transactions that appear unusual compared with the l
