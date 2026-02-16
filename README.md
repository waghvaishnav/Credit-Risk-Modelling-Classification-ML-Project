# Credit-Risk-Modelling-Classification-ML-Project
Developed a machine learning model to predict loan default risk using financial and behavioral customer data.

# Credit Risk Modeling Project

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

- Credit utilization ratio
- Delinquent months
- Total DPD (days past due)
- Enquiry count
- Income & repayment behavior

Target variable:
- Default / Non-default

---

## ⚙️ Project Workflow
1. Data cleaning & preprocessing
2. Exploratory data analysis (EDA)
3. Feature engineering
4. Model training (Logistic Regression / XGBoost)
5. Model evaluation (ROC-AUC, KS, Gini)
6. Model serialization
7. Streamlit deployment

---

## 📈 Model Performance
- ROC-AUC: XX%
- KS Score: XX
- Gini Score: XX

(The model shows strong ranking ability in separating risky customers.)

---

## 🚀 Deployment
The trained model is deployed using Streamlit.

Run locally:

```bash
pip install -r requirements.txt
streamlit run app.py

