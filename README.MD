# 📊 Sales and Revenue Prediction

This project builds and compares multiple machine learning regression models to predict **Sales and Revenue**. The goal is to identify the best-performing model based on prediction error.

## Project Overview
Accurate sales and revenue forecasting helps businesses make better decisions regarding production, inventory, and marketing strategies.

In this project, we:
- Clean and preprocess sales data
- Create baseline regression models
- Compare multiple machine learning algorithms
- Select the best model based on performance metrics

## Models Implemented
The following regression models were trained and evaluated:

1. Linear Regression (Baseline Model)
2. KNN Regressor
3. Random Forest Regressor (Ensemble Learning)
4. Gradient Boosting Regressor (Ensemble Learning)
5. Voting Regressor (Ensemble Learning)

## Model Performance

| Model                | Mean Absolute Error (MAE) |
|----------------------|----------------------------|
| Linear Regression    | 662.00                     |
| KNN Regressor        | 893.68                     |
| Random Forest        | 558.11                     |
| Gradient Boosting    | 598.12                     |
| Voting Regressor     | 661.95                     |


## Best Model
The **Random Forest Regressor** performed best.

- Lowest MAE: **558.11**
- R² Score: **51.32%**
- Provides more accurate predictions compared to other models.

Therefore, Random Forest is selected as the final model for sales and revenue prediction.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

