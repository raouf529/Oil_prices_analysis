# Brent Crude Oil Price Forecasting
analysis of oil prices time series data from 2016 to 2020 using R. The dataset used in this analysis is sourced from [FRED](https://fred.stlouisfed.org/series/POILBREUSDM).

## Content:
- `brent_crude_oil_arima_forecast.ipynb` — full analysis
- `POILBREUSDM.csv` — raw data (FRED)

## Summary:
- The analysis include data understanding, data preparation, ARIMA model selection, model fitting, and forecasting. The code is well commented to explain each step of the analysis process.
- The ARIMA model is used to forecast future oil prices based on historical data. The results of the forecast are visualized to provide insights into the expected trends in oil prices.
- Final model: **ARIMA(0,1,1)** — selected by BIC and residual diagnostics. 
- Test MAPE: **8.04%** over a 10-month horizon




