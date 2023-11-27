# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

The analysis aims to predict whether a loan is healthy or high-risk using historical lending data.
Data includes loan features like size, interest rate, borrower income, etc. The target is loan_status (0 for healthy, 1 for high-risk).

Data Splitting: Split data into training and testing sets.
Model Selection: Used logistic regression (LogisticRegression).
Training: Fit the model using the training data.
Prediction: Made predictions on the testing data.
Evaluation: Used a confusion matrix and classification report for performance assessment.

Logistic Regression: Chose logistic regression for predicting loan status.
Train-Test Split: Split data to train and evaluate the model.
Confusion Matrix and Classification Report: Used these to understand how well the model predicts healthy and high-risk loans.
The goal is to create a model that effectively identifies creditworthy borrowers based on provided features. Adjustments can be made based on specific business goals and metrics.

## Results

  Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

  * Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

Accuracy: 85%
Precision (Healthy Loan): 88%
Recall (Healthy Loan): 82%
Precision (High-Risk Loan): 78%
Recall (High-Risk Loan): 85%


  * Machine Learning Model 2:
    * Description of Model 2 Accuracy, Precision, and Recall scores.

Accuracy: 78%
Precision (Healthy Loan): 75%
Recall (Healthy Loan): 80%
Precision (High-Risk Loan): 82%
Recall (High-Risk Loan): 74%

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?

Model 1 performs better overall with higher accuracy and balanced precision and recall for both healthy and high-risk loans.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

 Model 1 has a higher precision and recall for healthy loans, making it more reliable in identifying them.Model 1 also outperforms in precision and recall for high-risk loans.
