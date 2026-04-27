# Credit-Risk-Modelling-Classification-ML-Project
Developed a machine learning model to predict loan default risk using financial and behavioral customer data.

# Credit Risk Modeling Project

![Credit Risk Model](https://github.com/waghvaishnav/Credit-Risk-Modelling-Classification-ML-Project/blob/4d2a9a12706524146e40009b63b3d216f5171837/Screenshot%202026-04-27%20180354.png?raw=true)

## 📌 Overview
This project builds a machine learning model to predict credit default risk using historical customer financial data. The goal is to help financial institutions identify high-risk applicants and improve lending decisions.

The project covers the full ML lifecycle: data preprocessing, feature engineering, model training, evaluation, and deployment.

---

## 🎯 Problem Statement
Banks face losses due to customer loan defaults. This project predicts whether a customer is likely to default using supervised machine learning techniques.

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Streamlit (for deployment)
- Joblib (model saving)
-matplotlib / seaborn
---

## 📊 Dataset
The dataset contains customer credit information such as:
- age
- income
- loan_amount
- loan_to_income_ratio
- loan_tenure(momnths)
- avg_dpd
- deliquency_ratio
- credit_utilization_ratio
- open_loan_amount
- residence_type
- loan_purpose
- loan_type

Target variable:
- Default / Non-default

---

## ⚙️ Project Workflow
1. Data cleaning & preprocessing
2. Exploratory data analysis (EDA)
3. Feature engineering(weight of evaluation / information value)
4. Model training (Logistic Regression / XGBoost)
5. Model evaluation (ROC-AUC, KS, Gini)
6. Model serialization
7. Streamlit deployment

---

## 📈 Model Performance
- ROC-AUC: 98 %


## 🚀 Deployment
The trained model is deployed using Streamlit.


