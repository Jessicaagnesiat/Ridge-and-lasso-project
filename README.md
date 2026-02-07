# Boston Housing Price Prediction using Ridge and Lasso Regression

## Overview
The Boston Housing dataset contains multiple correlated features that can negatively affect the stability and interpretability of linear regression models. This project applies Ridge and Lasso Regression to handle multicollinearity and improve model generalization when predicting housing prices.

## Problem Statement
Multicollinearity among features in the Boston Housing dataset can lead to unstable coefficients and poor generalization in traditional linear regression models.

## Objectives
- Identify and handle multicollinearity among housing features  
- Compare Ridge and Lasso Regression performance  
- Evaluate model generalization using unseen test data  
- Interpret feature importance in housing price prediction  

## Dataset
- **Source:** Boston Housing Dataset  
- **Target Variable:** Median value of owner-occupied homes (MEDV)  
- **Features:** Crime rate, number of rooms, pollution level, tax rate, distance to city center, and others  

## Methodology
1. **Data Splitting**
   - Train, validation, and test sets were created to ensure unbiased evaluation.
2. **Multicollinearity Analysis**
   - Variance Inflation Factor (VIF) and correlation analysis were used.
   - Highly correlated features were reduced to improve model stability.
3. **Modeling**
   - Ridge Regression and Lasso Regression were implemented.
   - Multiple regularization strengths (alpha values) were tested.
4. **Model Evaluation**
   - RMSE, MAE, MAPE, and R² metrics were used for performance comparison.

## Results
- Ridge Regression achieved stable performance but showed lower generalization on test data.
- Lasso Regression outperformed Ridge on unseen data with a higher R² score (64.18%).
- Lasso also performed feature selection by shrinking less important coefficients to zero.

## Conclusion
Lasso Regression proved to be more effective in predicting unseen housing prices, offering better generalization and model interpretability compared to Ridge Regression.

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Statsmodels
- Matplotlib & Seaborn

## Key Takeaways
- Regularization is essential when dealing with multicollinearity.
- Lasso Regression provides both predictive power and feature selection.
- Model evaluation on unseen data is critical for reliable performance assessment.

## Author
Jessica Agnesia Tataung
