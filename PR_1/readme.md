<h1 align="center">📊 Data Profiler: Customer Churn EDA & Preprocessing</h1>

<p align="center">
  <em>A comprehensive Data Preprocessing, Feature Engineering, and Exploratory Data Analysis (EDA) pipeline to transform multi-source raw data into ML-ready insights. 🚀</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter Notebook" />
  <img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

---

## 🎯 Project Objective

In the modern data ecosystem, information rarely lives in a single place. This project simulates a real-world scenario as a Junior Data Analyst for a consumer insights company. 

The primary goal is to **frame a machine learning problem (predicting customer churn)** and perform robust data preprocessing and profiling on customer purchase behavior data collected across multiple formats (CSV, JSON, SQL). 

## 📂 Repository Structure

This repository contains all the scripts, datasets, and notebooks used in the analysis:

* **`data_gen.py`** 🐍: A Python script used to generate the synthetic, multi-format datasets.
* **`data_profiler.ipynb`** 📓: The core Jupyter Notebook containing the end-to-end data pipeline (Acquisition, Cleaning, EDA, and Feature interactions).
* **`customer_data1.csv`** 📄: Raw customer data subset (CSV format).
* **`customer_data2.json`** ｛｝: Raw customer data subset (JSON format).
* **`customer_data.db`** 🗄️: Raw customer data subset (SQLite Database format).
* **`customers_data_report.html`** 📈: The automated, interactive Pandas Profiling report summarizing data quality, missing values, and correlations.

## 🛠️ Key Features & Workflow

### 1. Multi-Source Data Acquisition 🌐
* Imported and merged datasets seamlessly from **CSV**, **JSON**, and a **SQL Database**.
* Integrated external data by making `GET` requests to a dummy REST API.

### 2. Data Cleaning & Understanding 🧹
* Handled missing values through imputation and removal strategies.
* Corrected inconsistent data types to ensure modeling compatibility.
* Dropped redundant and irrelevant columns.

### 3. Exploratory Data Analysis (EDA) 🔍
* **Univariate Analysis:** Visualized distributions of `Age`, `Income`, and `Purchases`.
* **Bivariate Analysis:** Investigated relationships between `Gender` & `Purchases`, and `Income` & `Churn`.
* **Multivariate Analysis:** Generated pair plots and correlation heatmaps for deeper feature interaction discovery.

### 4. Automated Data Profiling ⚙️
* Generated a comprehensive, shareable HTML report detailing descriptive statistics, data quality warnings, and variable correlations.

## 📊 Results & Output

* **Cleaned Dataset:** A unified dataset ready for predictive modeling (Churn Classification).
* **Visualizations:** Cleanly labeled distribution plots, scatter plots, and heatmaps located in the notebook.
* **Profiling Report:** Open `customers_data_report.html` in any web browser for a full statistical breakdown of the dataset.

---
<p align="center">
  <i>"Transforming raw data into predictive power, one dataset at a time. 💡"</i>
</p>