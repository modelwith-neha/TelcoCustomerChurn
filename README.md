# 📞 Telco Customer Churn Prediction

**Author**: Neha Tiwari  
**Dataset**: Telco Customer Churn – [source: IBM Sample Dataset]  
**Objective**: Predict whether a customer will churn (i.e., stop using services) based on demographic, usage, and service features  
**Problem Type**: Supervised Classification  
**Tools**: Python, Pandas, Scikit-learn, Seaborn, Matplotlib, Logistic Regression, XGBoost

---

## 📌 Project Overview

Churn is a critical business metric for telecom providers. This project uses a structured dataset of Telco customers to build a classification model that predicts churn and identifies key factors contributing to customer attrition.

---

## 📁 Dataset Summary

- **Rows**: ~7,000 customers  
- **Features**:
  - Customer demographics (gender, age, senior citizen)
  - Account info (tenure, contract type, monthly charges)
  - Services used (phone, internet, streaming)
  - Payment methods
  - Target: `Churn` (Yes/No)

---

## 🔍 Workflow Summary

### 1. **Data Preprocessing**
- Removed duplicates and handled missing values
- Converted categorical variables using one-hot encoding
- Standardized numerical features
- Target encoded as binary (Yes = 1, No = 0)

### 2. **Exploratory Data Analysis (EDA)**
- Visualized churn distribution
- Correlation heatmaps and boxplots
- Identified high-risk churn groups (e.g., month-to-month contracts)

### 3. **Modeling**
- Logistic Regression
- Decision Trees
- XGBoost Classifier
- Used cross-validation for performance tuning
- Evaluated via accuracy, precision, recall, F1-score, AUC

---

## ✅ Key Results

- **Best Model**: XGBoost  
- **AUC**: ~0.88  
- **Top Predictors**:
  - Contract type
  - Tenure
  - Monthly charges
  - Payment method
  - Internet service

---

## 📊 Visual Insights
- High churn observed among customers with short tenure and month-to-month contracts
- Customers paying via electronic check showed higher churn rates

---

## 📂 Repository Contents

- `HandsOn4.ipynb` — Full notebook with code, analysis, and model output  
- `telco_customer_churn.csv` — Dataset used for the project  
- `README.md` — Overview and documentation  

---

## 📬 Contact

For feedback or collaboration, connect on [LinkedIn](https://www.linkedin.com/in/neha-tiwarii/)

---
