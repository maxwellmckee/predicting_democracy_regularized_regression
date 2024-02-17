# Predicting Democracy Index with Regularized Regression

## Overview
This repository hosts a Python notebook dedicated to investigating the correlation between income per capita, democracy, and additional demographic factors across 195 countries during the period from 1960 to 2000. Through the application of several regularized regression techniques, including Ridge, Lasso, Adaptive Lasso, and Elastic Net, we aim to forecast the democracy index with respect to the aforementioned variables.

## Data Preparation
- **Dataset**: "income democracy.csv", featuring real GDP per capita, democracy index, and other demographic variables.
- **Splitting Strategy**: The dataset is divided into an 80% training set and a 20% testing set, with any instances of missing data excluded from the analysis.

## Models & Evaluation
The assignment leverages the following regression models for analysis:
- Ridge Regression
- Lasso Regression
- Adaptive Lasso Regression
- Elastic Net Regression

### Key Steps:
1. **Model Training**: Each model is fitted using the training dataset.
2. **Parameter Tuning**: Optimal tuning parameters are identified through cross-validation, focusing on the lambda parameter for all models and the alpha parameter for the Elastic Net regression model.
3. **Coefficient and MSPE Reporting**: The coefficients obtained with optimal parameters are reported alongside the Mean Square Prediction Error (MSPE) for the test dataset.

## Conclusion
The notebook concludes with a critical comparison of the models to identify the most effective predictor of the democracy index based on empirical performance metrics and the suitability of each model.

## Requirements
- `numpy`
- `pandas`
