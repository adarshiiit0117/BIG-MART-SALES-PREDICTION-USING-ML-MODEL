# BigMart Sales Prediction

This repository contains a machine learning project aimed at predicting the sales of products in BigMart stores. The project involves data preprocessing, feature engineering, model training, and evaluation. The goal is to build a model that can accurately predict the sales based on various features such as item type, store type, and other relevant attributes.

## Project Overview

- **Data Source**: The dataset used in this project contains information about products, stores, and their respective sales. It includes features such as item type, item weight, visibility, and store establishment year, among others.

- **Objective**: The objective of this project is to predict the sales of products in BigMart stores using the provided features. The model is trained to minimize the difference between the predicted sales and the actual sales.

## Model and Evaluation

- **Model Used**: XGBoost Regressor
- **Training Data R-squared**: 0.64
- **Test Data R-squared**: 0.59



## Steps in the Notebook

1. **Data Loading**: The dataset is loaded into the notebook and basic exploration is performed.
2. **Data Preprocessing**: Missing values are handled, and categorical features are encoded.
3. **Feature Engineering**: New features are created based on existing ones to improve model performance.
4. **Model Training**: The XGBoost Regressor model is trained using the preprocessed data.
5. **Evaluation**: The model's performance is evaluated using the R-squared metric on both training and test data.



