## Project: Time Series Analysis

### Overview
Analysis of time series data, visualizing patterns and modeling data for prediction.

### Some Details
These notebooks explore time series datasets. 

In *noaa-weather-maxtemp-SARIMA.ipynb*...

>I use the daily maximum temperatures from Sacramento, CA to look at seasonal patterns and trends. Downsampling the daily data to a weekly average maximum temperature, I show the seasonal variations from year to year with line plots and a heatmap. To model the data and make predictions, I fit a seasonal ARIMA, testing for stationarity and checking for correlations. I fit a few different SARIMAs, calculating the error of the predictions agaonst the test data to gauge improvement in the forecasting. 


### Language
Python

### Packages Used
statsmodels, matplotlib, seaborn

### Models
seasonal ARIMA/SARIMA

### Resources

[NOAA climate data](https://www.ncdc.noaa.gov/cdo-web/search)

