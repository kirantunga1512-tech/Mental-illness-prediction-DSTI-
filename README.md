# 🧠 Mental Illness Prediction Project

This project uses machine learning to predict the presence of mental illness based on patient characteristics data from the *New York State Office of Mental Health (PCS 2019)* dataset.

## 📌 Project Overview
- Dataset: 76 features, 196,102 rows (PCS 2019 survey data).
- Target: Mental Illness (Yes/No).
- Models trained: Random Forest, Decision Tree, Logistic Regression, Neural Network (MLP).
- Techniques used: Data preprocessing, SMOTE for imbalance handling, hyperparameter tuning, model evaluation.

## 🚀 Features
- End-to-end ML pipeline (EDA → Feature Engineering → Model Training → Evaluation).
- Handles class imbalance using *SMOTE*.
- Web app deployment using *Flask/Streamlit*.
- Predictions can be made via a simple user interface.

## 📊 Results
- Logistic Regression achieved the *best CV F1 Score = 0.9515*.
- Decision Tree was the *second-best* with CV F1 = 0.9476.

## Installation
Clone the repository and install dependencies:
```bash

