<div align="center">

# 📊 Data Preprocessing & Feature Engineering

**A structured, hands-on project series covering the full data science pipeline — from raw multi-source data ingestion to automated EDA, cleaning, imputation, encoding, scaling, and model-ready dataset preparation.**

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white)](#)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](#)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](#)
[![ydata-profiling](https://img.shields.io/badge/ydata--profiling-4.x-blueviolet?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)](#)

</div>

---

## 📌 About This Repository

This repository is a structured collection of **lab exercises** and **projects** built progressively across three units of a data science course. Each piece targets a specific stage of the ML data pipeline — from understanding raw data formats to engineering features for predictive modelling.

The overarching theme is a real-world **Credit Risk / Loan Default** binary classification problem, with supporting labs that explore the individual techniques in isolation using smaller, focused datasets.

---

## 📂 Repository Structure

```
📦 Data-Preprocessing-and-Feature-Engineering
 │
 ├── 📓 Lab_Work_1_1.ipynb         # Unit 1 — DS project planning, ML framing, tensors
 ├── 📁 Lab_Work_1_2/              # Unit 1 — Multi-format data ingestion (CSV, JSON, SQL)
 ├── 📁 Lab_Work_1_3/              # Unit 1 — EDA (univariate, bivariate, profiling)
 │
 ├── 📓 Lab_Work_2_1.ipynb         # Unit 2 — General, numerical & categorical imputation
 ├── 📓 Lab_Work_2_2.ipynb         # Unit 2 — Random sample & KNN imputation
 ├── 📓 Lab_Work_2_3.ipynb         # Unit 2 — MICE / IterativeImputer & RMSE evaluation
 ├── 📓 Lab_Work_2_4.ipynb         # Unit 2 — Outlier detection: Z-score & IQR
 ├── 📓 Lab_Work_2_5.ipynb         # Unit 2 — Outlier treatment: Percentile & Winsorization
 │
 ├── 📓 Lab_Work_3_1.ipynb         # Unit 3 — Feature construction from datetime
 ├── 📓 Lab_Work_3_2.ipynb         # Unit 3 — Encoding: Ordinal, Label, One-Hot
 ├── 📓 Lab_Work_3_3.ipynb         # Unit 3 — Binning: Discretization, Binarization, Quantile
 ├── 📓 Lab_Work_3_4.ipynb         # Unit 3 — Scaling: Standardization, Normalization, MinMax
 │
 ├── 📁 PR_1/                      # Project 1 — Automated EDA & Data Profiling
 ├── 📁 PR_2/                      # Project 2 — Data Cleansing: Patient Health Records
 ├── 📁 Final_Project/             # Final Project — End-to-end Preprocessing Pipeline
 │
 └── 📜 requirements.txt           # All Python dependencies
```

---

## 🧪 Lab Exercises

### 🔷 Unit 1 — Data Foundations

| Notebook | Topics Covered |
|---|---|
| `Lab_Work_1_1.ipynb` | Planning a data science project, framing an ML problem, NumPy tensor fundamentals (scalar, vector, matrix, higher-order) |
| `Lab_Work_1_2/` | Reading CSV, JSON, and SQLite files; filtering, merging, and exporting structured data across formats |
| `Lab_Work_1_3/` | EDA — univariate distributions, bivariate relationships, multivariate pair plots; automated profiling report via `ydata-profiling` |

### 🔷 Unit 2 — Missing Values & Outliers

| Notebook | Topics Covered |
|---|---|
| `Lab_Work_2_1.ipynb` | `SimpleImputer` with mean, median, and mode strategies for numerical and categorical features |
| `Lab_Work_2_2.ipynb` | `MissingIndicator`, random sample imputation, `KNNImputer` (multivariate) |
| `Lab_Work_2_3.ipynb` | MICE via `IterativeImputer`, simulating MAR patterns, holdout RMSE evaluation, mixed numeric + categorical imputation |
| `Lab_Work_2_4.ipynb` | Outlier theory in ML, Z-score detection & removal, IQR detection & removal |
| `Lab_Work_2_5.ipynb` | Percentile-based clipping with threshold tuning, Winsorization technique |

### 🔷 Unit 3 — Feature Engineering

| Notebook | Topics Covered |
|---|---|
| `Lab_Work_3_1.ipynb` | Datetime feature construction — parsing, type conversion, computing delivery durations |
| `Lab_Work_3_2.ipynb` | Ordinal Encoding (education levels), Label Encoding, One-Hot Encoding with `drop='first'` |
| `Lab_Work_3_3.ipynb` | KBins Discretization (uniform & quantile), Binarization, K-Means binning |
| `Lab_Work_3_4.ipynb` | Standardization (Z-score), L1/L2 Normalization, MinMax Scaling, MaxAbs & Robust Scaling |

---

## 🚀 Projects

### PR_1 — Automated Data Profiling

> **Domain:** Customer Purchase Behaviour | **Goal:** Churn Prediction (Binary Classification)

A hands-on implementation of automated EDA across multiple data formats. Customer purchase data is ingested from CSV, JSON, and a SQLite database, merged into a single DataFrame, cleaned, and profiled using `ydata-profiling` to produce an interactive HTML report.

**Key highlights:** multi-source ingestion, REST API data fetch, type fixing, univariate/bivariate/multivariate EDA, automated profiling report.

📁 [`PR_1/`](./PR_1) · See the [project README](./PR_1/readme.md) for full details.

---

### PR_2 — Data Cleansing: Patient Health Records

> **Domain:** Healthcare | **Goal:** Produce analysis-ready patient records

An end-to-end data cleaning pipeline applied to raw, messy patient health records. The notebook walks through every stage of data purification — deduplication, missing value imputation, type casting, string sanitisation, and outlier handling — to output a fully clean CSV ready for EDA and ML modelling.

**Key highlights:** duplicate removal, targeted imputation by data type, datetime casting, whitespace/capitalisation standardisation, feature dropping, clean CSV export.

📁 [`PR_2/`](./PR_2) · See the [project README](./PR_2/readme.md) for full details.

---

### 🏆 Final Project — Holistic Data Preparer

> **Domain:** Credit Risk / Financial Services | **Goal:** Loan Default Prediction (Binary Classification)

The capstone project bringing together every technique from all three units. Customer credit risk data from three separate sources (CSV, JSON, SQLite) is merged and taken through an 8-part preprocessing pipeline to produce a model-ready 29-feature dataset.

**Pipeline at a glance:**

| Part | Stage | Key Decision |
|---|---|---|
| A | Conceptual Foundation | DS problem framing, tensor demos |
| B | Multi-Source Acquisition | CSV + JSON + SQLite merged on `customer_id` |
| C | Cleaning & Imputation | Compared Simple / Random / KNN / MICE → **MICE selected** |
| D | Outlier Handling | Z-score / IQR / Percentile / IQR+Winsorization → **zero rows lost** |
| E | Feature Engineering | Ordinal / Label / OHE / KBins / Binarizer / Quantile / K-Means binning |
| F | Feature Scaling | Standard / Normalizer / MinMax / MaxAbs / **RobustScaler** |
| G | Feature Construction & Transformation | 3 domain features + Log, Reciprocal, Sqrt, Box-Cox, Yeo-Johnson transforms |
| H | Final Deliverable | `final_cleaned_data.csv` — 2,500 rows × 29 features, zero nulls |

**Outputs:** `final_cleaned_data.csv`, `customer_credit_risk_dataset_EDA_report.html`, KDE comparison plots (`kde.png`), outlier box plots (`boxplot.png`).

📁 [`Final_Project/`](./Final_Project) · See the [project README](./Final_Project/README.md) for full details.

---

## 📊 Dataset Summary

| Project | Dataset | Records | Formats | Target Variable |
|---|---|---|---|---|
| PR_1 | Customer purchase behaviour | ~100 | CSV, JSON, SQLite | `Churn` (binary) |
| PR_2 | Patient health records | ~500 | CSV | — (cleaning only) |
| Final Project | Customer credit risk | 2,500 | CSV, JSON, SQLite | `default_flag` (binary) |

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/krish-desai-123/Data-Preprocessing-and-Feature-Engineering.git
cd Data-Preprocessing-and-Feature-Engineering
```

### 2. Set Up a Virtual Environment

```bash
python -m venv venv

# Windows:
venv\Scripts\activate

# macOS / Linux:
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Open any lab notebook directly, or navigate into `PR_1/`, `PR_2/`, or `Final_Project/` to run a full project end-to-end.

---

## 🧰 Tech Stack

| Tool | Purpose |
|---|---|
| `Python 3.10+` | Core language |
| `pandas` | Data loading, merging, manipulation |
| `numpy` | Numerical operations & tensor demonstrations |
| `matplotlib` + `seaborn` | Visualisations — distributions, heatmaps, box plots, KDE plots |
| `scikit-learn` | Imputation, encoding, scaling, binning (`SimpleImputer`, `KNNImputer`, `IterativeImputer`, `OrdinalEncoder`, `OneHotEncoder`, `StandardScaler`, `KBinsDiscretizer`, etc.) |
| `ydata-profiling` | Automated interactive HTML EDA reports |
| `sqlite3` | SQLite database connections |
| `jupyter` | Interactive notebook environment |

---

## 👨‍💻 Author

**Krish Desai**
GitHub: [@krish-desai-123](https://github.com/krish-desai-123)

---

<div align="center">
<i>If this repository helped you learn or saved you time, consider giving it a ⭐ — it means a lot!</i>
</div>
