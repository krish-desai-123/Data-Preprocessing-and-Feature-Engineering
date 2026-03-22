
<div align="center">

# 📊 Automated Data Profiling: PR_1 🚀

**A hands-on implementation of automated exploratory data analysis (EDA) across multiple data formats.**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Data Analysis](https://img.shields.io/badge/Data_Analysis-success?style=for-the-badge)](#)

</div>

<br>

## 🌟 About the Repository

Welcome to Practical 1 (PR_1)! This section focuses on the crucial first step of any data project: understanding your data. This repository demonstrates how to ingest data from various sources (CSV, JSON, SQLite) and automatically generate a comprehensive, interactive HTML report summarizing the dataset's characteristics, missing values, and distributions.

**Topics:** `python` `data-profiling` `pandas-profiling` `exploratory-data-analysis` `eda` `data-science` `jupyter-notebook`

---

## 📂 Repository Structure

The repository is organized as follows:

```text
📦 PR_1
 ┣ 📜 customer_data.db         # Sample dataset in SQLite database format
 ┣ 📜 customer_data1.csv       # Sample dataset in CSV format
 ┣ 📜 customer_data2.json      # Sample dataset in JSON format
 ┣ 📜 data_profiler.ipynb      # Main Jupyter Notebook containing the profiling logic
 ┣ 📜 customers_data_report.html # The generated interactive EDA report
 ┗ 📜 readme.md                # This file
```

---

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

---


## 📊 Results & Output

* **Cleaned Dataset:** A unified dataset ready for predictive modeling (Churn Classification).
* **Visualizations:** Cleanly labeled distribution plots, scatter plots, and heatmaps located in the notebook.
* **Profiling Report:** Open `customers_data_report.html` in any web browser for a full statistical breakdown of the dataset.

---

## ⚙️ Getting Started

Want to run this project on your local machine and generate your own reports? Follow these simple steps:

### 1. Clone the Repository

Open your terminal or command prompt and run:

```bash id="96ho3z"
git clone https://github.com/krish-desai-123/Data-Preprocessing-and-Feature-Engineering.git
cd Data-Preprocessing-and-Feature-Engineering/PR_1
```

### 2. Run the Code

Make sure you have Python installed. You will need a few essential libraries to run the profiler.

```bash id="s2ghx0"
# Install required libraries
pip install pandas ydata-profiling jupyter

# Launch the interactive notebook
jupyter notebook
```

Open `data_profiler.ipynb` and run the cells to generate the HTML report!

---



## 👨‍💻 Author

**Krish Desai**  

GitHub: [@krish-desai-123](https://github.com/krish-desai-123)

---

<div align="center">
<i>If you found this repository helpful or learned something new, consider giving it a ⭐!</i>
</div>
