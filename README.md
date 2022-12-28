# Time-Series-Forecasting-Apple-Stock-Price
This project was created to analyse and forecast the stock price for product Apple using AR, MA, ARIMA and Second order exponential smoothing.  

Step 1: 
In this project we are extracting the data from yahoo finance and using closing price for forecasting the Apple stock.

Step 2:
Here we have converted the data from daily to weekly basis. for eg, here we are taking mean value of stock price from monday till friday to maintain the continuity.

Step 3:
1. In this step we will check whether data is stationary or not by using rolling mean, rolling std and ADF test.
2. Transforming the data from non-stationary to stationary. 

step 4:
Training the data using stationary and non-stationary data for identifying whether its working well with transformation or not.

Step 5:
Forecasting the data by trained model. 
