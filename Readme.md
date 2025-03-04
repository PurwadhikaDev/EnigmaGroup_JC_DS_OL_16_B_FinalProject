# Telco Customer Churn Analysis

This repository contains an analysis of customer churn for a telecommunications company. 

The goal of this project is to build the most effective Machine Learning model to predict whether customers will churn or remain subscribed. Additionally, the project aims to provide insights into customer behavior to help reduce the attrition rate.

The dataset used comes from the IBM Watson Repository - Sample Datasets for Customer Retention Programs, where each row represents a customer, and each column represents a specific customer attribute. These attributes include:

**Target Variable**: The `Churn` column indicates whether a customer has remained subscribed (0) or churned within the last month (1).
**Service Types**: These attributes describe the types of services customers have signed up for, including phone service, multiple lines, internet service, online security, online backup, device protection, tech support, and streaming for TV and movies.
**Customer Account Information**: This includes details about the customer’s subscription, such as contract type, payment method, paperless billing preference, monthly charges, and total charges.
**Demographic Information**: This contains additional customer details, including gender, senior citizenship status, and whether they have a partner or dependents.

## Dataset Attributes

| **Attribute**        | **Description** |
|----------------------|----------------|
| `customerID`        | Customer ID |
| `gender`            | Whether the customer is male or female |
| `SeniorCitizen`     | Whether the customer is a senior citizen or not (1, 0) |
| `Partner`          | Whether the customer has a partner or not (Yes, No) |
| `Dependents`       | Whether the customer has dependents or not (Yes, No) |
| `tenure`           | Number of months the customer has been with the company |
| `PhoneService`     | Whether the customer has a phone service or not (Yes, No) |
| `MultipleLines`    | Whether the customer has multiple phone lines or not (Yes, No, No phone service) |
| `InternetService`  | Customer's internet service provider (DSL, Fiber optic, No) |
| `OnlineSecurity`   | Whether the customer has online security or not (Yes, No, No internet service) |
| `OnlineBackup`     | Whether the customer has online backup or not (Yes, No, No internet service) |
| `DeviceProtection` | Whether the customer has device protection or not (Yes, No, No internet service) |
| `TechSupport`      | Whether the customer has tech support or not (Yes, No, No internet service) |
| `StreamingTV`      | Whether the customer has streaming TV or not (Yes, No, No internet service) |
| `StreamingMovies`  | Whether the customer has streaming movies or not (Yes, No, No internet service) |
| `Contract`         | Customer's contract term (Month-to-month, One year, Two year) |
| `PaperlessBilling` | Whether the customer has paperless billing or not (Yes, No) |
| `PaymentMethod`    | Customer's payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)) |
| `MonthlyCharges`   | Amount charged to the customer each month |
| `TotalCharges`     | Total amount charged to the customer |
| `Churn`           | Whether the customer has churned or not (Yes, No) |


## Notebook Overview

- Data cleaning and preprocessing steps to handle missing values and outliers.
- Exploratory Data Analysis (EDA) to identify key factors affecting churn.
- Implementation of Machine Learning models to predict churn.
- Hyperparameter tuning to optimize model performance.
- Feature importance analysis to understand the most significant predictors of churn.


## Author

This project was developed by Dadang, Herry, and Nabila from Enigma Group Final Project.

## Tableau Link
https://public.tableau.com/views/DashboardEnigma/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
