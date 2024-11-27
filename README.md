# dominos_project
Dataset Overview and Cleaning:

Load the sales and ingredients datasets and review the structure and summary statistics.
Handle missing data by using interpolation for numerical columns (e.g., total_price).
For categorical columns with missing data (e.g., pizza_name_id, pizza_ingredients), fill them based on matching reference columns.
Identify and remove duplicate rows.
Date and Time Feature Engineering:

Parse the order_date and order_time columns and extract additional features like order_hour, day_of_week, Month, season, and time_of_day.
Create a function to categorize time of day and determine the season based on the month.
Exploratory Data Analysis (EDA):

Visualize the distribution of categorical columns (pizza_id, pizza_name_id, etc.) using count plots, and perform a detailed analysis on the uniqueness and skewness of each variable.
For numerical columns (quantity, unit_price, total_price), create histograms to analyze their distributions and check for skewness.
Plot and analyze the correlation matrix for numerical columns, and identify highly correlated variables.
Time Series Analysis:

Plot sales over time to identify trends, peaks, and seasonality.
Analyze monthly sales trends and sales patterns by the hour of the day.
Visualize the heatmap of average sales by the hour and day of the week to understand optimal times for promotions or staffing.
Seasonality and Trend Analysis:

Group sales by season and analyze how seasonal changes impact the total sales.
Visualize the distribution of sales across seasons and discuss the presence or absence of strong seasonal patterns.
Forecasting Models:

Prophet Model: Use Facebook's Prophet for forecasting with time-series data. Split the data, fit the model, and predict future values.
After that taking into consideration of Prophet model calculated the ingredients for one week and calculated total ingredients value
