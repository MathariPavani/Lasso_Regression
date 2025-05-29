# 🏠 House Price Prediction using LASSO Regression

**Author**: Mathari Pavani & Shalini Jonnadula  
**Published**: May 29, 2025  
**Course**: Data Science Project – Spring 2025  
**Project Focus**: Feature Selection and Predictive Modeling using LASSO Regression

---

## 📌 Project Overview

This project demonstrates the use of **LASSO (Least Absolute Shrinkage and Selection Operator) Regression** for **feature selection and house price prediction** using the **Ames Housing Dataset**. LASSO’s L1 regularization makes it ideal for reducing model complexity and improving prediction accuracy by identifying only the most important features.

---

## 🎯 Objectives

- Apply LASSO Regression for feature selection and dimensionality reduction.
- Predict house prices using the most relevant variables.
- Visualize model performance and coefficient shrinkage.
- Compare LASSO with Ridge and Elastic Net (future scope).
- Evaluate model using MSE, R-squared, and Cross-Validation.

---

## 🛠️ Technologies & Tools

- **Language**: R
- **Libraries**: `glmnet`, `caret`, `ggplot2`, `tidyverse`, `Matrix`, `data.table`
- **Techniques**:
  - LASSO Regression
  - Feature Engineering
  - Cross-Validation
  - Regularization
  - Model Evaluation & Visualization

---

## 📊 Dataset

**Ames Housing Dataset**  
- 📍 [Source](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)  
- 🔢 Observations: 2,930  
- 🧾 Features: 81 total  
  - 38 Numerical  
  - 24 Categorical  
  - 19 Ordinal  
- 🎯 Target: `SalePrice`

---

## ✅ Features Used

After imputation, encoding, and feature engineering, we selected the following key predictors:

- `TotalSquareFootage`: Total above ground + basement area
- `TotalBathrooms`: Full + 0.5 * half bathrooms
- `HouseAge`: Age of the house at the time of sale
- `TotalGarageSize`: Garage area + number of cars
- `TotalPorchArea`: Sum of porch types
- `HasPool`, `HasFence`, `HasFireplace`, `HasMiscFeature`: Binary indicators
- `OverallQualityScore`: Composite score of quality and condition

---

## 📈 Results Summary

| Metric               | Value       |
|----------------------|-------------|
| **MSE**              | 1,282,393,660 |
| **R-squared**        | 0.7948      |
| **Top Predictors**   | `TotalSquareFootage`, `HouseAge`, `OverallQualityScore`, `TotalGarageSize` |

**Key Insights:**

- Larger homes (`TotalSquareFootage`) have higher prices.
- Older homes are priced lower (`HouseAge`).
- Better construction quality (`OverallQualityScore`) increases value.
- `GarageSize` and `Fireplace` presence also contribute positively.

---

## 📊 Visualizations Included

- 📉 Coefficient Path Plot (L1 Shrinkage)
- 🔍 Cross-Validation Curve (Lambda Selection)
- 🧮 Residual Plots
- 📊 Scatter and Boxplots for Key Features vs Sale Price

---

## 🧠 Skills Demonstrated

- Feature Engineering & Data Cleaning  
- Regression Modeling & Regularization  
- Model Tuning with Cross-Validation  
- Interpretation of Sparse Models  
- Data Visualization & Communication  
- Reproducible ML Workflow in R

---

## 📚 Literature References

This project builds on:

- Tibshirani (1996) – Regression Shrinkage and Selection via the LASSO  
- Hastie et al. (2015) – Statistical Learning with Sparsity  
- Xu et al. (2012) – Robust Regression and LASSO  
- Hill (2016), Jonas & Cook (2018), Lee et al. (2020) – Practical LASSO applications  
- [Full references in final report](#https://matharipavani.github.io/Lasso_Regression/)

---

## 📌 Future Work

- Add comparison models (Ridge, Elastic Net)  
- Use non-linear features or interaction terms  
- Build a web app using R Shiny for user input  
- Extend to real estate datasets from other regions  

## 📫 Contact

📧 pavani.mathari@example.com  
🌐 GitHub/LinkedIn (https://github.com/MathariPavani)


