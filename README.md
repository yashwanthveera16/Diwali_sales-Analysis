# Diwali_sales-prediction
# Diwali Sales Analysis and Purchase Prediction (Machine Learning)

## Project Overview
This project analyzes customer purchase behaviour during Diwali festival sales and builds a Machine Learning model to predict how much a customer is likely to spend based on their characteristics.

The project demonstrates the complete Data Science workflow including data cleaning, exploratory data analysis, feature engineering, model building, evaluation and prediction.

---

## Problem Statement
Businesses want to understand customer purchasing behaviour during festival seasons to improve marketing strategies and increase revenue.

Goal of this project:
- analyze customer purchase patterns
- identify important factors affecting spending
- predict purchase amount for new customers

---

## Dataset Description
The dataset contains 11,000+ records of customer purchases during Diwali sales.

Features included:
- Gender
- Age
- Marital Status
- State
- Zone
- Occupation
- Product Category
- Number of Orders
- Purchase Amount

---

## Steps Performed

### 1. Data Cleaning
- removed null values
- dropped unnecessary columns
- converted data types

### 2. Exploratory Data Analysis (EDA)
Analyzed customer behaviour using visualizations:
- spending based on gender
- spending based on age group
- top states contributing to sales
- occupation-wise spending
- product category performance

### 3. Feature Engineering
Converted categorical features into numerical format for machine learning.

### 4. Model Building
Used Random Forest Regressor to predict purchase amount.

### 5. Model Evaluation
Evaluated model performance using:
- Mean Absolute Error (MAE)
- R² Score

### 6. Prediction
Model can predict expected purchase amount for new customers based on their characteristics.

---

## Key Insights
- Product category strongly influences purchase amount
- Age group 26–35 shows higher spending behaviour
- Certain occupations contribute higher purchase value
- Married customers show higher purchasing trend

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- random forest regression
- Jupyter Notebook
- VS Code

 ---

---

## Conclusion
This project demonstrates how machine learning can be used to predict customer spending behaviour based on demographic and product information.

The model can help businesses identify potential high-value customers and optimize marketing strategies.

---

## Future Improvements
- include customer income data
- include product price details
- try advanced models like XGBoost
- deploy as web application
