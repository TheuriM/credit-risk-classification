# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

-----------------------------------------------------------------------------------------------------------------------------------------------
Answer
The purpose of this analysis was to create a model that predicts creditworthiness of loan applicants. The data used is historical and measures various lending activities. It data identifies each loan as either healthy(0) or high-risk(1). The lender's objective was to create a machine learning (ML) model that places the loans in either of the two categories for informed decision making.
The following were the stages of the ML process:
    . Data Preparation: data was loaded and then split into X features and y labels. X were the variables that predict lending risk, y variable the target loan   status.
    . Data Split:Data was split into two sets, training and testing to  evaluate the model's performance.
    . Modelling: Logistic regression  was used to predict the target variable.
    . Evaluation: A confusion  matrix was used to evaluate the model's performance by assessing accuracy,  precision, and recall.
Results
    Logistic  Regression Model:
    . Accuracy: 0.99
    . Precision: Healthy loans(0) 0.99, High-risk loans (1) 0.86
    . Recall:  Healthy loans(0) 0.99, High-risk loans (1) 0.94

Summary
    Overall performance  of the model was good with an accuracy of 0.99. 
    . It was able to predict healthy loans with a precision of 0.99 and recall of 0.99.
    . Best Performance: The model ably predicts both healthy and high-risk loans  with a precision of 0.99 and recall of 0.99 respectively.
      The model's ability to predict high-risk loans is more important than predicting healthy loans. This is because
      high-risk loans are more likely to default and cause financial loss to the lender. 
    . Importance of Recall: It is critical that the model  has a high recall for high-risk loans. This is because the model needs to be able to identify
      all high-risk loans to prevent financial loss.
Recommendation
    Given the results exhibited, the logistic regression model is recommended for use in predicting creditworthiness of loan applicants. It has a high 
    accuracy of 0.99 and is able to predict both healthy and high-risk loans.  Its ability to predict high-risk loans is more important than predicting 
    healthy loans. The model's ability to identify all high-risk loans is critical in preventing financial loss. 
