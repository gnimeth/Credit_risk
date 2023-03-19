## Overview of the Analysis

* Various techniques were utilized to train and evaluate a loan risk model based on a historical lending dataset from a peer-to-peer lending company. The goal of this was to create a model that can identify the creditworthiness of borrowers.
* The data was divided into training and testing sets using train_test_split from the sklearn.model_selection.  LogisticRegression was used from sklearn.linear_model to create a model with the original dataset.  The model's performance was evaluated by the accuracy score of the model, generating a confusion matrix, and printing out the classification report.

## Results

This data represents the performance of a classification model in predicting the labels of a dataset, where 0 indicates a negative class (healthy) and 1 indicates a positive class (high-risk).

* Machine Learning Model 1:
  
  
  
  - The model achieved high levels of precision and recall for both labels, with a precision of 1.00 and recall of 0.99 for label 0, and a precision of 0.85 and recall of 0.89 for label 1.
  
  - In general, the model seems to be performing well in predicting both healthy and high-risk cases, but it has slightly lower accuracy for predicting high-risk cases compared to healthy cases.

* Machine Learning Model 2:

  - The model performed well in terms of precision and recall. It had a precision score of 1.00 for label 0. For label 1, the precision score was 0.87, indicating that 87% of predicted high-risk loans were actually high-risk. 

  - Overall, the model seems to be performing well for both labels, although it is slightly less accurate in predicting high-risk loans.

## Summary

* Model 1 outperformed Model 2 in terms of precision and recall scores. For label 1 (high-risk loans), Model 1 achieved a precision score of 0.85, indicating a lower false positive rate compared to Model 2's precision score of 0.87. Additionally, Model 1 attained a perfect precision score of 1.00 for label 0 (healthy loans), while Model 2's precision score for label 1 indicates that it may misclassify some healthy loans as high-risk.
* Both models had a recall score of 1.00 for label 0, but Model 1 had a slightly higher recall score of 0.89 for label 1 compared to Model 2's score of 0.87. This means that Model 1 is better at correctly identifying high-risk loans.
