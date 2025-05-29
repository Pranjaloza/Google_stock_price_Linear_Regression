# Google_stock_price_Linear_Regression
This repository contains a Jupyter Notebook that predict Google stock closing prices using linear regression models. It uses both simple linear regression (based on the opening price only) and multiple linear regression (using opening price, high, low, and volume) to estimate the closing price.

## What I Did
- Loaded and cleaned the Google stock price dataset.
- Built two models:
  - Simple Linear Regression using the `open` price.
  - Multiple Linear Regression using `open`, `high`, `low`, and `volume`.
- Split data into training and testing sets.
- Trained models and made predictions.
- Evaluated performance with MAE, MSE, and R².
- Analyzed coefficients to understand feature impact.
- Visualized actual vs predicted prices.

## Dataset
- Google Stock Price (2018 - 2025)(google_stock_price.csv)
