# Loan Approval Prediction (Machine Learning Project)

## 🧠 Overview
This project builds a machine learning model to predict whether a loan application should be approved or rejected using applicant demographic and financial data.

## 📊 Dataset
- Source: Custom CSV (`loan_approval_dataset.csv`)
- Features: Applicant income, loan amount, term, CIBIL score, assets, etc.
- Target: Loan status (`Approved` / `Rejected`)

## ⚙️ Methodology
- Data cleaning & preprocessing (missing values, encoding)
- Feature engineering (Debt-to-Income ratio)
- Models trained: Logistic Regression, Random Forest
- Evaluation metrics: Accuracy, F1-score, ROC-AUC
- Best model saved as `best_loan_model.joblib`

## 🚀 How to Run
1. Open `Loan Approval Prediction.ipynb` in Jupyter Notebook or VS Code.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run all cells — choose your dataset file when prompted.
4. View metrics, confusion matrix, and saved model file.

## 📈 Results
- Model Accuracy: ~XX%
- F1 Score: ~XX%
- ROC-AUC: ~XX%

## 📩 Contact
Project Author: Harsh
