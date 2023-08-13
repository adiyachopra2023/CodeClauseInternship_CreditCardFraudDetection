# CodeClauseInternship_CreditCardFraudDetection

## Problem Statement:
To identify whether a new credit card transaction is fraudulent or not based on a model trained by past data.

## Workflow:
1. Data Collection/Finding Dataset
2. Data Pre-processing
3. Data Analysis
4. Splitting into train & test data
5. Logistic Regression Model Building (Binary Classification)
6. Evaluating the model

## Dataset:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Dataset Description:
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Attributes:
	1. Time - Number of seconds elapsed between 	this transaction and the first transaction in 	the dataset
	2. V1-V28 - numerical values giving details of 	transactions
	3. Amount - Amount of transaction in USD
	4. Class - 0:Legitimate Transaction, 		1:Fraudulent Transaction

## References:
https://developers.google.com/machine-learning/data-prep/construct/sampling-splitting/imbalanced-data#:~:text=A%20classification%20data%20set%20with,smaller%20proportion%20are%20minority%20classes.

https://www.mdpi.com/2078-2489/14/1/54#:~:text=Oversampling%20works%20by%20replicating%20samples,the%20majority%20class%20%5B4%5D.
