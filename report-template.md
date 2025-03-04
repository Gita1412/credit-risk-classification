# Module 12 Report Template
This report documents the credit risk analysis and serves as a reference for financial decision-making.
## Overview of the Analysis

The objective of this analysis is to evaluate the performance of a logistic regression model in predicting credit risk. The dataset, lending_data.csv, consists of financial information used to classify loans as either healthy (0) or high risk (1).

The primary goal of this machine learning model is to determine whether a loan is likely to default, providing financial institutions with insights to minimize risks. The analysis follows these steps:

Data Preprocessing:

Read the dataset and review its structure.

Separate the target variable (loan_status) and the feature set.

Split the data into training and testing sets.

Standardize numerical features using StandardScaler.

Logistic Regression Model Implementation:

Train a logistic regression model using the training dataset.

Use the model to make predictions on the test dataset.

Evaluate model performance using classification metrics.



## Results

Logistic Regression Model Performance:

Accuracy Score: 99%

Confusion Matrix:

The model correctly classified nearly all healthy loans (0).

False negatives (high-risk loans misclassified as healthy) are minimal.

## Summary & Recommendation

The logistic regression model performed exceptionally well, achieving an accuracy of 99%.

High precision and recall for both loan categories indicate that the model is highly reliable in predicting credit risk.

The model correctly identifies high-risk loans with 98% recall, which is crucial in preventing financial defaults.

Recommendation: This model is well-suited for predicting credit risk and can be used by financial institutions to assess loan eligibility. However, additional models such as Random Forest or XGBoost could be explored for further improvements.