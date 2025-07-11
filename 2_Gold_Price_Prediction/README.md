# Gold Price Prediction

## Overview

This project aims to build a regression model that predicts gold prices (GLD) based on various financial indicators. The model utilizes Random Forest Regressor from scikit-learn and evaluates performance using R-squared error metrics.

This project explores the relationship between gold prices and market factors such as the US dollar index, crude oil prices, and stock volatility. It also includes data visualization, correlation analysis, and prediction vs. actual comparison.

---

## Dataset Description

- **Source**: GLD historical price dataset (`gld_price_data.csv`)
- **Target Variable**: `GLD` (Gold ETF price)
- **Features Used**:
  - SPX (S&P 500 Index)
  - USO (Crude Oil ETF)
  - SLV (Silver ETF)
  - EUR/USD Exchange Rate

---

## Key Tasks

- Loaded and cleaned the dataset
- Explored correlations using a heatmap
- Visualized the distribution of gold prices
- Split the dataset into training and testing sets
- Trained a Random Forest Regressor
- Evaluated the model using R² score
- Visualized actual vs. predicted gold prices

---

## Technologies Used

- Python (NumPy, Pandas)
- Matplotlib, Seaborn for visualization
- scikit-learn (train_test_split, RandomForestRegressor, r2_score)
- Google Colab (development environment)

---

## Results

- The Random Forest Regressor achieved strong predictive performance on the test set.
- The R² score confirmed the model’s effectiveness in capturing the price behavior of gold.
- Visualization of actual vs. predicted prices showed good alignment and general trend capture.

---

## Conclusion

This project demonstrates the use of machine learning for financial prediction tasks. By leveraging ensemble learning and real-world financial indicators, the model provides insights into gold price forecasting with a high level of accuracy.
