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
-card-fraud-detection/
│
├── 01_eda.ipynb
├── 02_data_cleaning.ipynb
├── 03_model_building.ipynb
├── requirements.txt
├── utils.py
├── README.md
└── .gitignore

Notebook Description
1. Exploratory Data Analysis

File: 01_eda.ipynb

This notebook includes:

Dataset overview
Missing values check
Duplicate rows check
Class imbalance analysis
Transaction amount analysis
Time distribution analysis
V-feature distribution analysis
Correlation analysis
EDA summary
2. Data Cleaning

File: 02_data_cleaning.ipynb

This notebook includes:

Loading the raw dataset
Checking missing values
Removing duplicate rows
Scaling Amount and Time using RobustScaler
Saving the cleaned dataset as data/creditcard_cleaned.csv
3. Model Building

File: 03_model_building.ipynb

This notebook includes:

Loading the cleaned dataset
Train-test split
Logistic Regression
Decision Tree
Random Forest
Naive Bayes
Model comparison
Cross-validation
ROC and Precision-Recall curves
Hyperparameter tuning
Feature importance
Prediction example
Final summary
Machine Learning Models Used

The following models were trained and evaluated:

Logistic Regression
Decision Tree
Random Forest
Naive Bayes
Tuned Random Forest
Evaluation Metrics

Since the dataset is highly imbalanced, the following metrics were used:

Accuracy
Precision
Recall
F1-score
ROC-AUC
Confusion matrix
Precision-Recall curve
Final Conclusion

This project completed a full machine learning workflow for credit card fraud detection, including EDA, data cleaning, model training, model evaluation, model comparison, hyperparameter tuning, feature importance analysis, and prediction examples.

Save:

```text
Ctrl + S
