# Credit Card Fraud Detection

## Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. Due to the highly imbalanced nature of fraud datasets, under-sampling was applied to create a balanced dataset for model training.

The model was trained using Logistic Regression and evaluated using classification metrics.

## Features

- Data preprocessing
- Missing value analysis
- Fraud vs Legit transaction analysis
- Handling imbalanced dataset using Under-Sampling
- Feature scaling using StandardScaler
- Logistic Regression model training
- Model evaluation
- Single transaction fraud prediction

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-Learn

## Machine Learning Workflow

1. Dataset Loading
2. Data Exploration
3. Data Cleaning
4. Fraud Distribution Analysis
5. Under-Sampling
6. Train-Test Split (80-20)
7. Feature Scaling
8. Model Training (Logistic Regression)
9. Model Evaluation
10. Prediction

## Model Used

Logistic Regression

## Evaluation Metrics

- Accuracy Score
- Classification Report
- Precision
- Recall
- F1 Score

## Dataset

The dataset used in this project can be accessed here:

Kaggle Dataset Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Target Variable:

- 0 → Legit Transaction
- 1 → Fraudulent Transaction

## Future Improvements

- Apply SMOTE instead of under-sampling
- Try Random Forest and XGBoost
- Hyperparameter tuning
- Deploy as a web application

Note: Dataset file is not included in this repository due to size considerations. Please download it from the Kaggle link above.
