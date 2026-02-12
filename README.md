# Anomaly-Detection

This project explores three unsupervised models — Autoencoder, Isolation Forest, and One‑Class SVM — to detect rare fraudulent transactions in a highly imbalanced credit‑card dataset. The notebook includes preprocessing, model training, evaluation, and insights into the flagged anomalies.

Models Used
Autoencoder

Isolation Forest

One‑Class SVM

Key Results
Isolation Forest achieved the best fraud‑detection performance.

Autoencoder modeled normal transactions very well but missed more fraud.

One‑Class SVM struggled with the dataset’s imbalance.

Insights
Fraud cases are extremely rare, so precision, recall, and F1‑score are more important than accuracy.

Flagged anomalies showed strong deviations in PCA‑based features (V1–V28).

Isolation Forest captured the clearest anomaly patterns.

Contents
Fraud_Detection.ipynb — full analysis and model comparison.
