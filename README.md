# Fraud-Detection-SVC---Decision-Tree-
Dataset Overview:
The dataset contains credit card transactions made by European cardholders during September 2013. It covers transactions that occurred over a two-day period, with a total of 284,807 transactions, among which 492 are fraudulent.
This results in a highly imbalanced dataset, where the positive class (fraud) represents only 0.172% of all transactions.
Due to confidentiality constraints, the dataset does not include the original transaction features. Instead, it consists entirely of numerical features generated through a Principal Component Analysis (PCA) transformation.

Features V1, V2, …, V28 correspond to the principal components obtained from PCA.
The only features that were not transformed are:
Time: The number of seconds elapsed between each transaction and the first transaction in the dataset.
Amount: The transaction amount, which can be leveraged for cost-sensitive learning and business impact analysis.

The target variable Class indicates whether a transaction is fraudulent:
1 → Fraud
0 → Legitimate transaction
