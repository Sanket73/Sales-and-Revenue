# Sales and Revenue Prediction

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
**Programming Language**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Data Processing & Analysis**  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**Data Visualization**  
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

**Machine Learning Library**  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

### Regression Models Implemented:

* Linear Regression

* KNN Regressor

* Random Forest Regressor

* Gradient Boosting Regressor

* Voting Regressor (Ensemble Learning)

### Model Evaluation Metrics:

* Mean Absolute Error (MAE)

* R² Score

### Development Environment: 

* Jupyter Notebook / Anaconda

![Architecture](https://github.com/Sanket73/Sales-and-Revenue/blob/main/image.png?raw=true)

## Conclusion

The Random Forest Regressor achieved the lowest prediction error and the best overall performance among all evaluated models. It provides a strong balance between accuracy and generalization, making it the most suitable model for sales and revenue forecasting in this project.

## Future Improvements

* Perform hyperparameter tuning to further reduce prediction error.

* Experiment with advanced models such as XGBoost or LightGBM.

* Deploy the model using a web framework (Flask/Streamlit) for real-time predictions.
