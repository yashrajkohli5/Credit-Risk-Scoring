# 🏦 Credit Risk Scoring - Loan Default Prediction

This project demonstrates a complete data analytics and machine learning pipeline for credit risk scoring. We use the XGBoost model to predict the likelihood of a loan applicant defaulting based on financial and demographic features.

## 📁 Dataset
- Sample dataset: `credit_data.csv`
- Features: Income, employment, loan amount, credit score, purpose, etc.
- Target: `loan_status` (e.g., Fully Paid / Default)

## 🧰 Technologies Used
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost
- Jupyter Notebook or VS Code

## 🧠 Problem Statement
Given a dataset of past loans, predict whether a new applicant is likely to default on the loan.

## 🚀 How to Run
```bash
# Clone the repo
$ git clone https://github.com/yourusername/credit-risk-scoring.git
$ cd credit-risk-scoring

# Install dependencies
$ pip install -r requirements.txt

# Run the notebook or script
$ jupyter notebook Credit_Risk_Scoring.ipynb
```

## 📈 Key Results
- Model Used: XGBoost
- Accuracy: ~85% (varies by data)
- Most important features: Credit Score, Income, Loan Amount, Employment

## 💡 Recommended Models for Credit Risk
- XGBoost (used here)
- Logistic Regression (baseline)
- LightGBM (similar to XGBoost)
- Random Forest
