# Churn Prediction Machine Learning Model

This project aims to predict customer churn using machine learning techniques. The model predicts whether a customer will exit (churn) or remain based on various customer attributes such as their credit score, demographics, and banking behavior.

## Project Overview

- **Objective**: Build a machine learning model to predict customer churn, i.e., whether a customer will exit or stay.
- **Dataset**: The dataset contains customer information, including demographics, credit score, banking behavior, and the target variable indicating whether a customer exited.
- **Technologies Used**:
  - Python
  - Scikit-learn
  - Pandas
  - Matplotlib / Seaborn (for data visualization)
  - Jupyter Notebook (for analysis and model development)

## Dataset

The dataset contains the following features for each customer:

- **CustomerId**: Unique identifier for each customer.
- **Surname**: Customer's surname (not used for modeling).
- **CreditScore**: The customer's credit score.
- **Geography**: The customer's location (country).
- **Gender**: The customer's gender (Male/Female).
- **Age**: The customer's age.
- **Tenure**: The number of years the customer has been with the bank.
- **Balance**: The customer's account balance.
- **NumOfProducts**: The number of products the customer has with the bank.
- **HasCrCard**: Whether the customer has a credit card (1 for yes, 0 for no).
- **IsActiveMember**: Whether the customer is an active member of the bank (1 for yes, 0 for no).
- **EstimatedSalary**: The customer's estimated salary.
- **Exited**: The target variable indicating whether the customer has exited (1) or stayed (0).
