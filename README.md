# London Temperature Forecasting: ARIMA vs SARIMA

## Project Overview

This project uses historical London temperature data from 2016 to 2025 to forecast average monthly temperatures using ARIMA and SARIMA time-series models.

The models were evaluated using both one-shot forecasting and walk-forward validation to compare their forecasting performance.

## Models

- ARIMA
- SARIMA

## Model Performance

| Model | One-Shot MAE | Walk-Forward MAE |
|---|---:|---:|
| ARIMA | 0.99°C | 1.00°C |
| SARIMA | 1.30°C | 1.08°C |

## Final Result

ARIMA achieved the lowest MAE in both one-shot forecasting and walk-forward validation. Therefore, ARIMA was selected as the best-performing model for forecasting monthly London temperatures.

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Statsmodels
- Scikit-learn
- Meteostat

## Kaggle Notebook

View the complete project on Kaggle:

https://www.kaggle.com/code/bolaalonge/london-temperature-forecasting-arima-vs-sarima
