# INR-USD-Exchange-Rate-Forecasting-using-ARIMA
1. Objective: To build a time series forecasting model that predicts the future INR/USD exchange rate using 15 years of daily data from the Reserve Bank of India (RBI),
employing the ARIMA methodology.

2. Data:
Source: Reserve Bank of India (https://rbi.org.in)
Frequency: Daily exchange rates (business days only)
Time Period: January 2009 – July 2025 (~15 years)

3. Steps Performed
Data Preparation: Imported daily INR/USD exchange rate
Handled missing values and set business-day frequency
Visualised trends over time
Stationarity Check (ADF Test): Augmented Dickey-Fuller (ADF) test applied
Chosen model: ARIMA(1,1,1)
Forecasting: Predicted next 30 business days
Visualised historical vs forecasted values

5. Visual: https://github.com/sugirtha-ge/INR-USD-Exchange-Rate-Forecasting-using-ARIMA/blob/main/inr_usd_forecast.png

