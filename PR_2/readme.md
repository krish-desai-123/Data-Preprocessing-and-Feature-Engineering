<div align="center">

# 🧼 Data Cleansing: Patient Records 🏥

**An end-to-end data preprocessing pipeline transforming raw, messy healthcare datasets into structured, analysis-ready formats.**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Data Cleaning](https://img.shields.io/badge/Data_Cleaning-success?style=for-the-badge)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](#)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)](#)

</div>

<br>

## 🌟 About the Project

Real-world healthcare data is notoriously messy, filled with missing values, inconsistent formatting, and outliers. This project demonstrates a robust, automated approach to data purification. By utilizing Python and Pandas within a Jupyter Notebook environment, this repository takes a raw dataset of patient health records and applies industry-standard preprocessing techniques to generate a clean, reliable dataset primed for exploratory data analysis (EDA) and machine learning modeling.

### 🎯 Key Objectives
* **Data Standardization:** Correcting structural errors, standardizing text formatting, and ensuring consistent data types across all columns.
* **Missing Value Treatment:** Identifying NaN/Null values and applying appropriate imputation strategies (mean/median/mode filling or algorithmic imputation) without introducing bias.
* **Outlier Management:** Detecting statistical anomalies and safely handling them to prevent skewed analytical results.
* **Feature Optimization:** Dropping redundant columns and renaming features for better readability and downstream processing.

---

## 🛠️ Technologies & Tools

* **Programming Language:** Python 3.x
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning & Preprocessing:** Scikit-Learn (sklearn)
* **Environment:** Jupyter Notebook
* **Version Control:** Git & GitHub

---

## 📂 Repository Architecture
```text
📦 PR_2
 ┣ 📜 data_cleanser.ipynb                    # The core Jupyter Notebook containing the step-by-step cleaning logic
 ┣ 📜 patient_health_records.csv             # [INPUT] The raw, unprocessed health records dataset
 ┣ 📜 final_clean_patient_health_records.csv # [OUTPUT] The final, sanitized, and standardized dataset
 ┗ 📜 readme.md                             # This file
```

## 🔍 The Cleaning Pipeline

If you explore the `data_cleanser.ipynb` notebook, you will see the process broken down into the following logical steps:

1. **Data Ingestion:** Loading the raw `.csv` file and performing an initial `shape` and `info()` inspection.
2. **Structural Assessment:** Checking for duplicate rows and dropping them to ensure data uniqueness.
3. **Handling Missing Data:** Mapping out the percentage of missing data per feature and applying targeted imputation rules based on the data type (categorical vs. numerical).
4. **Data Type Conversion:** Casting features (like dates, IDs, or categorical flags) into their proper pandas data types for optimized memory usage.
5. **Sanitization:** Stripping whitespace, standardizing capitalization, and fixing known typos in categorical string columns.
6. **Export:** Saving the finalized dataframe to `final_clean_patient_health_records.csv` while dropping the index.

---

## ⚙️ Getting Started & Installation

To run this pipeline locally and experiment with the data, follow these steps:

### 1. Clone the Repository
Open your terminal and pull down the project:
```bash
git clone https://github.com/krish-desai-123/Data-Preprocessing-and-Feature-Engineering.git
cd Data-Preprocessing-and-Feature-Engineering/PR_2
```

### 2. Set Up a Virtual Environment (Recommended)
It's best practice to run this in an isolated environment.
```bash
# Create a virtual environment
python -m venv venv

# Activate it
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
Install the required data science and visualization libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch the Notebook
Start the Jupyter server to interact with the code:
```bash
jupyter notebook
```

Navigate to `data_cleanser.ipynb` in your browser, run the cells sequentially, and watch the raw data transform!

---


## 👨‍💻 Author

**Krish Desai**

* GitHub: [@krish-desai-123](https://github.com/krish-desai-123)

---

<div align="center">
<i>If this repository helped you understand data preprocessing better, consider dropping a ⭐!</i>
</div>