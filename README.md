# CodeAlpha_heart-disease-prediction
# Heart Disease Prediction with Explainable Machine Learning

## Overview
This project explores machine learning techniques for predicting the presence of heart disease using the UCI Heart Disease dataset.

## Objectives
- Perform data cleaning and exploratory data analysis.
- Compare multiple machine learning classification models.
- Evaluate performance using Accuracy, Precision, Recall, F1 Score, and ROC-AUC.
- Interpret model predictions using feature importance and SHAP explainability.

## Dataset
**Source:** [UCI Machine Learning Repository: Heart Disease](https://archive.ics.uci.edu/dataset/45/heart+disease)

The project converts the original target into a binary classification task:
- `0`: No heart disease indicated by the dataset
- `1`: Heart disease indicated by the dataset

## Models Compared
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting

## Tools and Libraries
Python, Google Colab, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SHAP

## Workflow
1. Data loading and preprocessing
2. Exploratory data analysis
3. Train-test split
4. Cross-validation and model comparison
5. Test-set evaluation
6. Feature importance and SHAP explanations
7. Saving the trained model and evaluation results

## Disclaimer
This is an educational machine learning project using a historical dataset. It is not a clinically validated diagnostic system and must not be used to make medical decisions.
