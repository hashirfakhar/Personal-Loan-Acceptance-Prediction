# Task 5 – Personal Loan Acceptance Prediction

## Objective
The goal of this task is to predict whether a customer will accept a personal loan offer using the Bank Marketing Dataset. The task involves exploring and preprocessing customer data, training classification models, and analyzing which features influence customer behavior.

## Approach
- Loaded the dataset and handled semicolon (`;`) delimiters properly
- Dropped the `duration` column to prevent data leakage
- Encoded categorical variables using:
  - One-Hot Encoding for multi-class categorical features
  - Binary encoding for the target column `y`
- Split the data into training and testing sets
- Trained two classification models:
  - Logistic Regression
  - Decision Tree Classifier
- Evaluated both models using:
  - Accuracy
  - Confusion Matrix
  - Classification Report

## Results and Insights
- Logistic Regression achieved an accuracy of **89.7%**
- Decision Tree achieved an accuracy of **83.9%**
- Key features that influenced loan acceptance included:
  - Job type
  - Contact method
  - Previous campaign outcome
  - Economic indicators (e.g., euribor3m)
- Removing the `duration` column avoided overfitting and improved model generalization

---
This task provided valuable experience in handling real-world marketing data, encoding categorical features, and analyzing customer behavior in response to financial offers.
