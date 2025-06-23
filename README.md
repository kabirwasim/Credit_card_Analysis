# 📊 Credit Card Analysis with Python

## 🧠 Overview

The credit card industry produces massive volumes of customer data every second—from applications to spending and repayments. This project uses **data analytics** to extract meaningful insights and improve decision-making across areas like **customer behavior, fraud detection, collections, and profitability**.

PSPD Bank, operating in over 50 countries, wants to use this data to enhance its services and address key business challenges.

---

## ❗ Business Problem

To remain competitive and efficient, PSPD Bank must:

- Understand customer spending and repayment patterns.
- Detect fraudulent activity and reduce chargebacks.
- Identify high-risk customers for bankruptcy or default.
- Offer personalized solutions proactively.

The CEO, Mr. Jim Watson, seeks **data-driven answers** to strategic questions using analytics and modeling tools.

---

## 🧰 Solution Approach

### 🔹 Data Cleaning & Preprocessing

- Replace `age < 18` with the mean age value.
- If `spend > limit`, set it to **50% of the limit**.
- If `repayment > limit`, cap it to the **limit**.

### 🔹 Summary Analysis

- Number of **distinct customers**.
- Number of **distinct product categories**.
- **Average monthly spend** and **repayment**.
- **Monthly profit**:
  - `Profit = Repayment – Spend` (Interest at 2.9% applied on positive profit only).
- **Top product types**, **spending cities**, and **age group behaviors**.
- Identify **top 10 customers** by repayment.

### 🔹 Visualization & Reporting

- 📈 Monthly total spend by city.
- ✈️ Yearly spend comparison for air tickets.
- 📦 Monthly spend by product type (to identify seasonality).
- 📊 City-wise, product-wise yearly spend with graphs.

### 🔹 Dynamic Analysis Function

A **user-defined Python function** to:
- Accept parameters:
  - `Product Type (Gold/Silver/Platinum)`
  - `Time Period (Monthly/Yearly)`
- Output:
  - **Top 10 customers** by repayment for selected filters.

---

## 💡 Use Cases

- 🎯 **Targeted Marketing**: Deliver personalized offers and product recommendations.
- 🕵️ **Fraud Detection**: Identify anomalies and suspicious activity in real time.
- 📊 **Customer Segmentation**: Focus resources on high-value clients.
- 🛡️ **Collections & Risk**: Predict default risk and act early.
- 💸 **Revenue Optimization**: Promote profitable services with precision.

---


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
- ✅ **Better decisions** through real-time analytics.
- 📈 **Increased revenue** with smarter marketing and upselling.
- 🔒 **Fraud prevention** and lower chargeback rates.
- 🤝 **Enhanced customer experience** with proactive service.



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
