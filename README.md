# Credit Card Fraud Detection

Machine learning project comparing ways to detect fraud in a highly imbalanced dataset (284,807 transactions, 0.17% fraud).

## What I did
- Showed the "accuracy trap": a baseline with 99.92% accuracy still missed over a third of real fraud
- Compared three imbalance fixes: class weighting, SMOTE, undersampling
- Compared four models: Logistic Regression, Decision Tree, Random Forest, XGBoost
- Validated with 5-fold cross-validation and an untouched 5% holdout set

## Results
- Final model: Random Forest (F1 0.85, ROC-AUC 0.98)
- On the holdout set it caught 19 of 25 frauds at 90% precision

## Tools
Python, pandas, scikit-learn, XGBoost, SMOTE, Jupyter Notebook

## Dataset
Kaggle: Credit Card Fraud Detection (mlg-ulb). Download it and place `creditcard.csv` next to the notebook to run it.
