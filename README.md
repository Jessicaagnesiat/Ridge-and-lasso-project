# 🏡 Boston Housing Price Prediction

> **Predicting housing prices using Ridge and Lasso Regression to address multicollinearity and improve model generalization.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![Statsmodels](https://img.shields.io/badge/Statsmodels-005571?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

---

# 📌 Project Overview

Accurate house price prediction is essential for property valuation, investment decisions, and urban planning. However, highly correlated features can reduce the stability and interpretability of traditional Linear Regression models.

This project compares **Ridge Regression** and **Lasso Regression** to mitigate multicollinearity, improve prediction performance, and identify the most influential factors affecting housing prices.

---

# 🎯 Business Problem

Traditional Linear Regression models often struggle with **multicollinearity**, where highly correlated features produce unstable coefficients and reduce prediction performance on unseen data.

A more robust predictive model is required to improve generalization while maintaining model interpretability for real estate price prediction.

---

# 🎯 Project Goals

- Predict housing prices using regularized regression models.
- Detect and mitigate multicollinearity using Variance Inflation Factor (VIF).
- Compare Ridge Regression and Lasso Regression performance.
- Evaluate model generalization using unseen test data.
- Identify the most influential housing features.
- Recommend the most suitable regression model for house price prediction.

---

# 📂 Dataset

**Boston Housing Dataset**

The dataset contains housing information collected from suburbs of Boston.

### Target Variable

- **MEDV** (Median value of owner-occupied homes)

### Features

- Crime Rate
- Residential Land Zoning
- Industrial Area
- Charles River Proximity
- Nitric Oxide Concentration
- Average Number of Rooms
- House Age
- Distance to Employment Centers
- Property Tax Rate
- Student-Teacher Ratio
- Lower Status Population
- Other socioeconomic indicators

---

# 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 🔍 Analysis Techniques

- Data Splitting
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Variance Inflation Factor (VIF)
- Feature Selection
- Ridge Regression
- Lasso Regression
- Hyperparameter Tuning
- Model Evaluation

---

# 🏗️ Project Workflow

```text
Raw Dataset
      │
      ▼
Train / Validation / Test Split
      │
      ▼
Correlation Analysis
      │
      ▼
Variance Inflation Factor (VIF)
      │
      ▼
Feature Selection
      │
      ▼
Ridge Regression
      │
      ▼
Lasso Regression
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Model Evaluation
      │
      ▼
Model Comparison
      │
      ▼
Business Recommendation
```

---

# 📊 Model Performance

| Metric | Ridge | Lasso |
|---------|-------:|-------:|
| RMSE (Test) | 5.159 | **5.125** |
| MAE (Test) | **3.244** | 3.398 |
| MAPE (Test) | **17.62%** | 17.86% |
| R² (Test) | 58.13% | **64.18%** |

---

# 🔍 Key Findings

- Strong multicollinearity was identified among several housing features.
- Removing redundant features improved model stability.
- Ridge Regression produced stable coefficients for correlated variables.
- Lasso Regression automatically selected the most important features by shrinking less influential coefficients to zero.
- Lasso Regression achieved the highest test R² score (64.18%), indicating better generalization on unseen data.

---

# 💡 Business Recommendations

| Recommendation | Business Value |
|---------------|----------------|
| Deploy Lasso Regression for house price prediction. | Provides better predictive performance on unseen housing data. |
| Apply feature selection before model training. | Reduces model complexity and improves interpretability. |
| Monitor highly correlated variables during feature engineering. | Prevents unstable coefficients and improves model reliability. |
| Prioritize influential housing characteristics such as room count, accessibility, and environmental quality. | Supports more accurate property valuation and pricing strategies. |
| Periodically retrain the model using updated housing market data. | Maintains prediction accuracy as market conditions change. |

---

# 🚀 Business Impact

This project demonstrates how machine learning can support:

- Accurate property valuation.
- Better real estate investment decisions.
- Explainable housing price prediction.
- Robust predictive modeling under multicollinearity.
- Data-driven decision making for real estate analytics.

---

# 🧠 Skills Demonstrated

- Machine Learning
- Regression Modeling
- Ridge Regression
- Lasso Regression
- Multicollinearity Analysis
- Variance Inflation Factor (VIF)
- Feature Selection
- Hyperparameter Tuning
- Model Evaluation
- Statistical Analysis
- Data Visualization

---

# 📁 Repository Structure

```text
Boston-Housing-Price-Prediction
│
├── notebook/
│   └── Boston_Housing_Price_Prediction.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── ridge_actual_vs_predicted.png
│   ├── lasso_actual_vs_predicted.png
│   └── coefficient_comparison.png
│
└── README.md
```

---

# 👩‍💻 Author

**Jessica Agnesia Tataung**

- LinkedIn: https://www.linkedin.com/in/jessicaagnesiat/

🌐 Portfolio Website

https://jessicaagnesiat.github.io/portofolio-data-scientist/

---

⭐ If you found this project useful, feel free to give it a star!
