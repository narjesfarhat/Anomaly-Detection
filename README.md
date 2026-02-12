# Anomaly Detection

A comprehensive analysis of unsupervised machine learning models for detecting fraudulent transactions in highly imbalanced credit card datasets.

## Overview

This project explores three unsupervised anomaly detection models to identify rare fraudulent transactions:
- **Autoencoder** - Neural network-based approach
- **Isolation Forest** - Tree-based ensemble method  
- **One-Class SVM** - Support Vector Machine for anomaly detection

The analysis includes preprocessing, model training, evaluation, and detailed insights into detected anomalies.

## Key Results

| Model | Performance |
|-------|-------------|
| **Isolation Forest** | Best fraud-detection performance |
| **Autoencoder** | Excellent normal transaction modeling, higher false negatives |
| **One-Class SVM** | Struggled with dataset imbalance |

## Key Insights

- **Metric Selection**: For imbalanced datasets, precision, recall, and F1-score are more informative than accuracy
- **Feature Analysis**: Flagged anomalies showed significant deviations in PCA-based features (V1–V28)
- **Best Performer**: Isolation Forest captured the clearest anomaly patterns and delivered superior results

## Project Structure

- `Fraud_Detection.ipynb` - Complete analysis with model comparison, training, and evaluation

## Technologies Used

- Python
- Scikit-learn
- TensorFlow/Keras (for Autoencoder)
- Pandas & NumPy
- PCA for dimensionality reduction

## Getting Started

1. Clone the repository
2. Install required dependencies
3. Open `Fraud_Detection.ipynb` in Jupyter Notebook
4. Run cells sequentially for full analysis

## License

This project is open source and available for educational purposes.