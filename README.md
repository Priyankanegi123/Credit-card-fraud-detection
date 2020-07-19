# Credit-card-fraud-detection
**ABSTRACT:**
The credit card fraud detection problem includes modelling the past credit card transactions with the knowledge of the ones that turned out to be fraud. This ML model is used to identify whether a new transaction is fraudulent or not.  The following project has been done using python language.
**DATASET:**
The dataset has been taken from: https://www.kaggle.com/mlg-ulb/creditcardfraud/

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. Each transaction has 30 features, all of which are numerical. The features v1, v2,  …. , v28 are the result of PCA transformation. To protect confidentiality, background information on these features is not available. The response variable should be 1 in case of fraud, and 0 otherwise.

**DATA ANALYSIS:**

•	The data set is highly skewed. This skewed set is justified by the low number of fraudulent transactions.

•	The dataset consists of numerical values from the 28 PCA transformed features. 

•	The ‘Time’ and ‘Amount’ features are not transformed data.

•	There is no missing value in the dataset.

**ALGORITHMS USED:**
The following problem is a classification problem so we have used the following classification algorithms to find which works best for the problem by finding accuracy.

•	Logistic regression :  0.998

•	Naïve bayes classifier: 0.98

•	Random forest regression: 0.99

•	KNN algorithm: 0.99




