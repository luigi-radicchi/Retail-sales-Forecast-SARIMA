# Retail sales Forecasting
## Project overview
This project explores weekly sales forecasting for retail stores using time series analysis techniques. The objective is to identify seasonal sales patterns, evaluate the impact of external economic factors, and build predictive models capable of forecasting future sales performance.

The project combines:

 - Exploratory Data Analysis (EDA)
 - Seasonal decomposition
 - Autocorrelation analysis
 - SARIMA forecasting
 - SARIMAX forecasting with external regressors
 - Forecast evaluation and model comparison
 - Future sales prediction

## Business problem
Retail demand is heavily influenced by seasonality and external economic conditions. Accurately forecasting sales allows organizations to:

 - Improve inventory planning
 - Optimize staffing levels
 - Anticipate seasonal demand peaks
 - Support strategic decision-making

This project investigates whether Walmart sales can be accurately forecasted using historical sales data and macroeconomic indicators.

## Dataset
The origin dataset contains weekly sales for many stores along with several external factors:
 - Weekly Sales
 - Fuel Price
 - Consumer Price Index (CPI)
 - Unemployment Rate
 - Holiday Flag

 The data covers approximately two and a half years of weekly observations.

## Data cleaning and validation
The origin dataset has been loaded from Kaggle.
<p align="center">
<img src="images/12_table_head.png" width="700">

These are the columns available after the astype check:
<p align="center">
<img src="images/13_info.png" width="400">

No null values have been found:
<p align="center">
<img src="images/14_null.png" width="400">

## Tools used
 - Pandas
 - NumPy
 - Matplotlib
 - Seaborn
 - pmdarima
 - Scikit-learn
