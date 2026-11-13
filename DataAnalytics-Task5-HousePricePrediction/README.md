
# Task 5: House Price Prediction Using Machine Learning

**Oasis Infobyte – Data Analytics Internship**

## Project Overview

This project predicts residential property prices using machine learning techniques. Linear Regression and Random Forest Regression were trained and evaluated to determine which model provides more accurate predictions.

## Dataset

- Dataset: Housing Prices Dataset
- Source: [Kaggle](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- Total Records: 545
- Total Columns: 13
- Missing Values: 0
- Duplicate Records: 0
- Target Variable: `price`

## Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Project Workflow

1. Dataset loading and exploratory data analysis
2. Data quality checks
3. Categorical feature encoding
4. Training and testing data split (80:20)
5. Linear Regression model training
6. Random Forest Regression model training
7. Model evaluation and comparison
8. Feature importance analysis
9. Final house price predictions

## Model Performance

| Metric | Linear Regression | Random Forest |
|---|---:|---:|
| MAE | 970,043.40 | 1,013,597.00 |
| RMSE | 1,324,506.96 | 1,396,544.00 |
| R² Score | 0.6529 | 0.6141 |

**Best-Performing Model: Linear Regression**

Linear Regression achieved lower prediction errors and a higher R² score than Random Forest on the test dataset.

## Feature Importance

The five most important housing features identified by Random Forest were:

1. Area – 46.40%
2. Bathrooms – 15.25%
3. Air Conditioning – 6.01%
4. Furnishing Status – 5.70%
5. Parking – 5.65%

## Conclusion

The project compared Linear Regression and Random Forest Regression for predicting residential property prices.

Linear Regression performed better on the test dataset, achieving an R² score of 0.6529 compared with 0.6141 for Random Forest.

Feature importance analysis identified property area and bathrooms as influential predictors in the Random Forest model.

The project demonstrates how regression techniques can support house price estimation using structured housing data.

## Future Scope

Future improvements could include cross-validation, hyperparameter tuning and incorporating additional property features such as location and building age.
