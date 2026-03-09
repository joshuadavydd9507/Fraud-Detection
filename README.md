# Fraud Detection Exploratory Data Analysis
Project Overview

This project explores a synthetic banking transaction dataset to identify behavioural patterns associated with fraudulent transactions. The analysis focuses on understanding which transaction characteristics are most strongly related to fraud occurrence through structured exploratory data analysis (EDA).

The goal of the project is to demonstrate a practical workflow for data cleaning, exploratory analysis, feature investigation, and fraud risk identification.

Dataset

The dataset contains 50,000 banking transactions with variables describing transaction characteristics, customer behaviour, and fraud indicators.

Example features include:

Transaction amount

Distance from customer home location

International transaction flag

Merchant novelty indicator

Failed transaction attempts

Previous fraud history

The target variable is:

Fraud_Label

which identifies whether a transaction is fraudulent or legitimate.

Methodology

The analysis follows a structured EDA workflow:

Data Overview

Data Quality Assessment

Data Cleaning

Exploratory Data Analysis

Behavioural Pattern Investigation

Multivariate Feature Analysis

Key Insight Summary

Techniques used include:

descriptive statistics

grouped aggregation

cross-tab analysis

distribution visualisation

correlation analysis

Key Findings
Fraud prevalence

Fraudulent transactions represent approximately 4–5% of the dataset, indicating a moderately imbalanced dataset.

Transaction amount

Transaction amount distributions are nearly identical for fraudulent and legitimate transactions, suggesting transaction value alone is not a reliable fraud indicator.

Distance from home

Distance from the customer’s home location shows very similar distributions across fraud and normal transactions, indicating minimal predictive value in this dataset.

International transactions

International transactions exhibit significantly higher fraud rates compared to domestic transactions:

Domestic fraud rate ≈ 3–4%
International fraud rate ≈ ~6%

This suggests international transactions represent elevated fraud risk.

Merchant novelty

Transactions with new merchants do not show a strong independent relationship with fraud risk.

Combined risk signals

The highest fraud rate occurs when transactions are both international and involve new merchants, although the increase appears primarily driven by international transaction status.

Tools & Libraries

Python libraries used:

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Project Skills Demonstrated

This project demonstrates practical skills in:

Data cleaning

Exploratory data analysis

Feature investigation

Behavioural pattern detection

Fraud risk segmentation

Data visualisation

Analytical interpretation
