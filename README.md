# Regression-Task (Medical Insurance Charges Prediction)

## Project Overview
This project aims to predict medical insurance charges using Machine Learning regression models.

## Dataset
The dataset contains information about individuals, including:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region

The target variable is `charges`, which represents the medical insurance cost.

## Models Used
- Linear Regression
- Random Forest Regression
- Gradient Boosting Regression

## Model Comparison

| Model | R² Score |
| Gradient Boosting | 0.850912 |
| Random Forest | 0.829398 |
| Linear Regression | 0.742579 |

## Evaluation Metrics
The models were evaluated using:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

## Best Model
The **Gradient Boosting Regression** model achieved the best performance with an R² score of **0.850912**, outperforming Random Forest and Linear Regression.

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Goal
The main goal is to build and compare regression models to predict medical insurance charges accurately.
