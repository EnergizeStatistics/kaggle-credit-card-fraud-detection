# Credit Card Fraud Detection #
This repository hosts Python code for credit card fraud detection. 

## Description ##
Credit card fraud is a problem that receives significant attention both in the real world and on Kaggle. From Kaggle public kernels and data science blogs I often see that people use boosting methods such as LightGBM and XGBoost to attack this problem. On the other hand, credit card fraud is a typical anomaly detection issue but I seldom see data scientists use algorithms that are commonly considered to be dedicated to anomaly detection such as Isolation Forest, one-class SVM, Local Outlier Factor, etc. Is their lack of popularity due to performance? How do the performance of these methods compare?

This analysis uses [Kaggle Credit Card Fraud Detection data](https://www.kaggle.com/mlg-ulb/creditcardfraud/ "Kaggle Credit Card Fraud Detection"). The Kaggle page has a detailed description of the dataset; basically we have 30 numerical input features that are the result of PCA transformation and 1 normal/fraud target where 0.172% of all transactions are fraud.

## Requirements ##
* `Python` and analytical packages `pandas`, `numpy`, `sci-kit learn`, `matplotlib`, `xgboost`, `lightgbm`.