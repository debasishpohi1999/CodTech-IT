Name: DEBASISH POHI

Company: CODTECH IT SOLUTIONS

ID: CT6WDS227

Domain: Data Analytics

Duration: Jun to July 2024

Mentor: G.SRAVANI

Project Report: Fraud Detection System

Introduction

The objective of this project is to develop a fraud detection system using machine learning techniques to identify fraudulent transactions in financial datasets.
The project utilizes various algorithms, including Random Forest, Isolation Forest, and Local Outlier Factor (LOF), to experiment with different methods for anomaly detection.

Data Description

The dataset used for this project is sourced from Kaggle's credit card fraud detection dataset for 2023.
It contains 568,630 entries with 30 features, including the transaction amount and a binary target class indicating whether a transaction is fraudulent.

Data Preprocessing

Loading Data: The dataset is loaded and the 'id' column is dropped.
Data Overview: Basic statistics and data types are examined to understand the dataset's structure.
Visualization: Distribution of the target class is visualized using count plots. Correlation matrix is plotted to identify relationships between features.

Model Development

The dataset is split into features (X) and target (y), followed by a training and testing split.

- Random Forest Classifier:
A Random Forest model is trained and evaluated.
Metrics: Accuracy, Precision, Recall, and F1-score.
Confusion matrix is plotted to visualize model performance.

- Isolation Forest:
An Isolation Forest model is trained and evaluated as an unsupervised learning method for anomaly detection.
Metrics: Accuracy, Precision, Recall, and F1-score.
Confusion matrix is plotted.

- Local Outlier Factor:
A Local Outlier Factor model is trained and evaluated.
Metrics: Accuracy, Precision, Recall, and F1-score.
Confusion matrix is plotted.

Results

- Random Forest Classifier:
Achieved high accuracy with balanced precision and recall.
Effective in distinguishing between fraudulent and non-fraudulent transactions.

- Isolation Forest:
Useful for detecting anomalies with moderate performance.
Slightly lower accuracy compared to Random Forest.

- Local Outlier Factor:
Effective in identifying outliers but with varying performance.
Comparable accuracy to Isolation Forest.

Conclusion

The fraud detection system developed demonstrates the use of multiple machine learning algorithms for detecting fraudulent transactions.
Random Forest provided the best performance in terms of accuracy and overall metrics. Isolation Forest and Local Outlier Factor also showed promising results, highlighting their potential in anomaly detection scenarios.
This project showcases the importance of experimenting with different algorithms to find the most effective solution for fraud detection.
