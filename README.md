# Churn-Prediction# Bank Customer Churn Prediction

## 1. Project Overview
Bank Customer Churn Prediction is a Machine Learning project that predicts whether a bank customer will continue using the bank's services or leave the bank.

The project analyzes customer details, account information, and transaction behavior to identify customers who are likely to leave.

## 2. Business Context
Banks need to identify customers who may stop using their services. Early identification helps banks take suitable steps to improve customer satisfaction and customer retention.

## 3. Objectives
- Predict customer churn.
- Identify customers who may leave the bank.
- Analyze customer demographics and transaction behavior.
- Understand factors associated with customer attrition.
- Compare different Machine Learning classification algorithms.

## 4. Dataset Description
The dataset contains bank customer information.

Important columns include:

| Column | Description |
|---|---|
| CLIENTNUM | Customer identification number |
| Attrition_Flag | Customer status |
| Customer_Age | Customer age |
| Gender | Customer gender |
| Education_Level | Education category |
| Marital_Status | Marital status |
| Income_Category | Income category |
| Card_Category | Card type |
| Credit_Limit | Credit limit |
| Total_Trans_Amt | Total transaction amount |
| Months_Inactive_12_mon | Inactive months in the last 12 months |

**Target Variable:**
- 0 – Existing Customer
- 1 – Attrited Customer

## 5. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 6. Machine Learning Algorithms
### 1. Decision Tree Classifier
Creates a tree-like structure using customer features to classify customers.

### 2. Random Forest Classifier
Combines multiple decision trees to improve prediction stability and performance.

### 3. Gradient Boosting Classifier
Builds decision trees sequentially, with each new tree learning from previous errors.

## 7. Project Workflow
1. Import Required Libraries
2. Load Dataset
3. Data Overview
4. Data Cleaning and Inspection
5. Univariate Analysis
6. Bivariate Analysis
7. Categorical Variable Encoding
8. Train-Test Split
9. Model Building
10. Model Prediction
11. Model Evaluation
12. Model Comparison

## 8. Data Visualization
The project uses:
- Count Plot
- Box Plot
- Bar Chart
- Bivariate Analysis Charts

These visualizations help understand customer distributions and relationships between customer features and churn.

## 9. Model Evaluation Metrics
The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

These metrics help compare training and testing performance.

## 10. Expected Output
The trained models classify customers into two categories:

- Existing Customer
- Attrited Customer

The model comparison helps identify a suitable classifier for predicting customer churn.

## 11. Conclusion
This project demonstrates how Machine Learning classification algorithms can be used to predict bank customer churn. It helps identify customers who may leave and supports better customer-retention decisions.

---

**Project Name:** Bank Customer Churn Prediction

**Domain:** Machine Learning

**Problem Type:** Classification

**Algorithms:** Decision Tree, Random Forest, Gradient Boosting
