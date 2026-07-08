# customer_churn_prediction

Author: Jake Visintin

Date: May 2026

## Project Overview

This project uses Python, Seaborn, Pandas, and Scikit-Learn to identify the business variables most strongly correlated with customer churn and develop predictive models to predict churn. It also compares the performance of the K-Nearest Neighbors (KNN) and Logistic Regression (LR) models to determine which provides more accurate predictions based on the selected variables. 

## Recommendations
I recommend that the KNN model be selected as a predictor for churn. Seeing that the accuracy score for the KNN model (80.77%) is higher than the LR model (78.83%), leads me to believe that the KNN model is a better choice. I also recommend that the Monthly Charges (MonthlyCharges), Total Charges (TotalCharges), and Contract variables be considered when wanting to predict churn within this company given that they showed the highest accuracy (80.77%).

## Data Source
The dataset used in this project is the **Telco Customer Churn** dataset sourced directly from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data). 

It contains historical data for 7,043 telecommunications customers and includes 21 columns mapping:

* **Demographics:** Gender, senior citizen status, and family dependencies.
* **Account Info:** Tenure length, contract types, billing methods, and charges.
* **Subscribed Services:** Web connectivity, telephone lines, and online security options.
* **Target Variable:** `Churn` (indicating clients who left within the last month).
