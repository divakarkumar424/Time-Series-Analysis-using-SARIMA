### Time-Series-Analysis-using-SARIMA (Seasonal Autoregressive Integrated Moving Average)
----
SARIMA which is an extension of the ARIMA model with the seasonal components. The SARIMA mostly applied to seasonal time series. If there is seasonality visible in the dataset then it is a better model given series using SARIMA (Seasonal ARIMA). In the ARIMA model, we are not using any seasonal information, only using part of the series which definitely results in poor predictions.

The SARIMA model addition to ARIMA includes seasonal parameters where we have to specify the seasonality of data. We think of it as two separate ARIMA models, one dealing with non-seasonal data and one dealing with seasonal data.

So in this section, our task is to model given seasonal time series data using SARIMA, for that we are using a dataset for a famous chair manufacturing company. The dataset holds the information on monthly sales for 10 years.
