# TimeSeriesProject


# Overview
This project focuses on forecasting a non-stationary time series dataset. I used Python's Statsmodels and Pandas to handle statistical tests, data transformation, and model selection.

# Goals
1) Identify non-constant variance and check for stationarity.
2) Normalize and stabilize variance through data transformations.
3) Achieve stationarity with differencing.
4) Select the best ARIMA model based on statistical criteria.
5)Use the model to forecast future values and evaluate its accuracy.

# Steps
1) Statistical Tests: Used Engle's ARCH test for variance and the Augmented Dickey-Fuller test for stationarity.
2) Transformations: Tried logarithmic and Box-Cox transformations to address variance and normalize data.
3) Differencing: Applied to make the series stationary, setting the stage for ARIMA modeling.
4) Model Selection: ACF and PACF plots, along with AIC values, guided us to choose ARIMA(2,0,3).
5) Forecasting: Forecasted future values using our model, assessing accuracy with the RMSE metric against a test dataset.
6) Results: The ARIMA(2,0,3) model was selected and used for forecasting, showing good predictive accuracy based on RMSE evaluation.

# Tools Used
Python: For programming.
Statsmodels: For statistical tests and modeling.
Pandas: For data handling.

# Conclusion
This project applied standard time series analysis techniques to predict future data points. The approach and tools used here can be adapted for similar forecasting tasks.
