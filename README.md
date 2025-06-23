# 🔍 Logistic Regression – Bank Loan Prediction

## 📘 Overview

This project uses **Logistic Regression** to analyze customer data from a bank loan dataset and predict loan repayment behavior. The goal is to build a classification model that can help the bank decide whether to approve or reject loan applications based on customer attributes.

---

## ❗ Business Problem

Banks need to assess the risk of default before issuing loans. Poor credit decisions can lead to losses, while overly strict policies may reduce business.

**Key Challenges:**
- Predict whether a customer will repay a loan.
- Understand what factors influence repayment decisions.
- Prevent losses due to defaults.

---

## 🧰 Solution Approach

### 📦 Data Preparation
- Load datasets: Customer acquisition, transaction (spend), and repayment.
- Handle data issues:
  - Replace invalid age values.
  - Cap spend/repayment if they exceed limits.

### 🔍 Exploratory Data Analysis (EDA)
- Analyze customer behavior: Age group, city-wise spend, product type.
- Understand spending patterns and repayment trends.

### 📈 Feature Engineering
- Derive new features from transactional data.
- Normalize or encode variables as needed.

### 🧠 Logistic Regression Modeling
- Build model using `statsmodels` and `sklearn`.
- Split data into training and test sets.
- Fit the model and analyze coefficients.

### ✅ Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report
- ROC-AUC Score

---

## 💼 Use Cases

- 🏦 **Loan Approval System** – Assist bank officers in deciding loan eligibility.
- 🔍 **Customer Risk Profiling** – Identify high-risk customers proactively.
- 📊 **Credit Scoring Models** – Incorporate insights into broader credit evaluation.

---

## 🌍 Impact

- ✅ **Reduced default rate** by making informed loan decisions.
- 📈 **Improved profitability** through smarter lending.
- 👥 **Better customer targeting** for financial products.

---

## 🧪 Technologies Used

- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn
- Modeling: `statsmodels`, `scikit-learn`
- Evaluation: Confusion matrix, ROC, Accuracy score

---

## 📁 Folder Structure

This analysis uses three datasets:

1. **Customer Acquisition** – Information collected at the time of card issue.
2. **Spend Transactions** – Monthly spending per customer.
3. **Repayments** – Monthly repayment details per customer.

---

## 📌 Getting Started

1. Load and clean the datasets.
2. Perform required summaries and visualizations.
3. Use the provided Python function for dynamic filtering.
4. Generate insights and recommendations.

---
