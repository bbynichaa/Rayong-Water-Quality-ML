# Rayong-Water-Quality-ML
Machine Learning-Based Estimation of Surface Water Quality Using Reduced Monitoring Parameters in Rayong Province.
# Machine Learning-Based Surface Water Quality Estimation

2107541 — Machine Learning for Environmental Applications

## Project Overview

This project investigates the potential of machine learning to estimate the Water Quality Index (WQI) using reduced monitoring parameters in Rayong Province, Thailand.

## Objectives

- Identify the best-performing machine learning model.
- Reduce the number of water quality monitoring parameters.
- Evaluate model prediction performance.
- Investigate feature importance using Explainable AI.

## Dataset

- Study Area: Rayong Province, Thailand
- Study Period: 2018–2024
- Raw Observations: 447
- Monitoring Stations: 27
- Target Variable: WQI

## Machine Learning Models

- Multiple Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest
- Gradient Boosting
- XGBoost

## Methodology

- Data Preprocessing
- Exploratory Data Analysis
- Feature Selection
- Regression
- Cross-Validation
- Hyperparameter Tuning
- Model Evaluation
- Explainable AI (SHAP)

## Key Findings

- Best Model: XGBoost
- R²: 0.6854
- MAE: 4.2617
- RMSE: 5.8264
- Feature Reduction: 50%
- Selected Features: DO, NO₃-N, NH₃-N
- Most Influential Feature: NH₃-N

## Conclusion

Machine learning demonstrates potential for faster preliminary water quality assessment using fewer monitoring parameters. Further validation is required before practical implementation.

## Tools and Libraries

Python, Google Colab, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost and SHAP.
