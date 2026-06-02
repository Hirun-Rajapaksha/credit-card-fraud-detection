# Credit Card Fraud Detection

## Project Overview

This project builds a machine learning solution for detecting fraudulent credit card transactions.

The dataset is highly imbalanced, meaning fraud transactions are very rare compared to legitimate transactions. Because of this, accuracy alone is not a suitable evaluation metric. The project focuses on Precision, Recall, F1-score, ROC-AUC, and confusion matrix.

## Dataset

The dataset used is the Credit Card Fraud Detection dataset.

Original dataset size:

- Rows: 284,807
- Columns: 31
- Legitimate transactions: 284,315
- Fraud transactions: 492
- Fraud rate: approximately 0.1727%

After data cleaning:

- Rows: 283,726
- Columns: 31
- Legitimate transactions: 283,253
- Fraud transactions: 473
- Fraud rate: approximately 0.1667%

Note: The dataset CSV files are not included in this repository because of file size limitations. Please download the dataset separately and place it inside a folder named `data`.

Expected dataset path:

```text
data/creditcard.csv
