# Customer Churn Analysis and Prediction

## Overview

This project analyzes customer behavior and predicts customer churn using Machine Learning techniques. The goal is to identify customers who are likely to leave a telecom service provider so that businesses can take proactive retention measures.

## Objectives

* Perform data cleaning and preprocessing
* Conduct exploratory data analysis (EDA)
* Visualize customer churn patterns
* Apply SQL queries for business insights
* Build and evaluate machine learning models
* Predict customer churn accurately

## Dataset

**Dataset:** Telco Customer Churn Dataset

**Source:** Kaggle

The dataset contains customer information such as:

* Gender
* Senior Citizen Status
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn Status

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SQL
* Jupyter Notebook

## Project Workflow

### 1. Data Collection

The Telco Customer Churn dataset was loaded and examined.

### 2. Data Cleaning

* Checked missing values
* Checked duplicate records
* Converted TotalCharges to numeric format
* Prepared data for analysis

### 3. Exploratory Data Analysis (EDA)

* Churn distribution analysis
* Contract type analysis
* Monthly charges analysis
* Tenure analysis
* Internet service analysis

### 4. Data Visualization

Various visualizations were created to identify patterns and trends related to customer churn.

### 5. Machine Learning Models

#### Logistic Regression

Accuracy: **78.54%**

#### Random Forest Classifier

Accuracy: **79.25%**

Random Forest achieved the best performance and was selected as the final model.

## Project Structure

```text
Customer_Churn_Analysis_and_Prediction/

├── data/
│   └── Telco-Customer-Churn.csv
│
├── churn_analysis.ipynb
│
├── churn_queries.sql
│
├── churn_model.pkl
│
└── README.md
```

## Key Findings

* Customers with month-to-month contracts are more likely to churn.
* Customers with shorter tenure have higher churn rates.
* Monthly charges have a significant impact on churn behavior.
* Contract type is one of the most important factors influencing churn.

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 78.54%   |
| Random Forest       | 79.25%   |

## Future Improvements

* Hyperparameter tuning
* Advanced feature engineering
* Deployment using Streamlit
* Real-time customer churn prediction

## Author

**Obaid Ashraf**

GitHub: **obaidashraf07**
