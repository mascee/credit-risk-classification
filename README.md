# credit-risk-classification
# Challenge 20 by Olga Petrova

# Overview of the Analysis

Project Credit risk Classification used various techniques to train and evaluate a model based on loan risk. 

The goal was to correctly predict and identify healthy loans and risky loans - to perform risk analysis for the loan lending data.

Machine learning technique called Logistical Regression Model was used for this purpose.

Data set that was used - historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The data included size of the loan, interest rate, borrower's income, debt to income ratio, number of accounts, derogatory marks(negative records on the borrower's credit report - 0 for no records, 1 for negative record), total debt, status of the loan(0 for healthy loan, 1 for high risk loan)

The Logistic Regression model was used to predict the if the loan is healthy or risky. The Logistic Regression model devides data to training and testing and performs statistical function on it to predict the outcome.

# Outcome:
# Confusion matrix explanation: 
- True Negatives (TN):  18673 - Correctly predicted healthy loans.
- False Positives (FP): 86 - Predicted high-risk, but actually healthy.
- False Negatives (FN): 32 - Predicted healthy, but actually high-risk.
- True Positives (TP):  593 - Correctly predicted high-risk loans.

# Classification report:

# Healthy loans: 
* Precision for healthy loans was 1.00 meaning that when model predicts the loan is healthy, it's 100% true. 
* Recall 1.00 - The model correctly identifies all healthy loans. 
* f1-score 1.00 - Perfect balance between precision and recall for healthy loans. 
* Support 18759 - Most of the dataset belongs to this class.
# High-risk loans: 
* Precision 0.87 - when system predicts high risk loans, it is correct in 87% cases. 
* Recall 0.95 - Model misses only 5% of the high-risk loans. 
* F1-score 0.91 - Strong balance between precision and recall for high risk loans. 
* Support 625 - Fewer high risk loans then healthy loans. 
# Model Metrics:
* Accuracy 0.99 - Model is correct in 99% of the cases.
* Macro average - precision 0.94, recall 0.97.
* Weighted average - Precision 0.99, recall 0.97. Support 19384 - class 0 (healthy loans) dominated.

This model is very good at identifying high risk loans, but from the confusion matrix it predicted 86 loans to be high-risk, that are actually healthy, and predicted 32 healthy loans that were high-risk. The model is conservative with giving out loans. That can lead to loosing potential good customers.

If the goal of the lending company was to catch as many bad loans as it can, preferring safety, this is a good model.


