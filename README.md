# credit-risk-classification
# Challenge 20 by Olga Petrova

# Overview of the Analysis
In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

Explain the purpose of the analysis.
Explain what financial information the data was on, and what you needed to predict.
Provide basic information about the variables you were trying to predict (e.g., value_counts).
Describe the stages of the machine learning process you went through as part of this analysis.
Briefly touch on any methods you used (e.g., LogisticRegression, or any other algorithms).
Results
Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.


**Question:** How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

**Answer:** Healthy loans: Precision for healthy loans was 1.00 meaning that when model predicts the loan is healthy, it's 100% true. Recall 1.00 - The model correctly identifies all healthy loans. f1-score 1.00 - perfect balance between precision and recall for healthy loans. Support 18759 - Most of the dataset belongs to this class.
High-risk loans: Precision 0.87 - when system predicts high risk loans, it is correct in 87% cases. Recall 0.95 - Model misses only 5% of the high-risk loans. F1-score 0.91 - Strong balance between precision and recall for high risk loans. Support 625 - Fewer high risk loans then healthy loans. 
Accuracy 0.99 - Model is correct in 99% of the cases.
Macro average - precision 0.94, recall 0.97.
Weighted average - Precision 0.99, recall 0.97. Support 19384 - class 0 (healthy loans) dominated.




Machine Learning Model 1:
Description of Model 1 Accuracy, Precision, and Recall scores.
Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Which one seems to perform best? How do you know it performs best?
Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the 1's, or predict the 0's? )
If you do not recommend any of the models, please justify your reasoning.
