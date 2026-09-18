# Credit Card Fraud Detection using Logistic Regression

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using
Machine Learning. Logistic Regression is used as the classification algorithm,
and an undersampling technique is applied to handle the highly imbalanced
dataset.

## 🎯 Objective

The main objective of this project is to:

- Detect fraudulent credit card transactions.
- Handle class imbalance between normal and fraudulent transactions.
- Train a Logistic Regression classification model.
- Evaluate the model using Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and ROC-AUC.

## 📊 Dataset

The project uses the **Credit Card Fraud Detection dataset** from Kaggle.

The dataset contains:

- Total transactions: 284,807
- Normal transactions: 284,315
- Fraudulent transactions: 492
- Fraud percentage: approximately 0.17%

The dataset is highly imbalanced because fraudulent transactions are much fewer
than normal transactions.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Logistic Regression
- Undersampling
- Jupyter Notebook / Google Colab

## 🔍 Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Check missing values
5. Perform statistical analysis
6. Analyze normal and fraudulent transactions
7. Visualize class distribution
8. Split the dataset into training and testing sets
9. Train Logistic Regression model
10. Evaluate the original model
11. Apply undersampling to balance the classes
12. Train Logistic Regression on balanced data
13. Evaluate the balanced model
14. Calculate ROC-AUC
15. Compare model performance

## ⚖️ Handling Class Imbalance

The dataset contains a very small number of fraudulent transactions compared
to normal transactions.

To address this class imbalance, undersampling is applied to the majority
class (normal transactions).

The undersampled dataset contains an equal number of normal and fraudulent
transactions.

- Fraud transactions: 492
- Normal transactions: 492
- Total undersampled transactions: 984

## 🤖 Machine Learning Algorithm

### Logistic Regression

Logistic Regression is used as the classification algorithm to predict whether
a transaction is:

- `0` → Normal Transaction
- `1` → Fraudulent Transaction

## 📈 Model Evaluation

The model is evaluated using the following metrics:

### Accuracy

Measures the percentage of total predictions that are correct.

### Precision

Out of all transactions predicted as fraud, precision tells how many were
actually fraudulent.

### Recall

Out of all actual fraudulent transactions, recall tells how many were correctly
detected by the model.

### F1-Score

F1-Score provides a balance between Precision and Recall.

### Confusion Matrix

The confusion matrix shows:

- True Negative (TN)
- False Positive (FP)
- False Negative (FN)
- True Positive (TP)

### ROC-AUC

ROC-AUC measures the model's ability to distinguish between normal and
fraudulent transactions.

## 📁 Project Structure

```text
credit-card-fraud-detection-logistic-regression/
│
├── Creditcard_Fraud_Logistic_Regression.ipynb
├── README.md
├── requirements.txt
└── .gitignore
