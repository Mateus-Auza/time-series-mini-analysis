
# Time Series Analysis in R

This repository contains projects demonstrating classical time series analysis and forecasting using **R** and **Quarto**. The analyses cover the complete modeling workflow, including exploratory data analysis, model identification, parameter estimation, diagnostic checking, model selection, and forecasting.

## Repository Structure
.
├── arma-modeling/
│   ├── arma-modeling.qmd
│   ├── arma-modeling.pdf
│   └── serie4.txt
│
├── sarima-modeling/
│   ├── sarima-modeling.qmd
│   ├── sarima-modeling.pdf
│   └── milk.txt
│
├── LICENSE
└── README.md

```

## Projects

### ARMA Modeling

Analysis of a stationary time series using autoregressive moving average (ARMA) models.

**Topics covered**
- Exploratory time series analysis
- ACF and PACF analysis
- Model order selection using AIC and BIC
- Maximum likelihood estimation
- Residual diagnostics
- Ljung–Box tests
- Rolling one-step-ahead forecasting
- Multi-step forecasting

**Main techniques**
- ARMA model identification
- Model comparison
- Forecast evaluation using Mean Squared Prediction Error (MSPE)

---

### SARIMA Modeling

Analysis of a seasonal monthly time series using Seasonal ARIMA (SARIMA) models.

**Topics covered**
- Variance stabilization using logarithmic transformation
- Seasonal and non-seasonal differencing
- Seasonal ACF and PACF analysis
- SARIMA model selection
- Information criteria (AIC/BIC)
- Residual diagnostics
- Ljung–Box tests
- Multi-step forecasting with prediction intervals

**Main techniques**
- Seasonal ARIMA modeling
- Time series transformation and differencing
- Forecasting of seasonal time series

---

## Software

The analyses were developed using:

- R
- Quarto
- Base R (`stats` package)

## Author

**Mateus Auza Cruz**
```
