# 💳 Credit Scoring Model using Random Forest

This project builds a machine learning model to predict an individual's creditworthiness using historical financial data from the German Credit dataset.

## 📌 Objective
To classify whether a person is creditworthy based on features like income, debts, and payment history.

---

## 🧠 Approach
- **Preprocessing**:
  - One-hot encoding of categorical variables
  - Train-test split (80/20)
- **Model**: Random Forest Classifier with 100 estimators
- **Evaluation**:
  - Classification report (Precision, Recall, F1-Score)
  - ROC-AUC Score
  - Feature importance analysis

---

## 📁 Dataset
- **Source**: `german.csv` (semicolon-separated)
- **Target Variable**: `Creditability` (1 = creditworthy, 0 = not creditworthy)
- **Features**: Demographic and financial attributes

---

## 🧪 Features
- One-hot encoded categorical variables
- Random Forest model trained on 80% of the data
- Top 5 most influential features identified

---

## 📊 Results
- **ROC-AUC Score**: ~`XX.XX` *(replace with your actual result)*
- **Top Risk Factors**:
  - Feature 1
  - Feature 2
  - Feature 3
  - Feature 4
  - Feature 5  
*(Replace with actual feature names from your output)*

---

## 🧰 Libraries Used
- `pandas`, `numpy`, `matplotlib`
- `sklearn` for modeling and evaluation

---

## 🚀 How to Run
1. Clone the repo
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
##  Run using
   python credit_scoring.py
