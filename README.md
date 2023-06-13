# Forecasting
### Forecasting Different Methods

1. Model based
	- Linear regression
	- Autoregressive models
	- ARIMA
	- Logistic regession
	- Econometric models


- Linear Model                   $Y_t = \beta_o+\beta_1t+\epsilon$ 
- Exponential Model          $Log(Y_t) = \beta_0+\beta_1t+\epsilon$
- Quadratic Model              $Y_t = \beta_0+\beta_1t+\beta_2t^2+\epsilon$
- Additive Seasonality        $Y_t = \beta_0+\beta_1D_{jan}+\beta_2D_{Feb}+...+\beta_{11}D_{Nov}+\epsilon$
- Additive Seasonality with Quadratic Trend         $Y_t = \beta_0+\beta_1t+\beta_2t^2+\beta_3D_{Jan}+...+\beta_{13}D_{Nov}+\epsilon$
- Multiplicative Seasonality       $Log(Y_t) = \beta_0+\beta_1D_{Jan}+\beta_2D_{Feb}+\beta_3D_{Mar}+...+\beta_11D_{Nov}+\epsilon$

In my time series forecasting project, I employed the SARIMAX model along with various linear models to predict future trends.
By utilizing SARIMAX, I aimed to capture the seasonal and autoregressive components of the time series data, while the linear 
models provided additional insights into the underlying linear relationships. Through extensive experimentation and model selection,
I evaluated the performance of each approach and identified the most effective models for accurate time series forecasting. 
This project demonstrates my ability to leverage different modeling techniques to uncover patterns and make informed predictions in time-dependent data.
