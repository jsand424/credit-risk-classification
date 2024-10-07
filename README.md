## Loan Risk Classification Model

# Overview of the Analysis

This analysis aims to predict the likelihood of a loan being high-risk or healthy based on historical lending data. By leveraging a logistic regression model, we aim to provide a reliable, efficient tool for classifying loans, helping the company make more informed lending decisions. The machine learning model is trained on loan data, where each loan is labeled as either "healthy" or "high-risk," and uses various features to predict the loan status.

# Results

Below is a summary of the model's performance based on the testing dataset:

Accuracy Score: 99%
Precision Score (Class 1 - High-Risk Loans): 86%
Recall Score (Class 1 - High-Risk Loans): 91%
F1 Score (Class 1 - High-Risk Loans): 88%
For the "healthy loans" (Class 0):

Precision: 100%
Recall: 100%
F1 Score: 100%

# Summary

The logistic regression model demonstrates a high level of accuracy (99%) when predicting loan statuses. It performs exceptionally well in identifying healthy loans (Class 0), with perfect precision and recall scores. For high-risk loans (Class 1), the model also shows strong performance, with a precision score of 86% and a recall score of 91%. The relatively high F1 score of 88% for high-risk loans suggests a good balance between precision and recall.

# Model Recommendation

Recommendation: Based on the results, I recommend using the logistic regression model for predicting loan risk. The model’s high accuracy and strong performance in identifying both healthy and high-risk loans make it a reliable choice for the company's loan classification needs. While there is a slight imbalance in the model's precision for high-risk loans, the recall score ensures that the majority of high-risk loans are identified correctly, which is crucial for minimizing financial risk.

However, to further improve the model's ability to predict high-risk loans, the company could explore advanced models or fine-tune hyperparameters to improve precision for this category.
