This Shiny app is dedicated to visualizing as well as forecasting the COVID data. 

## Characterestics of the Shiny app

- The app lets you choose a range for the date and region of interest, and view the number of confirmed cases or deaths. 

- Enables you to view the 7-day moving average for the selected data.

- Visualize the data as the total number of selected cases (confirmed/deaths) upto the selected date or the increase in the number of selected cases on that particular date.

- Forecasts the occurrence of confirmed cases/deaths for the next 28 days based on the data from 01/25/202 until the present. The user has the freedom to choose the type of model to use for forecasting.

#### More on the forecast

- The models chosen for forecast are Support Vector Machine, ARIMA, and polynomial regression of order 4.

- Forecast is available for both the daily increase in the number of cases as well as the cumulative number of cases.

- This forecast is done on the 7-day moving average data.
