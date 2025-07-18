# Telco Customer Churn Prediction
    This project uses machine learning techniques to predict customer churn based on demographics, account information, and service usage patterns from a Telco company dataset.


## Dataset

- Source : Provided in `telco_churn.csv`
- Rows : ~5043, customers
- Target variable : `Churn` (Yes/No)
- Features :
  - Customer info: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - Services: `InternetService`, `PhoneService`, `OnlineSecurity`, etc.
  - Account info: `tenure`, `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`

## Models Used

- Random Forest
- XGBoost
- LightGBM

## Workflow Summary

1. Data Cleaning:
   - Handle missing values in `TotalCharges` and other columns
   - Drop rows with invalid churn values
2. Feature Encoding:
   - Label encoding for categorical features
3. Resampling:
   - Use SMOTE techniques to balance classes
4. Model Training:
   - Train multiple classifiers
   - Evaluate using accuracy, classification report, ROC-AUC

## Evaluation Metrics

- Accuracy
- ROC-AUC Score
- Classification Report (Precision, Recall, F1-Score)

## Requirements

Install dependencies:
```bash
pip install pandas numpy scikit-learn xgboost lightgbm imbalanced-learn



