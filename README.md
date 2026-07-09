# thyroid-disease-prediction-ml
# Thyroid Disease Prediction using Machine Learning

## Overview

Early detection of thyroid disorders is essential for improving patient outcomes and supporting timely medical intervention. This project develops a machine learning model capable of classifying patients into three categories:

- Hyperthyroid
- Hypothyroid
- Negative (No Thyroid Disease)

The implementation includes data preprocessing, feature engineering, model training, hyperparameter optimization, and performance evaluation using multiple machine learning algorithms.

---

## Problem Statement

Thyroid diseases affect millions of people worldwide and can significantly impact metabolism, energy levels, and overall health. Because the dataset contains imbalanced classes, accurately identifying patients with thyroid disorders presents a challenging classification problem.

This project investigates several machine learning techniques to improve prediction accuracy while maintaining strong performance on minority classes.

---

## Features

- Data preprocessing
- Missing value handling
- Outlier detection and removal
- Feature engineering
- Class imbalance handling
- Hyperparameter optimization
- Model comparison
- Performance visualization

---

## Dataset

The project uses a publicly available Kaggle thyroid disease dataset containing over **9,000 patient records** with demographic information, medical history, and laboratory test results.

The dataset includes:

- Age
- Sex
- Medical history
- Hormone measurements (TSH, T3, TT4, T4U, FTI, TBG)
- Referral information
- Thyroid diagnosis

---

## Machine Learning Models

The following classifiers were evaluated:

- Decision Tree
- AdaBoost
- Naive Bayes

To improve performance on imbalanced classes, AdaBoost was further optimized using:

- Balanced class weights
- Customized class weights
- GridSearchCV hyperparameter tuning

---

## Technologies

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Results

Several classification models were compared using Accuracy, Precision, Recall, and F1-score.

The best-performing model was **AdaBoost with customized class weights**, achieving:

- **Accuracy:** 98%
- **F1-score:** 91%

The optimized AdaBoost model demonstrated improved detection of minority classes while maintaining excellent overall classification performance.

---

## Repository Contents

- Data preprocessing pipeline
- Feature engineering
- Model training
- Hyperparameter tuning
- Performance evaluation
- Data visualization

---

## Future Improvements

- Deep learning models
- Ensemble learning techniques
- Explainable AI (XAI)
- External clinical validation
- Deployment as a clinical decision support tool

---
