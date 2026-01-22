# Time-Series-Forecasting
### Background

This project is part of the Tripleten data science practium. Focuses of the project is ARIMA algorithms for time series.

## Project Description

To predict amount of taxi orders withon the next hour based on historical data for client "Swift Lift Taxi". Data is based on tixi rides requested from airports. RMSE should not exceed 48.

**Evaluation metric:** Root mean squared error, mean absolute error

**Models evaluated:** LinearRegression, seasonal_decompose, AutoReg, ar_select_order, auto_arima

## Findings

Autoregression model is suited for seasonal taxi order per hour prediction with a MAE of 37.311 and RMSE of 6.108.

## Software

**Tools:** _python_, _jupyter_

**Libraries:** _pandas_, _sklearn_, _statsmodels_, _pmdarima_
