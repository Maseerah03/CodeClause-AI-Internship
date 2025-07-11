# House Price Prediction (Macro-Economic Model)

## Overview

This project focuses on building a predictive model to estimate the future direction of U.S. housing prices based on macroeconomic indicators. The model uses Random Forest classification to predict whether adjusted home prices will increase in the next quarter.

The project combines real estate and economic datasets, performs feature engineering, and evaluates model accuracy using a custom backtesting function. It also examines the importance of each feature in the prediction process.

---

## Data Sources

- **Federal Reserve Economic Data (FRED)**:
  - Mortgage rates (`MORTGAGE30US.csv`)
  - Rental vacancy rate (`RRVRUSQ156N.csv`)
  - Consumer Price Index (CPI) (`CPIAUCSL.csv`)

- **Zillow Housing Data**:
  - Median sale prices
  - Home value indices across metropolitan areas

---

## Key Tasks

- Merged and aligned time-series data from Zillow and FRED
- Adjusted prices for inflation using CPI
- Engineered quarterly forward price comparison target (`Change`)
- Built a binary classification model using:
  - Interest rates
  - Vacancy rates
  - Adjusted prices and values
- Included rolling 52-week feature ratios to improve accuracy
- Performed backtesting to simulate real-world performance
- Visualized prediction accuracy and feature importances

---

## Technologies Used

- Python (Pandas, NumPy)
- scikit-learn (RandomForestClassifier, Permutation Importance)
- Matplotlib
- Google Colab

---

## Results

- The final Random Forest model with rolling ratio features yielded improved predictive accuracy.
- Feature importance analysis showed which macroeconomic factors were most influential in driving price direction.
- Custom visualization highlighted correctly vs incorrectly predicted price changes over time.

---

## Conclusion

This project demonstrates how macroeconomic indicators and time-series feature engineering can be used to predict trends in housing prices. It provides a foundation for modeling financial assets and real estate using publicly available datasets and interpretable machine learning techniques.
