# timeSeries_temp_dataset_DMT
Data analysis on the daily temperature dataset.

About the dataset: The input .csv file consists of 6 columns, including date, minimum temperature, maximum temperature, average temperature, Sunrise, and sunset times in integer format (e.g., 657, i.e., 6:57 AM or 1756, as 5:56 PM) in 24-hour format.
The time series dataset spans the period from January 1, 2014, to December 30, 2018. Using pandas, we are going the predict the temperature for a subset of data using ARIMA.
ARIMA stands for Auto Regressive Integrated Moving Average, which is widely used for time series datasets. 
ARIMA is univariate, which means a single feature can be used at once. Here sunrise temperature is used for analysis. Further actual vs predicted values are plotted to find the errors. 
Let's begin to see how this works.!!!
