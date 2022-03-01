# Predict-the-temparature-in-delhi
Predict the temperature column ‘ _tempm’ for Delhi, using Time Series Forecasting
Predicting Time-series sata, using "Daily Climate time series data" dataset from Kaggle. The Dataset contains daily climate data in the city of delhi from 2013 to 2017. In this project to keep things simple I would only work with temprature to keep this a univariate time-series problem

The model is in Delhi_daily_temp.py and acc_plotter.py is a helper function.
The training data is available from Jan 1996 - Nov 2016. We will use data from Dec 2016 -
April 2017 to check the model accuracy/validity.
Model must take a date as input and output the probable temperature for that day (so basically
forecast to the given date and then report the value of that date)
