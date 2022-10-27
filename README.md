# Time-Series-Analysis
All about time series analysis using ARIMA model


Time series analysis is a specific way of analyzing a sequence of data points collected over an interval of time. In time series analysis, analysts record data points at consistent intervals over a set period of time rather than just recording the data points intermittently or randomly.

ARIMA models use differencing to convert a non-stationary time series into a stationary one, and then predict future values from historical data. These models use “auto” correlations and moving averages over residual errors in the data to forecast future values
## Summary of work done so far:

1. Used ARIMA model
2. Find p, d, q vales with the help of acf and pacf graphs.
3. Find p, d, q values by using auto_arima
4. compared different AIC.
5. checked errors.
6. Predict Forecast.

## Conclusion
we have discussed the process of finding the values of parameters in the ARIMA modelling. One thing that is also noticeable here is the AIC value that needs to be lower while performing the ARIMA modelling. We can reduce this term by changing the values of the q parameter. 


