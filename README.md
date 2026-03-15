# Customer Churn Analysis

## Project Overview

Customer churn is a critical problem for subscription-based businesses. Retaining existing customers is often more cost-effective than acquiring new ones.

This project performs an end-to-end data analysis and predictive modeling workflow to identify customers who are likely to churn.

The goal is to help businesses detect churn risk early and take preventive actions.

---

## Project Objectives

- Understand customer behavior and churn patterns
- Perform exploratory data analysis (EDA)
- Clean and prepare raw customer data
- Visualize churn patterns across customer segments
- Build a machine learning model to predict churn
- Evaluate model performance using ROC Curve

---
## Full Analysis Report
You can view the full interactive notebook report here:

https://github.com/irfankafait/customer-churn-analysis/blob/reports/Customer_churn_analysis.html

---
## Dataset

The dataset contains information about customer demographics, service usage, and subscription details.

Key features include:

- Customer tenure
- Contract type
- Monthly charges
- Total charges
- Internet service type
- Payment method
- Customer churn status

---

## Project Workflow

### 1. Data Collection
Raw customer churn dataset was loaded for analysis.

### 2. Data Cleaning
- Handled missing values
- Converted data types
- Removed inconsistencies

Clean dataset saved as:
customer_churn_cleaned.csv

### 3. Exploratory Data Analysis

Key analyses performed:

- Churn distribution
- Contract type vs churn
- Customer tenure analysis
- Service usage patterns

Visualization example:

![Churn by Contract](images/churn_by_contract.png)
![Confusion_Matrix](images/Confusion_Matrix.png)
![Feature_Correlation_Matrix_heatmap](images/Feature_Correlation_Matrix_heatmap.png)
![ROC_Curve](images/ROC_Curve.png)

### 4. Predictive Modeling

A machine learning classification model was trained to predict churn probability.

Evaluation metrics used:

- ROC Curve
- Model accuracy

---

## Results

The analysis shows strong churn correlation with:

- Contract type
- Monthly charges
- Customer tenure

Customers with **month-to-month contracts** and **high monthly charges** show higher churn probability.

---

## Technologies Used

Python  
Pandas  
NumPy  
Matplotlib  
Scikit-learn  
Jupyter Notebook  

---

## Project Structure
customer-churn-analysis
│
├── data
├── notebooks
├── reports
├── images
└── README.md

---
## Key Insights

- Customers with month-to-month contracts have the highest churn rate.
- Higher monthly charges are associated with increased churn probability.
- Customers with longer tenure are less likely to churn.

## How to Run the Project

1. Clone the repository
https://github.com/irfankafait/customer-churn-analysis.git

2. Install dependencies
pip install -r requirements.txt

3. Open the notebook
jupyter notebook

---

## Author

Arfan Chaudhry  
Data Analyst | Python | Data Visualization
