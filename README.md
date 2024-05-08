The analysis of credit card transaction data involved the identification of fraudulent transactions and the development of a predictive model to prevent future fraudulent activities. 
The dataset, containing 786,363 transactions, encompassed various fields such as transaction ID, account holder information, merchant details, transaction amount, and fraud indicators.

Duplicated transactions, including reversals and multi-swipe transactions, were scrutinized, with 19,731 reversals identified, totaling $2,322,179. 
However, 4,268 reversals lacked associated purchases, totaling $499,613.02, prompting their removal.

For machine learning modeling, a decision tree algorithm was initially trained, achieving an accuracy of 97.84%. 
Hyperparameter tuning, cross-validation, and alternative algorithms such as logistic regression and kernel methods were explored, with the final logistic regression model selected based on performance metrics. 
Despite an overall accuracy of 98.43%, challenges persisted in accurately classifying the minority class of fraudulent transactions, warranting further investigation and improvement.





