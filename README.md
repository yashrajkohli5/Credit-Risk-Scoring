# 💳 Credit Risk Scoring Using UCI Credit Card Default Dataset

This project demonstrates an end-to-end process for credit default prediction using XGBoost on the UCI Default of Credit Card Clients dataset.

## 📁 Dataset
- Source: [UCI Repository](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)
- Records: 30,000
- Features: Demographic info, payment history, bill amounts, previous payments
- Target: `default` (1 = defaulted, 0 = paid)

## 🛠️ Technologies Used
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- xgboost
- Jupyter Notebook or any Python IDE

## 🧠 Project Workflow
1. Data Loading & Cleaning
2. Exploratory Data Analysis (EDA)
3. Advanced Feature Analysis
4. Train/Test Split
5. Modeling with XGBoost
6. Evaluation Metrics & Feature Importance
7. Business Recommendations

## 📌 How to Run
```bash
# Clone the repository
$ git clone https://github.com/yourusername/credit-risk-xgboost.git
$ cd credit-risk-xgboost

# Install dependencies
$ pip install -r requirements.txt

# Run the notebook
$ jupyter notebook
```

## 📈 Results
- Accuracy: ~81%
- Important Features: PAY_0, LIMIT_BAL, AGE, PAY_AMT1, BILL_AMT1
