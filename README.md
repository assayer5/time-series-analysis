## Project: Time Series Analysis

### Overview
Analysis of time series data, visualizing patterns and modeling data for prediction.

### Some Details
These notebooks explore time series datasets. 

In *noaa-weather-maxtemp-SARIMA.ipynb*...

>I use the daily maximum temperatures from Sacramento, CA to look at seasonal patterns and trends. Downsampling the daily data to a weekly average maximum temperature, I show the seasonal variations from year to year with line plots and a heatmap. To model the data and make predictions, I fit a seasonal ARIMA, testing for stationarity and checking for correlations. I fit a few different SARIMAs, calculating the error of the predictions agaonst the test data to gauge improvement in the forecasting. 

In *sp500_10yhist_analysis.ipynb*...

>I take a look at 10 years of price data for the S&P 500. I calculate the daily percent change and the 30-day moving average for later analysis. I explore a couple different ways to view patterns in volatility over time, and look for patterns in market lows and days with gains/losses. Later, I simulate 3 different investing strategies and compare the results of the strategies after a 5 year period.

### Language
Python

### Packages Used
statsmodels, pandas, matplotlib, seaborn

### Models
seasonal ARIMA/SARIMA

### Resources

[NOAA climate data](https://www.ncdc.noaa.gov/cdo-web/search)

