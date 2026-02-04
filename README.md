# credit-card-fraud-detection
Credit Card Fraud Detection using Logistic Regression
# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using Logistic Regression on a highly imbalanced dataset.

## Problem Statement
Credit card fraud detection is a binary classification problem where fraudulent transactions are extremely rare compared to legitimate ones.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Approach
- Performed exploratory data analysis (EDA)
- Handled class imbalance using stratified train-test split
- Trained Logistic Regression model
- Evaluated using confusion matrix, recall, F1-score

## Key Insight
Recall is prioritized over accuracy since missing a fraud results in financial loss.

## Result
The model demonstrates strong recall for fraudulent transactions while maintaining reasonable precision.

## Future Improvements
- Threshold tuning
- Class weighting
- Advanced models like Random Forest or XGBoost
