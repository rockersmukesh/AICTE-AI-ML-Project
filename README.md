# Predicting Employee Financial Behaviour Through Digital Payment Usage Analysis

## 📌 Project Overview

This project aims to predict employee financial behaviour based on digital payment usage patterns using Machine Learning techniques.

With the rapid growth of digital payments (UPI, cards, mobile wallets), transaction behaviour reflects financial management patterns. This system analyzes digital payment data and classifies financial behaviour as:

- Good Financial Behaviour
- Bad Financial Behaviour

The project was developed as part of the AICTE Internship Capstone Project.

---

## 🎯 Problem Statement

Organizations lack analytical systems to evaluate financial stability patterns based on employee digital payment usage. 

There is a need for a predictive system that can analyze transaction behavior and classify financial behaviour for better financial awareness and data-driven insights.

---

## 💡 Proposed Solution

The system uses:

- Data preprocessing techniques
- Feature encoding
- Binary classification (Good vs Bad)
- Multinomial Naïve Bayes algorithm
- Performance evaluation metrics

The final output predicts whether an employee demonstrates financially stable behaviour based on digital payment patterns.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## ⚙️ Project Workflow

1. Load Dataset (CSV format)
2. Remove irrelevant columns (e.g., Timestamp)
3. Encode target variable (Good vs Bad)
4. One-hot encode categorical features
5. Stratified Train-Test Split
6. Train Multinomial Naïve Bayes model
7. Evaluate using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - ROC-AUC
   - Confusion Matrix

---

## 🤖 Machine Learning Model

### Algorithm Used:
Multinomial Naïve Bayes

### Why Naïve Bayes?
- Works well with categorical data
- Efficient and fast
- Performs well with one-hot encoded features
- Suitable for classification problems

---

## 📊 Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Classification Report
- ROC-AUC Score
- Confusion Matrix

Output Classes:
- 0 → Bad Financial Behaviour
- 1 → Good Financial Behaviour

---
