# E-commerce Spending Prediction

This project aims to predict the yearly amount spent by customers on an e-commerce website based on various user behavior metrics. Using a linear regression model, we explore which features are the most influential in predicting customer spending.

## 📌 Objective

To build a regression model that predicts the yearly amount a customer spends on the website using features such as:
- Time spent on website
- Time spent on mobile app
- Length of membership
- Average session length

## 📊 Dataset

- The dataset contains customer information like:
  - Average Session Length
  - Time on App
  - Time on Website
  - Length of Membership
  - Yearly Amount Spent (target)
- Source: [Dummy/Generic E-commerce dataset] (Typically used in ML tutorials)

## 🔧 Tools & Technologies

- Python  
- Jupyter Notebook  
- Pandas & NumPy (Data Analysis)  
- Seaborn & Matplotlib (Data Visualization)  
- Scikit-learn (Modeling and Evaluation)

## 📈 Workflow

1. **Data Loading and Exploration**
   - Checked for null values and basic statistics.
   - Explored feature relationships using Seaborn pairplots and correlation heatmaps.

2. **Visualization**
   - Compared time spent on app vs. website.
   - Analyzed which feature has stronger correlation with yearly spend.

3. **Model Building**
   - Applied Linear Regression using Scikit-learn.
   - Trained the model using the training data and evaluated it on the test set.

4. **Model Evaluation**
   - Visualized residuals.
   - Measured R² score and interpreted regression coefficients.

## 📌 Key Insights

- **Time on App** had a stronger correlation with spending than **Time on Website**.
- **Length of Membership** was one of the strongest predictors of customer spending.
- The model gave a good fit with minimal residual error and high R² value.

