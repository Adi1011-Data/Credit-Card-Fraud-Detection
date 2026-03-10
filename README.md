# Credit Card Fraud Detection using XGBoost

## Overview

This project builds a machine learning model to detect fraudulent credit card transactions from a highly imbalanced dataset. The model uses XGBoost to classify transactions as **fraudulent** or **legitimate**.

## Dataset

The dataset contains anonymized transaction features (V1–V28), transaction **Amount**, and a **Class** label:

* `0` → Normal transaction
* `1` → Fraudulent transaction

## Approach

* Data preprocessing
* Handling class imbalance using cost-sensitive learning
* Model training using XGBoost
* Hyperparameter tuning using GridSearchCV
* Evaluation using Precision, Recall, Confusion Matrix, and ROC-AUC

## Results

The model achieves strong fraud detection performance with high **recall** and **ROC-AUC**, making it suitable for detecting rare fraudulent transactions.

## Author

Aditya Jadhav
