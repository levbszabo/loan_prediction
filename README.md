# Predicting Loan Repayment

In this notebook we analyze loans and attempt to predict if a loan will be repaid or not. The data is analyzed and a
binary classification model is tuned using XGboost giving approximately 92.3% accuracy on our test dataset.

## Summary

After investigating the borrower/loan dataset we constructed a deeper intuition behind the features and
came up with ways to fill missing values and encode categorical features. 

After this we performed hyperparameter tuning on a variety of hyperparameters used in XGBoost 

We constructed a model and then iterated on it, but alteration regarding feature engineering and further hyperparameter tuning
will only take us so far. It seems that the hard financial features are the strongest indicators of a loan being repaid, namely savings amounts and other direct proxies of financial ability and responsibility. 

Further improvements to this model could be made however large improvements could be made with additional feature sets regarding both the loan (loan amount, type of financing) as well as the user (martial status, education, etc).
