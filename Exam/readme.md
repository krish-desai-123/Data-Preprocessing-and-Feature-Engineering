<div align="center">

# 🚖 Ride-Sharing Data Integration: Practical Exam 🛣️

**An end-to-end data engineering assessment merging multi-format mobility data into a clean, analysis-ready dataset.**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Data Engineering](https://img.shields.io/badge/Data_Engineering-success?style=for-the-badge)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](#)

</div>

---

## 🌟 About the Repository

Welcome to the Practical Exam repository! This project tackles a highly realistic data engineering challenge: integrating fragmented data sources. Using a simulated ride-sharing environment, this repository demonstrates how to extract rider demographics (`.csv`), trip logs (`.json`), and spatial city zones (`.db`), clean the inconsistencies, and merge them into one unified, pristine dataset (`final_prepared_rides_dataset.csv`).

To validate the quality of the merged data, the pipeline also automatically generates a comprehensive Exploratory Data Analysis (EDA) HTML report!

**Topics:** `python` `data-engineering` `data-preprocessing` `ride-sharing` `eda` `pandas` `sqlite` `practical-exam` `data-science`

---

## 📂 Repository Structure

```text
📦 Ride-Sharing-Data-Integration
 ┣ 📜 practical_exam.ipynb               # Core Jupyter Notebook containing the ETL, merging, and cleaning logic
 ┣ 📜 riders.csv                         # [INPUT] Raw rider demographic data
 ┣ 📜 trips.json                         # [INPUT] Raw trip/ride logs
 ┣ 📜 city_zones.db                      # [INPUT] Raw SQLite database containing spatial city zones
 ┣ 📜 final_prepared_rides_dataset.csv   # [OUTPUT] The merged, cleaned, and standardized dataset
 ┣ 📜 eda_report.html                    # [OUTPUT] Interactive exploratory data analysis report
 ┗ 📜 .gitignore                         # Ignores temporary files and virtual environments
```

---

## ⚙️ Getting Started

Want to run this data pipeline on your local machine and review the exam logic? Follow these simple steps:

### 1. Clone the Repository
Open your terminal or command prompt and run:

```bash
git clone https://github.com/krish-desai-123/Data-Preprocessing-and-Feature-Engineering.git
cd Data-Preprocessing-and-Feature-Engineering
```
*Note: Adjust the path if this is located in a specific subfolder like Exam.*

### 2. Run the Code
Make sure you have Python installed. You will need Pandas, SQLite3 (built-in), ydata-profiling (for the EDA report), and Jupyter to run the notebook:

```bash
# Install required libraries
pip install pandas ydata-profiling jupyter seaborn matplotlip scikit-learn numpy

# Launch the interactive notebook
jupyter notebook
```

Open `practical_exam.ipynb` to explore the step-by-step ingestion, merging, and cleaning process!

### 3. View the Report
You don't need to run the code to see the results! Just open `eda_report.html` in your favorite web browser to view the interactive data profile of the final dataset.

---

## 👨‍💻 Author

**Krish Desai**  
GitHub: [@krish-desai-123](https://github.com/krish-desai-123)