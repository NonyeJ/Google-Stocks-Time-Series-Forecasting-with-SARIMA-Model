This is the Google-Stocks-Time-Series-Forecasting-with-SARIMA-Model.
Forecasting using series data with the Autoregressive Integrated Moving Average model. Using this model, we can analyze and model time-series data to make future decisions. 
Some of the applications of Time Series Forecasting are weather forecasting, sales forecasting, business forecasting, stock price forecasting, etc.

For this project, we used Google's stock price list from Yahoo finance. 
To ensure that our dataset is constantly accurate,since it's avery dynamic dataset; we usedan API from Yfinance.

It's super important to note, before using the ARIMA model, we have to figure out whether our data is stationary or seasonal. 
The data visualization graph about the closing stock prices above shows that our dataset is not stationary.


To check whether our dataset is stationary or seasonal properly,
We can use the seasonal decomposition method that splits the time series data into trend, seasonal, 
#and residuals for a better understanding of the time series data:

If we assume an additive decomposition, then we can write:
 yt=St+Tt+Rt
 
 Subsequently, we saw the the dataset is  not stationary,it is seasonal (after grap plot). Therefore, the SEASONAL-ARIMA is required.
This will be in 2 steps: a. Using the ARIMA model before b. Using the SARIMA model.

Finally, We have been able to predict the closing amount for the next one month!

Do let me know when you buy that stock:)!
