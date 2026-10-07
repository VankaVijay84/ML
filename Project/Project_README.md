# 🎬 Box Office Revenue Prediction Using Random Forest & XGBoost

## 📌 Project Overview

**Box Office Revenue Prediction** is a machine learning project that predicts the worldwide box office revenue of a movie based on different movie-related features.

The project uses two powerful machine learning regression algorithms:

1. **Random Forest Regressor**
2. **XGBoost Regressor**

The models are trained on a synthetic dataset containing **1,200 movie records**. After training, both models are evaluated and compared using **MAE, RMSE, and R² Score**.

The project also provides feature-importance analysis, visualization of predictions, and the ability to predict the expected revenue of a new movie.

> **Note:** The supplied dataset is synthetic and is intended for educational and project demonstration purposes.

---

## 🎯 Objective

The main objective of this project is to develop a machine learning system capable of estimating movie box office revenue based on available movie characteristics.

The project aims to:

- Analyze movie-related data.
- Perform exploratory data analysis.
- Preprocess data for machine learning.
- Train Random Forest and XGBoost regression models.
- Compare model performance.
- Identify important features affecting revenue.
- Predict revenue for a new movie.

---

## 🧠 Machine Learning Models

### 1. Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines multiple decision trees to produce a more reliable prediction.

It is suitable for this project because it can:

- Handle nonlinear relationships.
- Work with multiple features.
- Reduce overfitting compared with a single decision tree.
- Estimate feature importance.
- Perform well on structured/tabular datasets.

### 2. XGBoost Regressor

XGBoost (Extreme Gradient Boosting) is a powerful gradient boosting algorithm that builds decision trees sequentially.

Each new tree attempts to correct the errors made by previous trees.

XGBoost is useful because it:

- Handles complex relationships between features.
- Provides strong predictive performance.
- Works efficiently with structured datasets.
- Supports regression problems.
- Provides feature importance analysis.

---

## 🎯 Target Variable

The target variable used for prediction is:

```text
Box_Office_Revenue_Million_USD
