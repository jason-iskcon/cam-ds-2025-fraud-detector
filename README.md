# Cambridge Data Science with ML and AI 2025
## Mini Project 1 - Identifying Fraud through anomoly detection

### Overview
This project implements an **unsupervised anomaly detection** pipeline for fraud detection using the ULB Credit Card Fraud dataset. The approach prioritizes recall (minimizing false negatives) over precision, as missed fraud cases incur significantly higher costs than false alarms. The notebook covers exploratory data analysis, feature engineering, and compares three unsupervised anomaly detection algorithms: **Isolation Forest**, **Local Outlier Factor (LOF)**, and **One-Class SVM**. It also includes threshold optimization via PR curves, explainability, and ethical considerations around bias and GDPR compliance.