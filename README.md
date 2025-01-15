**Credit Risk Analysis Report**

**Overview of the Analysis**

The purpose of this analysis is to evaluate the performance of logistic regression machine learning model in predicting the credit risk associated with loans. The analysis was conducted on financial data of loan sizes, interest rates, borrowers income, debt-to-income ratios, number of accounts, derogatory marks, and total debt. The objective was to predict the loan status, being either a healthy loan of ('0') or high-risk loan of ('1').

The stages of this machine learning process included the following:

Split the datasets for training and testing
Create and fit a logistic regression model with data
Evaluate the model's performance by observing accuracy, precision, recall, and f1 scores

**Machine Learning Model:**
Description of Model Accuracy, Precision, and Recall scores.

Accuracy: The accuracy of the model is 0.99, meaning that it correctly classifies 99% of the instances.
Precision: 
For healthy loans ('0'): The model has a precision of 1.00, meaning that it perfectly identifies true positives with no false positives.
For high-risk loans ('1'): The model has a precision of 0.87, meaning that it is moderately effective in identifying high-risk loans with some false positives.

Recall: 
For healthy loans ('0'): The model has a recall of 1.00, meaning that it perfectly identifies all instances of healthy loans with no false negatives. 
For high-risk loans ('1'): The model has a recall of 0.89, meaning that it is moderately effective in identifying high-risk loans with some false negatives.

**Summary**

After observing the modeling results, I determined that the first model trained with original data does a great job in predicting 0 (healthy loan) and 1 (high-risk loan). The model produced higher precision, recall, and f1 scores for high-risk loans, which is most important to aid the lending company in reducing the amount of bad loans and financial losses incurred.
