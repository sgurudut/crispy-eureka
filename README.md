# crispy-eureka # prophet # time-series-analysis
Time Series Analysis using Prophet

Goal of this project uses JetRail data to forecast the traffic on JetRail for the next 7 months.

- Project used prophet for forecasting
- Root mean square log error (RMSLE) was the metric used for model performance
- Data was split into training and valid data sets.
- Forecasts were made and compared with the valid data set to achive RMSLE of 0.33
- Performed Hyperparameter tuning on the model using parameter grid.
- Achieved 83% improvement in performance and forecasted traffic for the next 7 months


Further steps:

- Forecast growth by using growth = 'logistic' in prophet while building model and then perform hyper parameter tuning
- Remove outliers and predict with prophet
- Implement automatic changepoint detection using Prophet
