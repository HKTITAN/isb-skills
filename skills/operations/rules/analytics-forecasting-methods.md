---
title: "Forecasting Methods"
impact: HIGH
impactDescription: "Important concept frequently tested in cases"
tags: forecasting, leadership, methods, quantitative, technology
---

**Time Series Methods** (for data with trends and seasonal patterns):
- Moving Average: Simple average of recent n periods; smooths noise but lags trends. Formula: F_t = (D_{t-1} + D_{t-2} + ... + D_{t-n}) / n
- Exponential Smoothing: Weights recent observations more; responsive to changes. Formula: F_t = α × D_{t-1} + (1-α) × F_{t-1}. Higher α (0.7-0.9) gives more weight to recent; lower (0.1-0.3) smoother
- Holt's Linear Trend: Separates level and trend; captures trend component
- Holt-Winters Seasonal: Captures trend and seasonality simultaneously; best for data with both
- ARIMA (AutoRegressive Integrated Moving Average): Advanced method for complex time series; captures autocorrelation and seasonality; requires stationarity testing

**Causal Forecasting** (using explanatory variables):
- Regression Analysis: Linear relationship between dependent (forecast) and independent (drivers) variables
- Example: Sales forecast using price, advertising, competitor pricing
- Assumption: stable relationships (poor when underlying relationships change)
- Elasticity: % change in demand per % change in price (often estimated via regression)

**Forecast Accuracy Metrics**:
- MAE (Mean Absolute Error): Average absolute deviation; interpretable in same units as forecast. MAE = Σ|D_t - F_t| / n
- MSE (Mean Squared Error): Penalizes larger errors more heavily; in squared units
- RMSE (Root Mean Squared Error): Square root of MSE; back in original units
- MAPE (Mean Absolute Percentage Error): Percentage error; useful for comparing across scales. MAPE = Σ|D_t - F_t| / D_t × 100 / n
- Tracking Signal: Cumulative forecast error ÷ MAD; values between -4 and +4 indicate unbiased forecaster; outside this range suggests systematic bias
- Bias: Average forecast error (positive = underfcasting, negative = overforecasting)

**Demand Sensing and Nowcasting**: Real-time demand signals from POS data, web traffic, orders reveal current demand more accurately than traditional forecasting for near-term decisions
