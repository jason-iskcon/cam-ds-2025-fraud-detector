# Cambridge Data Science with ML and AI 2025
## Mini Project 1 - Identifying fraud through anomaly detection

### Overview
This project builds an **unsupervised anomaly detection** pipeline for fraud detection, using the ULB Credit Card Fraud dataset.

The approach prioritises recall (minimising false negatives) over precision, because a missed fraud costs far more than a false alarm.

The notebook covers exploratory data analysis and feature preparation, then compares three unsupervised anomaly detection algorithms:

1. **Isolation Forest**
2. **Local Outlier Factor (LOF)**
3. **One-Class SVM**

It also covers choosing an alert threshold from precision-recall curves, explaining why transactions were flagged, and the ethical considerations of bias and GDPR compliance.

### Status
Stages 1 to 3 (environment setup, data loading and exploratory data analysis) are complete. The modelling stages (4 to 12) are outlined in the notebook and will be added next.
