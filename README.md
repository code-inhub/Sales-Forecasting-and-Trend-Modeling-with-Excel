# FORECASTING USING VARIOUS FUNCTIONS


## FORECAST.LINEAR:

Purpose: Predicts future values using linear regression based on a given dataset. Best for datasets with a linear trend.
Use Case: Predicting sales, revenues, or costs over time without seasonality.
```python
=FORECAST.LINEAR(target_date, values, timeline)
```


## FORECAST.ETS (Exponential Smoothing):

Purpose: Suitable for time-series forecasting with seasonality. It uses exponential smoothing to account for trends and seasonality in data.
Use Case: Predicting seasonal sales, demand, or other metrics with recurring patterns.
```python
=FORECAST.ETS(target_date, values, timeline)
```

## Line Chart:
Purpose: Used to visualize trends over time, making it easier to see patterns and project future values.
How to Use It:
Created a line chart to plot historical data (e.g., sales, revenue, etc.).
Identified trends and potential outliers by observing the trajectory of the plotted data points.

![Solution image](https://github.com/LakshyaChauhan/Forecasting/blob/main/forecasting/assets/line_chart.png)

## Forecast Sheet:
Purpose: The Forecast Sheet tool in Excel generates a forecast based on historical data and displays it with confidence intervals.
How To Use It:
Automatically generated a forecast sheet from historical data, predicting future values with a visual display of the projected trend.
Used confidence intervals to quantify the uncertainty in the forecasted values, providing a comprehensive view of future possibilities.

![Solution image](https://github.com/LakshyaChauhan/Forecasting/blob/main/forecasting/assets/forecast_sheet.png)
