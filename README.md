#Credit Card Fraud Detection Using Machine Learning

#Abstract: 
With the increasing use of online banking, credit cards, and debit cards, the risk of fraudulent activities has risen significantly. Many incidents have occurred where users, due to a lack of awareness, share sensitive information such as personal details, card numbers, and one-time passwords with unknown callers, leading to fraudulent transactions. Detecting and preventing these frauds is challenging, especially when perpetrators use fake identities or internet-based calls. This research aims to use supervised learning methods and algorithms to identify and prevent fraudulent transactions, achieving highly accurate results. Fraud not only impacts customers' trust but also adversely affects businesses, leading to revenue loss. This study utilizes the Isolation Forest algorithm to classify and detect fraudulent activities, using datasets from professional survey organizations.

#Content: 
The dataset consists of credit card transactions made by European cardholders in September 2013. Over two days, 284,807 transactions were recorded, with 492 identified as fraudulent, highlighting a severe class imbalance, as fraudulent transactions represent only 0.172% of the total.

The dataset includes only numerical input variables, derived through Principal Component Analysis (PCA). Due to confidentiality agreements, the original features and further background information are not disclosed. Features are labeled as V1, V2, … V28, representing the principal components from PCA. The features 'Time' and 'Amount' are not transformed by PCA. 'Time' indicates the seconds elapsed between each transaction and the first transaction, while 'Amount' denotes the transaction value, suitable for cost-sensitive learning. The target variable, 'Class,' identifies transactions as either fraudulent (1) or non-fraudulent (0).

#Problem Statement: 
The objective of this project is to predict fraudulent credit card transactions using machine learning models. This will involve analyzing customer transaction data, sourced from a collaboration between Worldline and the Machine Learning Group.

The dataset, sourced from Kaggle, comprises 284,807 transactions, of which 492 are fraudulent. Due to the significant imbalance in the dataset, specific techniques must be employed to address this before building predictive models.
