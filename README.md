# Customer Churn Analysis Using Python

## Overview

This project analyzes customer churn behavior using Python, Pandas, Matplotlib, and Scikit-Learn. The dataset contains 64,374 customer records and 12 variables related to demographics, subscription behavior, payment history, support interactions, and churn status.

The goal was to identify the primary drivers of customer churn and build a machine learning model capable of predicting customer attrition.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

## Key Findings

* Overall churn rate: **47.37%**
* Monthly contract customers exhibited the highest churn rate.
* Customers with 5 or more support calls showed significantly higher churn risk.
* Payment delays greater than approximately 15 days were strongly associated with churn.
* Higher usage frequency was associated with lower churn rates.

## Machine Learning Model

A Logistic Regression model was developed to predict customer churn.

### Model Performance

* Accuracy: **83.16%**
* Precision: **82%**
* Recall: **83%**
* F1 Score: **82%**

### Top Predictors of Churn

1. Monthly contract length
2. Number of support calls
3. Payment delay

## Business Recommendations

* Encourage migration from monthly to annual contracts.
* Improve first-contact resolution in customer support.
* Monitor customers with increasing payment delays.
* Implement retention campaigns for high-risk customers.
* Increase engagement among low-usage customers.

## Project Structure

* Customer_Churn_Analysis.ipynb
* customer_churn_dataset-testing-master.csv
* requirements.txt
* README.md

## Conclusion

This project demonstrates end-to-end data analytics and machine learning workflows, including exploratory data analysis, visualization, business insight generation, and predictive modeling.
