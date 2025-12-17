# 📊 Customer Churn Prediction Using Machine Learning

## 📌 Project Overview
Customer churn refers to customers discontinuing a service. Predicting churn in advance helps businesses take preventive actions such as targeted offers and improved customer support.

This project builds a **machine learning–based churn prediction system** using a telecom customer dataset. It covers the **complete ML workflow**, including data cleaning, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

---

## 🎯 Problem Statement
To predict whether a customer is likely to **churn (leave the service)** based on historical customer behavior and service usage patterns.

---

## 📂 Dataset Description
- **Dataset Name:** Telecom Churn Dataset  
- **Source:** Public Telecom Dataset (BigML / Kaggle)  
- **Total Records:** 667  
- **Total Features:** 20  

Each row represents a telecom customer and their service usage information.

---

## 🔑 Target Variable
- **Churn**
  - `1` → Customer churned
  - `0` → Customer retained

---

## 📌 Features Included
- State  
- Account length  
- Area code  
- International plan  
- Voice mail plan  
- Number of voice mail messages  
- Total day, evening, night & international minutes  
- Total day, evening, night & international calls  
- Total charges  
- Customer service calls  

---

## 🛠️ Tools & Technologies Used
- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to identify churn patterns and customer behavior trends:
- Churn distribution analysis
- International plan vs churn
- Customer service calls vs churn
- Account length comparison

### 📌 Key Insights
- Customers with **international plans** show higher churn rates
- Higher **customer service calls** strongly correlate with churn
- Customers with shorter account tenure are more likely to churn

---

## 🧹 Data Preprocessing
- Removed irrelevant columns
- Handled missing and inconsistent values
- Converted categorical variables into numerical format
- Standardized numerical features using `StandardScaler`
- Split data into training and testing sets

---

## 🤖 Machine Learning Models Implemented

### 1️⃣ Logistic Regression
- Baseline classification model
- Simple and interpretable

### 2️⃣ Random Forest Classifier
- Ensemble learning technique
- Handles non-linear relationships effectively

---

## 📈 Model Evaluation
Models were evaluated using:
- Accuracy
- Recall
- ROC-AUC Score


---

## 📌 Results & Conclusion
- Random Forest outperformed Logistic Regression
- Customer service interactions are the strongest predictor of churn
- The model can assist telecom companies in customer retention strategies

This project demonstrates a **real-world application of machine learning** in customer analytics.
