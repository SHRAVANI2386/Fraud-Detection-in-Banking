# Fraud Detection in Banking

## Project Overview
This project focuses on detecting fraudulent banking transactions using machine learning techniques. The goal is to classify transactions as fraudulent or non-fraudulent based on transaction data.

## Problem Statement
Fraudulent transactions cause major financial losses in the banking sector. Because fraud cases are rare compared to normal transactions, fraud detection becomes an imbalanced classification problem. This project aims to build a machine learning model that can identify fraudulent transactions effectively.

## Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset. It contains transaction records with features such as anonymized variables, transaction amount, and target class.

- Class 0: Non-fraud transaction
- Class 1: Fraud transaction

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Workflow
1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Data preprocessing
4. Train-test split
5. Baseline Logistic Regression model
6. Balanced Logistic Regression model
7. Random Forest model
8. Model evaluation using confusion matrix, precision, recall, and F1-score
9. Model saving using Joblib

## Model Results
The final selected model achieved the following performance:

- Accuracy: 0.99949
- Precision (Fraud class): 0.91
- Recall (Fraud class): 0.79
- F1-score (Fraud class): 0.84

These results show that the model performs well in identifying fraudulent transactions while maintaining high precision.

## Conclusion
The Random Forest model performed better than the baseline Logistic Regression model for fraud detection. Since the dataset is highly imbalanced, metrics such as precision, recall, and F1-score are more meaningful than accuracy alone.

## Future Scope
- Use SMOTE for handling class imbalance
- Try XGBoost for better performance
- Build a Streamlit web app for fraud prediction
- Deploy the project online

## How to Run the Project
1. Clone the repository
2. Open the Jupyter Notebook
3. Install required libraries
4. Run all cells step by step

## Author
Shravani Gaikwad (CITS766)
