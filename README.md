# End-to-End Demand Forecasting System
An end-to-end time series demand forecasting project using Prophet, ARIMA, and baseline models with business insights.

## Project Overview
This project builds an end-to-end demand forecasting system using historical retail sales data.
The goal is to predict future product demand and support inventory and business planning decisions.

## Problem Statement
Retail businesses need accurate demand forecasts to:
- Avoid overstocking
- Prevent stock-outs
- Improve revenue planning

This project applies time-series forecasting techniques to solve this problem.

## Dataset
- Retail store-item daily sales data
- Multiple stores and multiple products
- Several years of historical data

## Approach
1. Data loading and cleaning
2. Exploratory Data Analysis (trend and seasonality)
3. Time series decomposition
4. Time-based train-test split
5. Model building:
   - Moving Average (Baseline)
   - ARIMA
   - Prophet
6. Model evaluation using MAE
7. Final model selection and business insights

## Models Compared
| Model                     | Performance |
|---------------------------|-------------|
| Baseline (Moving Average) |   Weak      |
| ARIMA                     |   Poor      |
| Prophet                   |   Best      |

## Final Output
- Accurate demand forecasts using Prophet
- Forecast visualizations
- Business insights for inventory planning

## Business Impact
The forecasting system can help businesses:
- Optimize inventory levels
- Improve demand planning
- Support data-driven decision-making

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels
- Prophet
- Scikit-learn

## Author
Abhishek Wankhede
