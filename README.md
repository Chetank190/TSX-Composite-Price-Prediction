# TSX-Composite-Price-Prediction
Compared linear regression performace with ARIMA model for prediction the prices of TSX Composite Index.  

# Results  
ARIMA model has a RMSE of 90.67 which has better results than linear Regression with RMSE of 595.60 while forecasting our TSX Composite closing price.  

# Conclusion

In this study we have taken original time series data such as Open, Close, Low, High and Volume etc. of the TSX Composite Index using the quantmod package in R and used the linear and ARIMA model to select the best model for prediction. Decomposing time-series data can give us a more detailed view of the pattern of our data. We have seen repeated seasonal fluctuation of data. The closing price of the TSX composite Index tended to reach the highest in July and the lowest in December. From this decomposition, we may say that the right time to sell this stock was at the middle of the year (especially in July) and the right time to buy was at the end of the year (especially in December). Analyzing it will help us in making decisions about our data.  

