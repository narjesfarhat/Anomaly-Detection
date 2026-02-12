# Anomaly-Detection
This project applies three unsupervised anomaly‑detection techniques — Autoencoder, Isolation Forest, and One‑Class SVM — to identify rare fraudulent transactions in a highly imbalanced credit‑card dataset. The notebook includes data preprocessing, model training, evaluation using precision, recall, and F1‑score, and insights into the types of anomalies flagged by each model.

Key Features
Handles a very imbalanced dataset where fraud cases represent less than 0.2% of all transactions.

Compares three anomaly‑detection models on their ability to detect rare fraud cases.

Evaluates performance using precision, recall, F1‑score, and confusion matrices.

Provides insights into which transactions were flagged and patterns in detected anomalies.

Main Findings
Isolation Forest achieved the strongest fraud‑detection performance.

Autoencoder modeled normal transactions extremely well but missed more fraud cases.

One‑Class SVM struggled due to the dataset’s size and imbalance.

Flagged anomalies showed unusual deviations in PCA‑based features (V1–V28).

Contents
Fraud_Detection.ipynb – Full analysis and model comparison

README file (this document)
