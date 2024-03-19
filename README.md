# Credit Card Fraud Detection Project Report

## Introduction

The dataset used in this project contains transactions made by credit cards in September 2013 by European cardholders. It presents transactions occurring over two days, totaling 284,807 transactions, with 492 instances of fraud. The dataset is highly unbalanced, with fraudulent transactions accounting for only 0.172% of all transactions.

The dataset consists of numerical input variables resulting from a Principal Component Analysis (PCA) transformation. Features V1 to V28 represent principal components, while the features Time and Amount remain unchanged. The Time feature denotes the seconds elapsed between each transaction and the first transaction in the dataset, while the Amount feature represents the transaction amount.

## Insights

### Data Unbalance

The dataset is highly unbalanced, with only 492 (0.172%) transactions labeled as fraudulent.

### Transactions in Time

Fraudulent transactions exhibit a more even distribution across time compared to valid transactions, including during off-peak hours.

### Feature Analysis

Analysis of feature distributions indicates that some features exhibit distinct profiles for legitimate and fraudulent transactions, while others show partial or no separation.

### Model Development - RandomForestClassifier

A RandomForestClassifier model was trained and validated using the dataset. The model achieved a Receiver Operating Characteristic Area Under the Curve (ROC-AUC) score of 0.85.

## Conclusion

Our credit card fraud detection project leveraged machine learning techniques to develop a model capable of effectively distinguishing between legitimate and fraudulent transactions. The highly unbalanced nature of the dataset posed a challenge, which was addressed through careful analysis and model development.

The RandomForestClassifier model demonstrated strong performance with an ROC-AUC score of 0.85, indicating its ability to accurately classify transactions. Important features contributing to the model's predictions were identified, providing insights into the underlying patterns of fraud.

Continuous monitoring and refinement of the model will be essential to maintain its effectiveness against evolving fraud patterns. Additionally, further exploration of feature engineering and model optimization techniques could lead to even greater performance improvements.

Overall, this project highlights the potential of machine learning in combating credit card fraud and underscores the importance of robust detection systems in safeguarding financial transactions.
