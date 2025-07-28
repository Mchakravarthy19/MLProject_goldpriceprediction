# Gold Price Prediction & Forecasting

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=Jupyter)](https://jupyter.org/)
This project focuses on predicting gold prices using machine learning techniques like Random Forest Regression, based on economic indicators such as S&P 500, oil prices, and silver prices.

---

## Project Overview

This notebook demonstrates:
- Loading and analyzing a gold price dataset
- Visualizing feature correlations
- Training a regression model
- Evaluating prediction accuracy

## Dataset

The dataset includes:
- `SPX`: S&P 500 Index
- `USO`: United States Oil Fund
- `SLV`: Silver price
- `GLD`: Gold price (target)

> Ensure you include or reference the dataset (`gld_price_data.csv`) in your repo.

---

## Tech Stack

| Tool | Description |
|------|-------------|
| Python | Main programming language |
| pandas & numpy | Data handling |
| matplotlib & seaborn | Data visualization |
| scikit-learn | Model building and evaluation |

---

## Workflow Summary

1. **Data Loading & Exploration**
   - Basic info, null check, data shape
2. **Visualization**
   - Correlation heatmaps and pairplots
3. **Modeling**
   - Train-test split (80:20)
   - Random Forest Regressor
4. **Evaluation**
   - R² Score
   - MAE, MSE, RMSE
   - Graphical comparison (Actual vs Predicted)

---
