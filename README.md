# Telco Customer Churn Prediction

## 📊 Project Overview

Customer churn is a critical business metric most companies should keep an eye on.

High attrition in churn is **more than just an immediate loss of revenue and market share**, as the culmulation of bad sentiment can snowball, culmulating dissatisfied ex-customers plus their family and friends that will be harder to winover.

Before bad reputation chokes the company, a high churn rate should be discovered immediately and treated ASAP by fixing the product, price, or even measle things like bad payment experience.

Calculation wise, the churn metric is simply calculated by

$$\text{Churn Rate} = \frac{\text{Customers Lost}}{\text{Customers at Start}} \times 100$$

There are some other ways to calculate churn like the adjusted churn which divides it by the average number of customers in the start and end of the period.

$$\text{Adjusted Churn Rate} = \frac{\text{Customers Lost}}{\left( \frac{\text{Customers at Start} + \text{Customers at End}}{2} \right)} \times 100$$

Churn can also be expressed in terms of revenue. This helps to grasp the damage more clearly. Although a more detailed dataset will be needed to accurately calculate customer churn in terms of revenue.

## 🎯 Objectives

- Identify key drivers of customer churn
- Build ML models to predict customer churn
- Compare NN vs XGBoost models

## 📈 Dataset

- 7,043 customers with 21 features
- Features: demographics, services, account information

## 🛠️ Technologies & Libraries

- PyTorch with CUDA support
- XGBoost
- Optuna for hyperparameter tuning
- Scikit-learn preprocessing

## 🔥 Motivations

- As a learning project
- Theory -> Practice
