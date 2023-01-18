# Google Stocks Forecasting


<b> Time Series Forecasting means analyzing and modeling time-series data to make future decisions. Some of the applications of Time Series Forecasting are weather forecasting, sales forecasting, business forecasting, stock price forecasting, etc. The ARIMA model is a popular statistical technique used for Time Series Forecasting </b>


## ARIMA stands for Autoregressive Integrated Moving Average. 
### It is an algorithm used for forecasting Time Series Data. 
### ARIMA models have three parameters like ARIMA(p, d, q).

Here p, d, and q are defined as: <br>

p is the number of lagged values that need to be added or subtracted from the values (label column). It captures the autoregressive part of ARIMA.<br>

d represents the number of times the data needs to differentiate to produce a stationary signal. If it’s stationary data, the value of d should be 0, and if it’s seasonal data, the value of d should be 1. d captures the integrated part of ARIMA.<br>

q is the number of lagged values for the error term added or subtracted from the values (label column). It captures the moving average part of ARIMA.

##### Will be using Google Stock Price data using Yahoo Finance API.

### As the data is 'Seasonal' will be using SARIMA.

## Forcasted Values

![download](https://user-images.githubusercontent.com/67755812/213175201-c1588eda-73a9-47da-a04f-09bcdf1be2bc.png)

