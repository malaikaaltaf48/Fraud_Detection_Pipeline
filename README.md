# Fraud Detection Pipeline

Leak-free fraud detection pipeline built for DecodeLabs Industrial Training (Batch 2026).

## Overview
Detects fraudulent transactions in a highly imbalanced dataset (~0.17% fraud rate) using a properly structured ML pipeline.

## Key Techniques
- SMOTE (Synthetic Minority Over-sampling) for class imbalance
- `imblearn.pipeline.Pipeline` to prevent data leakage
- GridSearchCV for hyperparameter tuning
- Evaluation via Precision, Recall, F1, and ROC-AUC (not accuracy)

## Models
- Logistic Regression (with StandardScaler)
- Random Forest Classifier

## Dataset
[Credit Card Fraud Detection (Kaggle)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
