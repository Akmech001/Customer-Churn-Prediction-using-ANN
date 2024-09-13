
Customer Churn Prediction Using ANN
This project demonstrates the application of Artificial Neural Networks (ANN) to predict customer churn based on a dataset from a telecom company. The analysis focuses on identifying whether customers will churn using both Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) and compares their performance.

Features
Data preprocessing and exploration.
Churn prediction using ANN.
Model evaluation and comparison.
Data visualization for insights.
Prerequisites
Before you begin, ensure you have met the following requirements:

Python 3.6+
pandas
NumPy
Matplotlib
TensorFlow
Scikit-learn
Installation
Clone the repo:

bash
Copy code
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
Run the script to train the model and evaluate its performance:

bash
Copy code
python churn_prediction.py
Data
The dataset used in this project (customer_churn.csv) includes the following features:

customerID: Customer ID
gender: Customer gender (male/female)
SeniorCitizen: Whether the customer is a senior citizen (1) or not (0)
tenure: Number of months the customer has stayed with the company
Service: Type of internet service
MonthlyCharges: The amount charged to the customer monthly
TotalCharges: The total amount charged to the customer
Churn: Whether the customer churned (1) or not (0)
