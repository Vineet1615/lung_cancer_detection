# 🫁 Lung Cancer Detection

 **Empowering Early Detection with Deep Learning**
This project focuses on predicting lung cancer risk using structured patient data.
It applies machine learning and deep learning techniques to analyze medical and lifestyle factors.
The system is designed to support early screening by identifying high-risk individuals.
Ensemble models and neural networks are used to improve prediction accuracy and stability.

# Features

Predicts lung cancer presence using tabular data

Handles class imbalance using SMOTE

Performs feature selection to remove irrelevant attributes

Uses ensemble learning for robust predictions

Compares machine learning and deep learning performance

# Dataset

The dataset is sourced from Kaggle and contains structured patient records in CSV format.
It includes lifestyle habits and medical symptoms related to lung cancer.
The target variable indicates whether lung cancer is present or not.
Categorical features are encoded, and the dataset is balanced before training.

# Methodology

The data is cleaned, encoded, and balanced using SMOTE to handle class imbalance.
Important features are selected using Recursive Feature Elimination (RFE).
Multiple models are trained, including Random Forest, SVM, and Gradient Boosting.
A stacking ensemble with XGBoost and a deep neural network is used for final prediction.

# Results

The ensemble stacking model achieved high accuracy and strong classification performance.
Neural network models showed good generalization with proper regularization.
Evaluation metrics such as accuracy, precision, recall, and ROC-AUC were used.
The results demonstrate the effectiveness of ensemble learning for lung cancer risk prediction.
