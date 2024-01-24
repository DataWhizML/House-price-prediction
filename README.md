# House Prices - Advanced Regression Techniques

## Overview

This project focuses on predicting house prices using advanced regression techniques. The comprehensive approach includes data cleaning, feature engineering, transformation, categorical feature encoding, feature scaling, and model training using XGBoost, CatBoost, and ensemble techniques.

## Dataset

The dataset for this project consists of house-related features and corresponding prices. The primary goal is to build a robust regression model that accurately predicts house prices.

## Key Steps

### 1. Data Cleaning and Preprocessing

- Imputing missing values to ensure a complete dataset.
- Handling outliers for improved model performance.

### 2. Feature Engineering and Transformation

- Creating new features to enhance predictive power.
- Transforming features for better representation.

### 3. Encoding Categorical Features

- Utilizing appropriate encoding techniques for categorical variables.

### 4. Feature Scaling

- Scaling features to bring them to a standard range.

### 5. Train-Test Split

- Splitting the data into training and testing sets for model evaluation.

### 6. Model Building

- Employing XGBoost with RandomizedSearchCV for hyperparameter tuning.
- Implementing a bagging ensemble of XGBoost and CatBoostRegressor.

### 7. K-Fold Cross Validation

- Evaluating model performance using K-Fold Cross Validation.

## Model Performance

Results from K-Fold Cross Validation:

- **CatBoost:**
  - Mean RMSE: 1.0278
  - Standard Deviation: 0.0

- **XGBoost:**
  - Mean RMSE: 1.0150
  - Standard Deviation: 0.0

## Instructions

To run the code locally, follow these steps:

1. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the main script:

    ```bash
    python house_prices_prediction.py
    ```

## Dependencies

- pandas
- numpy
- scikit-learn
- xgboost
- catboost
- matplotlib
- seaborn

## Acknowledgments

- The project acknowledges the importance of data cleaning and preprocessing for robust modeling.
- Utilizing advanced regression techniques, including XGBoost and CatBoost, for accurate predictions.
- Ensemble techniques are employed for improved model performance.
