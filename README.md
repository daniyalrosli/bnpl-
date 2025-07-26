# 💳 BNPL Credit Risk Analyzer

A machine learning project that helps financial institutions decide whether a customer is eligible for Buy Now, Pay Later (BNPL) based on their credit risk.

---

## 🔍 Project Goal

To build a model that predicts if a customer is risky or not, using real-world financial data. This helps reduce the chances of default and improves BNPL approval decisions.

---

## 📊 Dataset

We use real-world data from:
- [LendingClub Loan Dataset (Kaggle)](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
- Or [Home Credit Default Risk (Kaggle)](https://www.kaggle.com/competitions/home-credit-default-risk/data)

Main features:
- Income, credit score, loan amount
- Employment status, debt-to-income ratio
- Repayment history, purpose of loan

---

## 🧠 Models Used

- Logistic Regression
- Random Forest ✅
- XGBoost
- Model Explainability (SHAP – optional)

Evaluation metrics:
- Accuracy
- Precision & Recall
- AUC-ROC

---

## 🖥️ Streamlit App

A simple app where users can enter customer details and see if they are eligible for BNPL.

### How to Run:
```bash
pip install -r requirements.txt
streamlit run app/streamlit_app.py
