Machine Learning Projects

This repository contains two supervised learning projects using real-world datasets:

1. California Housing Price Prediction – Linear Regression
2. Telco Customer Churn Prediction – Classification with Logistic Regression and K-Nearest Neighbors (KNN)

---

Project 1: California Housing Price Prediction

Dataset: California Housing from the 1990 US Census  
Source: `sklearn.datasets.fetch_california_housing()`

Model Used:
- Linear Regression

Evaluation Metric:
- Mean Squared Error (MSE) on test data

Steps:
- Loaded dataset with 8 numeric features and 1 target: `MedHouseVal`
- Split data into training and test sets
- Trained a linear regression model
- Computed Mean Squared Error (MSE) on predictions

---

Project 2: Telco Customer Churn Prediction

Dataset: `telco_churn.csv`  
Source: IBM Sample Dataset

Models Used:
- Logistic Regression
- K-Nearest Neighbors (KNN)

Preprocessing:
- Removed ID columns
- Converted `TotalCharges` to numeric
- Filled missing values
- Used one-hot encoding for categorical variables
- Standardized numeric features

Evaluation Metrics:
- Confusion Matrix
- Classification Report: Precision, Recall, F1-score, Accuracy

Target Variable:
- `Churn` → whether the customer canceled service