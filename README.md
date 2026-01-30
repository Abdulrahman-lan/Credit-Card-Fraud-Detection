# Fraud Shield: Credit Card Fraud Detection

This project uses Logistic Regression to identify fraudulent credit card transactions. The goal is to build a reliable system that can distinguish between legitimate and suspicious financial activities.

---

## Project Results & Visualization
Below is the **Confusion Matrix** which shows exactly how the model performed on the test data:

![Confusion Matrix](confusion_matrix.png)

### Model Performance Metrics:
* **True Negatives (Correctly identified normal):** 56,851
* **True Positives (Correctly identified fraud):** 47
* **False Positives (Normal flagged as fraud):** 13
* **False Negatives (Missed fraud cases):** 51

> **Insight:** The very low number of **False Positives (13)** indicates that the model is highly efficient at not bothering legitimate customers with false alarms.

---

## Data Insights
We analyzed the transaction amounts to see the difference between normal (Class 0) and fraud (Class 1) cases:

![Transaction Distribution](transaction_distribution.png)

The chart shows that fraudulent transactions tend to have a higher average amount (around 120) compared to normal transactions.

---

## Project Overview
The model was trained on a dataset of over 284,000 transactions. The primary challenge was the high imbalance in the data, which was handled through normalization and careful feature scaling.

---

## Key Technical Details
* **Data Preparation**: Scaled features and split the dataset into training and testing sets.
* **Model Used**: Logistic Regression.
* **Performance**: The model achieved an overall accuracy of 99.58%.

---

## Files in this Repository
* **Fraud_Shield.ipynb**: Main notebook with the Python implementation.
* **requirements.txt**: List of Python libraries used (Pandas, Scikit-Learn, etc.).
* **confusion_matrix.png**: Visualization of model performance.
* **transaction_distribution.png**: Visualization of data analysis.

---
## Team Members
* Abdulrahman Aljeelani
* Abdulrahman Jilani
* Omar Mahdi
* Rashed AlRadadi
* Hamza Jan