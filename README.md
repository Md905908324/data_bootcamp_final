# Telco Customer Churn Prediction

## Introduction

This project aims to predict customer churn for a telecommunications company using the Telco Customer Churn dataset. Churn, in this context, refers to customers who discontinue their services with the company. By accurately predicting churn, the company can take proactive measures to retain valuable customers.

The dataset contains information about customer demographics, services subscribed, account information, and churn status. We will explore various machine learning models, including Logistic Regression, K-Nearest Neighbors (KNN), and a Neural Network, to build a predictive model for churn.

## Summary of Findings

Our analysis revealed that the Neural Network model achieved the highest accuracy on the test set, followed by Logistic Regression and KNN. Key factors influencing churn included contract type, monthly charges, and tenure. Further analysis and model refinement could potentially improve prediction accuracy.

## Data Description

The Telco Customer Churn dataset is a publicly available dataset on Kaggle. It contains information about 7043 customers and includes the following features:

- **Demographics:** Gender, Senior Citizen, Partner, Dependents
- **Services:** Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies
- **Account Information:** Tenure, Contract, Paperless Billing, Payment Method, Monthly Charges, Total Charges
- **Churn:** Whether the customer churned (Yes/No)

The dataset was preprocessed to handle missing values, convert categorical features to numerical representations, and scale numerical features.
