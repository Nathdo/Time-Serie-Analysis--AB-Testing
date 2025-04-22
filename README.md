# Time Series Analysis & A/B Testing

This repository contains a full end-to-end project that combines Time Series Forecasting and A/B Testing methodologies using real business data. The goal is to evaluate the impact of a marketing action over time while considering natural fluctuations in the data.

## Time Series Forecasting
* Objective: Build a forecasting model to predict baseline values without the marketing intervention.

* Techniques:

  * Data visualization & decomposition
  * Stationarity testing (ADF Test)
  * Differencing techniques to make the series stationary
  * ARIMA and SARIMA modeling
  * Hyperparameter tuning
  * Prophet modeling (with external regressors such as weather and marketing)
 
## Key Learnings

* Importance of stationarity in time series modeling
* How to perform differencing and seasonal decomposition
* How to evaluate an intervention by comparing it with a synthetic baseline
* How to combine machine learning and statistical testing in a robust pipeline
