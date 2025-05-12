# Stock Analysis: Forecasting & Portfolio Optimization

This project focuses on two main tasks:  
(1) **Forecasting stock prices** of four selected stocks for the first 10 trading days of 2025, and  
(2) **Solving two portfolio optimization problems** using historical data and predefined financial constraints.

## 📁 Project Structure

- `Analyze_stockprice.Rmd`: Time series analysis and 10-day price forecasting using ARIMA/ETS models.
- `Analyze_revenue.Rmd`: Basic financial performance metrics to support investment decisions.
- `G06.xlsx`: Contains historical stock prices and serves as the basis for optimization problems.
- `Stock_Analysis_Cointegration_vs_Optimization.ipynb`: Combines cointegration testing, VAR forecasting, and portfolio modeling.
- `README.md`: Project overview and documentation.

## 📌 Objectives

- Forecast closing prices of 4 selected stocks for the first 10 days of 2025 using statistical models.
- Solve two optimization problems:
  1. **Maximize expected return** with a given risk constraint.
  2. **Minimize risk (variance)** with a given target return.

## 🛠 Methods and Tools

- Time series forecasting with **ARIMA**, **Exponential Smoothing (ETS)**.
- Portfolio optimization using **Markowitz Mean-Variance framework**.
- Visualization and analysis via **R**.
- Excel-based solver for quick scenario testing.

## ✅ Outputs

- 10-day price forecasts for each stock.
- Efficient portfolio weights under different investment strategies.
- Risk-return trade-off visualized with frontier charts.
