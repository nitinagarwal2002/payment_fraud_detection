# Online Payment Fraud Detection

## Introduction
Online payment is the most popular transaction method in the world today. However, with an increase in online payments also comes a rise in payment fraud. The objective of this notebook is **to train machine learning models for identifying fraudulent and non-fraudulent payments**. The dataset is collected from Kaggle, which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. 

The dataset consists of 10 variables:
* step: represents a unit of time where 1 step equals 1 hour
* type: type of online transaction
* amount: the amount of the transaction
* nameOrig: customer starting the transaction
* oldbalanceOrg: balance before the transaction
* newbalanceOrig: balance after the transaction
* nameDest: recipient of the transaction
* oldbalanceDest: initial balance of recipient before the transaction
* newbalanceDest: the new balance of recipient after the transaction
* isFraud: fraud transaction


### Python Libraries
pandas, numpy, seaborn, matplotlib, tabulate, sklearn

Random Forest and Naive Bayes were used to identify online payment fraud due to the large dataset.

![image](https://user-images.githubusercontent.com/118715799/210950017-e4d317e0-6bf4-4ecd-8313-9b8121e04e9f.png)

## Usage

1. **Data Preparation**: Before running the system, prepare the transaction data. Ensure that the dataset is properly formatted and includes relevant features such as transaction amount, time, merchant information, customer information, geographical location, etc.

2. **Feature Engineering**: Perform feature engineering to extract additional features or transform existing ones that might improve the performance of the machine learning models. This may include feature scaling, one-hot encoding, or creating new features based on domain knowledge.

3. **Training**: Train the machine learning models using the provided training script. You may need to tune the hyperparameters and select the appropriate algorithms based on the characteristics of your dataset.

4. **Evaluation**: Evaluate the performance of the trained models using validation data or cross-validation techniques. Measure metrics such as accuracy, precision, recall, and F1-score to assess the effectiveness of the models.

5. **Deployment**: Deploy the trained models into a production environment where they can analyze real-time transaction data and flag potentially fraudulent transactions in real-time.

6. **Monitoring**: Continuously monitor the performance of the deployed models and update them as necessary to adapt to evolving fraud patterns and techniques.

## Features

In addition to the basic features mentioned above, this project also supports the following advanced features:

- **Customer Behavior Analysis**: Analyze patterns in customer behavior, such as transaction frequency, transaction amounts, and time of transactions, to detect anomalies indicative of fraudulent activities.
- **Merchant Reputation Analysis**: Incorporate data about merchants' reputation, including reviews, ratings, and transaction history, to identify potentially suspicious merchants involved in fraudulent transactions.
- **Geographical Location Analysis**: Utilize geographical information such as IP addresses or GPS coordinates to detect discrepancies between the location of the transaction and the customer's usual location.
- **Network Analysis**: Perform network analysis to identify connections between different entities involved in transactions (e.g., customers, merchants) and detect organized fraudulent activities such as collusion or money laundering.

## Made By

- Nitin
- Saksham
- Rohit
