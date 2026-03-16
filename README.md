Credit Card Fraud Detection — Exploratory Data Analysis

Project Overview
This project performs exploratory data analysis (EDA) on a real-world credit card transaction dataset. The goal of the analysis is to understand patterns in transaction behavior and investigate characteristics that may help distinguish fraudulent transactions from legitimate ones.

The dataset contains anonymized financial transaction data where most features have been transformed using Principal Component Analysis (PCA) to protect sensitive information.

---

Dataset Description

The dataset contains 284,807 credit card transactions and 31 columns.

Features include:

- Time — Seconds elapsed between each transaction and the first transaction
- V1–V28 — PCA-transformed anonymized features representing transaction characteristics
- Amount — Transaction amount
- Class — Target variable indicating fraud status  
  - 0 → Normal transaction  
  - 1 → Fraudulent transaction

The dataset is **highly imbalanced**, with fraudulent transactions representing only **0.17% of the total data**.

---

Objectives

The main goals of this analysis are:

- Understand the structure of the dataset
- Identify missing values and data quality issues
- Analyze the distribution of transaction amounts
- Compare fraud and normal transactions
- Study relationships between variables using correlation analysis
- Detect potential outliers in transaction amounts

---

Exploratory Analysis Steps

The analysis follows these steps:

1. Import required libraries
2. Load and inspect the dataset
3. Perform data overview and summary statistics
4. Check for missing values
5. Analyze feature distributions
6. Compare fraud vs non-fraud transactions
7. Examine correlations between variables
8. Detect outliers in transaction amounts
9. Summarize key insights from the analysis

---

Key Insights

- The dataset contains **284,807 transactions** with **31 variables**.
- Fraudulent transactions account for only **0.17% of the data**, making the dataset highly imbalanced.
- Most transactions are relatively small, with an average transaction amount of approximately **$88**.
- The transaction amount distribution is **right-skewed**, meaning most transactions are small while a few are very large.
- Correlation analysis shows weak relationships between most features due to PCA transformation.
- No single feature strongly correlates with fraud, indicating that fraudulent activity is identified through patterns across multiple variables.
- Only a few transactions exceed **$15,000**, appearing as outliers in the dataset.

---

Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn

---

How to Run the Project

1. Clone the repository
2. Install required libraries
3. Open the Jupyter Notebook
4. Run the notebook cells sequentially

---

Author

Data analysis project focused on financial fraud detection and exploratory data analysis.
