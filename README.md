Fraud Detection in Financial Transactions

- Overview

This project focuses on identifying suspicious or fraudulent financial transactions using anomaly detection techniques on anonymized transaction data. It addresses extreme class imbalance by applying unsupervised learning and presents alert based visual dashboards in Jupyter Notebook.

- Objectives

Detect fraudulent transactions
Handle highly imbalanced fraud data
Generate risk based fraud alerts
Visualize fraud patterns and trends

- Dataset

The dataset contains anonymized financial transaction data with no personally identifiable information. Features include transaction amount time based variables and user behavior history.

- Methodology

Data preprocessing includes duplicate removal numerical feature selection and feature scaling.
Isolation Forest is used for anomaly detection to identify rare fraudulent patterns.
Anomaly scores are converted into fraud alerts using threshold based logic.
Class imbalance is handled using unsupervised learning and evaluation focuses on precision recall and ROC AUC.

- Alert Based Dashboard

The Jupyter Notebook includes visualizations such as alerts distribution by risk level risk score distribution transaction amount versus risk score fraud alerts by hour of day fraud alerts by day of week and high risk transaction tables.

-  Project Structure

Fraud_Detection_In_Financial_Transactions.ipynb
fraud_alerts.csv
README.md

- Evaluation Metrics

Precision
Recall
F1 score
ROC AUC

- Tools and Technologies

Python
Pandas
NumPy
Scikit learn
Matplotlib
Jupyter Notebook

- Business Impact

Enables early identification of high risk transactions reduces false positives improves fraud investigation efficiency and supports data driven decision making.

- Future Enhancements

AutoEncoder based anomaly detection
Real time fraud monitoring
Interactive dashboard integration

- Author
Gayathri Polepalli



If you want, I can also make a **shorter README**, **internship submission version**, or **resume aligned version**.
