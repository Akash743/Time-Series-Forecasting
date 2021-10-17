# Time-Series-Forecasting

Forecasting Alcohol slaes using different Time series models including Seasonal Autoregressive Moving Averages and deep learning models like LSTMS.

**Contents of the notebook:**

1. Checking for stationarity of data using Augmented Dickey-Fuller Test 

2. Standardizing the data for making that scale invariant

3. Generating sequences to be fed to LSTM model using TimeSeriesGenerator

4. Fitting the Train data and predciting for test data. 

5. Inverse Transforming the results and plotting them

6. Analyzing the performance using MSE and RMSE 

Now using other statistical models for the same.

7. Using Auto-correlation plot and analyzing it.

8. Using auto-arima to find the best model and sequence of parameters

9. Training the best models found, i.e. SARIMA(Seasonal Auto Regressive Moving Averages with order=(3,1,2) & seasonal_order=(2,1,2,12)

10. Predciting the results and visualizing them

11. Comparing the MSE and RMSE with results obtained using LSTM

12. PLotting for future time blocks




