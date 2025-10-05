# Forecasting Net Sales Amount of SITD using Time Series Models # 
# Overview
This project focuses on forecasting the Net Sales Amount of SITD using historical transactional data. By applying time series models, the analysis aims to uncover underlying patterns, learn from past sales behavior, and generate accurate short-term forecasts that help the company manage liquidity and reduce risk from market fluctuations.
# Objective:
To apply various time series models, including ARIMA, SARIMA, ARCH, and GARCH to analyze sales trends and volatility, thereby providing data-driven insights that support short-term financial planning and operational decision-making.
# Methodology
- Data preprocessing: Cleaning and structuring daily sales data for multi-year analysis.
- Model implementation: Building and evaluating ARIMA, SARIMA, ARCH, and GARCH models.
- Model evaluation: Comparing forecast accuracy using metrics such as MAPE and RMSE.
- Volatility analysis: Using GARCH to interpret and quantify fluctuations in sales data.
# Key Findings
- ARIMA(3,0,2) achieved the highest forecast accuracy with the lowest MAPE, closely matching the actual sales trend.
**## Visualization Example
![Sales Forecast](images/sales_forecast_plot.png)
**
- GARCH(1,1) effectively captured risk and volatility patterns, identifying periods of potential instability.
- Classical autoregressive models performed best for trend-dominated, non-seasonal datasets.
# Outcome
The project produced accurate short-term sales forecasts and volatility insights, supporting liquidity management, business planning, and risk reduction against unexpected fluctuations.
# Tools and Technologies
- Python (pandas, numpy, statsmodels, arch, matplotlib)
- Jupyter Notebook
- Time Series Forecasting Techniques
