# Credit Card Fraud Detection System

## Overview
This project develops a Credit Card Fraud Detection System using machine learning techniques. It detects fraudulent transactions based on the popular Credit Card Fraud Dataset by leveraging data preprocessing, model training, evaluation, and an interactive testing interface.

---

## Features
- Handles highly imbalanced data using **SMOTE** (Synthetic Minority Oversampling Technique).
- Trains a **Random Forest Classifier** for fraud detection.
- Evaluates model performance with key metrics: **Accuracy, Precision, Recall, and F1-score**.
- Provides a **command-line interface** for real-time testing of transaction data.

---

## Dataset
The model is trained and tested on the Credit Card Fraud Dataset, which contains anonymized features representing credit card transactions with labels indicating fraudulent (1) or legitimate (0) transactions.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>

Install the required Python Packages
pip install -r requirements.txt

The main dependencies are:

scikit-learn

imbalanced-learn

pandas

numpy

Usage
Load the dataset and preprocess it (handling imbalance with SMOTE).

Train the Random Forest model.

Evaluate the model on the test set.

Use the command-line interface to input transaction features and get predictions.

Example command to run the script:
python fraud_detection.py

The program will prompt you to enter 30 transaction features separated by commas and then predict whether the transaction is fraudulent or legitimate.

Sample Output:
Testing a sample transaction from test set:
✅ Legitimate Transaction.

Enter a transaction's features separated by commas (30 features expected):
-1.3598071336738, -0.0727811733098497, 2.53634673796914, ..., 0.0223325408706627
✅ Legitimate Transaction.

Evalvation Metrics
| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 99.95% |
| Precision | 88%    |
| Recall    | 80%    |
| F1-Score  | 84%    |

