# Predict-the-temparature-in-delhi
Predict the temperature column ‘ _tempm’ for Delhi, using Time Series Forecasting
Predicting Time-series sata, using "Daily Climate time series data" dataset from Kaggle. The Dataset contains daily climate data in the city of delhi from 2013 to 2017. In this project to keep things simple I would only work with temprature to keep this a univariate time-series problem

The model is in Delhi_daily_temp.py and acc_plotter.py is a helper function.
The training data is available from Jan 1996 - Nov 2016. We will use data from Dec 2016 -
April 2017 to check the model accuracy/validity.
Model must take a date as input and output the probable temperature for that day (so basically
forecast to the given date and then report the value of that date)

##Timeseries Analysis-(ARIMA Model)
For prediction we are going to use one of the most popular model for time series, Autoregressive Integrated Moving Average (ARIMA) which is a standard statistical model for time series forecast and analysis. An ARIMA model can be understood by outlining each of its components as follows:

Autoregression (AR) - refers to a model that shows a changing variable that regresses on its own lagged, or prior, values.
The notation AR(p) indicates an autoregressive model of order p.
Integrated (I) - represents the differencing of raw observations to allow for the time series to become stationary, i.e., data values are replaced by the difference between the data values and the previous values.
Moving average (MA) - incorporates the dependency between an observation and a residual error from a moving average model applied to lagged observations.

The notation MA(q) refers to the moving average model of order q:
Autocorrelation Function (ACF): It just measures the correlation between two consecutive (lagged version). example at lag 4, ACF will compare series at time instance t1…t2 with series at instance t1–4…t2–4

Partial Autocorrelation Function (PACF): is used to measure the degree of association between X(t) and X(t-p).

