# 💳 Credit Risk Modeling Using Machine Learning

## 📌 Project Overview
Credit risk modeling is a critical task in the banking and financial sector. This project aims to **predict whether a customer is credit risky or credit worthy** by analyzing **transaction behavior and demographic attributes**.

The project uses **two datasets** — customer payment history and demographic data — and applies machine learning techniques to build an accurate and explainable credit risk prediction system.

---

## 🎯 Objective
To assess the **creditworthiness of customers** and classify them as:
- **High Credit Risk (1)**
- **Low Credit Risk (0)**

This helps banks reduce default risk and make better lending decisions.

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was conducted to identify patterns influencing credit risk.

### Key Insights:
- Customers with **higher overdue counts** are more likely to be risky
- **Total overdue days** strongly correlate with credit risk
- Credit-worthy customers show **more regular payment behavior**
- Risky customers tend to maintain **higher balances**

---

## ⚖️ Handling Imbalanced Data
The dataset is **imbalanced**, with fewer high-risk customers.

### Solution:
- Applied **SMOTE (Synthetic Minority Over-sampling Technique)**
- Balanced the training dataset
- Improved recall for high-risk customer prediction

---

## 🧹 Data Preprocessing
- Removed irrelevant ID and date columns
- Handled missing values
- Converted categorical variables using one-hot encoding
- Standardized numerical features using `StandardScaler`
- Split data into training and testing sets

---

## 🤖 Machine Learning Models Used

### 1️⃣ Logistic Regression
- Baseline model widely used in banking
- Highly interpretable
- Performs well with standardized features

### 2️⃣ Decision Tree Classifier
- Captures non-linear patterns
- Rule-based and easy to interpret

---

## 📈 Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall (important for detecting risky customers)
- F1-score
- ROC-AUC Score
  
---

## 🔍 Model Explainability (SHAP)
To ensure transparency in predictions:
- SHAP (SHapley Additive exPlanations) was used
- Identified top features contributing to credit risk:
  - Overdue frequency
  - Total overdue days
  - Credit limit utilization
  - Payment regularity

This makes the model suitable for **banking and regulatory requirements**.
