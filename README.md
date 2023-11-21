# credit-risk-classification
* The purpose of this analysis was to create a model that is able to predict whether a loan is a healthy loan or a high risk loan. With the data, specifically, finanicial information, it's able to assess and establish whether certain components equal to a healthy or high risk loan. 
* There was financial information, such as loan size,interest rate,debt to income,num_of_accounts,total_debt,loan_status, etc. All these components were used to predict loan risk level.
* Value counts calculated the total number of healthy and high-risk loans.
* Well, the csv was made into a dataframe and read. A separation of the x and y values was done. The data was split and then the Logistic Regression method was used to predict the level of risk of loans. Another method that was used was RandomOverSampler. This method takes into account the imbalanced datasets. Classification reports were made to evaluate the predictions of the models. Some components that were outputted by the report was the precision, recall, and F1-score.


## Results

* Machine Learning Model 1: Logistic Regression 
  * The logistic regression model for a healthy loan has a precision of 1, so it predicts a healthy loan to be correct 100% of the time. The recall is also high and it has a percentage of 99% of being actual healthy loans. For a high risk, the model predicts a high risk loan and is correct 85% of the time. The recall is 91% and 91% of the loans are high risk. The balanced accuracy score was 0.9520479254722232.

* Machine Learning Model 2: RandomOverSampler
  * he logistic regression model for a healthy loan also has a precision of 1, so it predicts a healthy loan to be correct 100% of the time. The recall is 99% and 99% are healthy loans. For a high risk, the model predicts a high risk loan to be 84% and is correct 84% of the time. The recall is high, 99% of the loans are actual high risk. The balanced accuracy score was 0.9936781215845847.

## Summary

* I prefer the RandomOverSampler model because it has a high percentage of precision and recall on identifying a healthy loan, but as well as a high percentage on idenetifying a high risk loan. 
* It is most important to accurately predict the high risk loans because the company will not lose money due to not granting the loans to people who may not be the ideal candidates.

