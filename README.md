# Customer Churn Prediction Using ANN

## Project Overview

This project uses Artificial Neural Networks (ANN) to predict customer churn from a telecom dataset. The goal is to analyze customer data and predict churn behavior, enabling the company to target retention strategies more effectively.

## Dataset

The dataset includes various customer attributes such as demographic information, account details, and service usage, labeled with whether the customer has churned or not.

### Key Features

- `Gender`: Whether the customer is male or female.
- `SeniorCitizen`: Indicates if the customer is a senior citizen.
- `Partner`: Whether the customer has a partner.
- `Dependents`: Whether the customer has dependents.
- `Tenure`: Number of months the customer has been with the company.
- `PhoneService`: Whether the customer has phone service.
- `MultipleLines`: Whether the customer has multiple lines.
- `InternetService`: Type of internet service (DSL, Fiber optic, None).
- `OnlineSecurity`: Whether the customer has online security.
- `OnlineBackup`: Whether the customer has online backup.
- `DeviceProtection`: Whether the customer has device protection.
- `TechSupport`: Whether the customer has tech support.
- `StreamingTV`: Whether the customer has streaming TV.
- `StreamingMovies`: Whether the customer has streaming movies.
- `Contract`: The contract term of the customer (Month-to-month, One year, Two year).
- `PaperlessBilling`: Whether the customer has paperless billing.
- `PaymentMethod`: The customer’s payment method.
- `MonthlyCharges`: The amount charged to the customer monthly.
- `TotalCharges`: The total amount charged to the customer.
- `Churn`: Whether the customer churned (Yes or No).

## Model

The project uses an ANN model built with TensorFlow and Keras. It includes several dense layers and processes features after encoding categorical variables and scaling numerical variables.

## Usage

Run the analysis notebook/script to train the model and make predictions. The model's performance is evaluated based on accuracy, precision, and recall metrics.
