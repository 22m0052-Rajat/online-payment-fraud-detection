# online-payment-fraud-detection


This repository contains a Python script that demonstrates the process of building a logistic regression model for online payment fraud detection. The script performs data preprocessing, model training, prediction, and evaluation. It uses the scikit-learn library for machine learning tasks and pandas for data manipulation.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- pandas
- scikit-learn
- numpy
- matplotlib

You can install the required libraries using the following command:

```bash
pip install pandas scikit-learn numpy matplotlib


Dataset
The code uses a dataset containing transaction records for online payment systems. The dataset includes various features related to
transactions and flags whether a transaction is fraudulent. The relevant features are:

amount: Transaction amount
oldbalanceOrg: Initial balance of the sender account
newbalanceOrig: New balance of the sender account after the transaction
oldbalanceDest: Initial balance of the recipient account
newbalanceDest: New balance of the recipient account after the transaction
isFraud: Whether the transaction is fraudulent (target variable)
isFlaggedFraud: Whether the transaction is flagged as fraudulent

Usage
Clone this repository to your local machine:
git clone https://github.com/22m0052-Rajat/online-payment-fraud-detection.git

Navigate to the repository directory:
cd online-payment-fraud-detection

Run the Python script:
python online-payment-fraud-detection.ipynb

The script will load the dataset, preprocess the data, train a logistic regression model, make predictions, and
evaluate the model's performance.

Results
After running the script, you will see the following outputs:

Model accuracy on the test set
Model accuracy on the training set
Confusion matrix visualizations
Classification report with precision, recall, and F1-score
