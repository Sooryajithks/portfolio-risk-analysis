# Stock Price Trend & Portfolio Risk Analysis

## Overview
This project analyzes historical stock price data for selected companies and evaluates portfolio risk metrics.  
Key tasks:
- Downloading stock price data using the `yfinance` API.
- Calculating daily returns and visualizing stock trends.
- Constructing a simple portfolio with user-defined weights.
- Computing key risk metrics: expected returns, volatility, and Sharpe ratio.
- Comparing portfolio performance against a market benchmark (S&P 500).

## Tools & Libraries
- Python 3
- Pandas
- NumPy
- Matplotlib
- yfinance (for stock data retrieval)

## Project Workflow
1. Select stock tickers (e.g., CBA, BHP, CSL).
2. Fetch historical data using `yfinance`.
3. Compute daily returns for each stock.
4. Construct a portfolio with weights (e.g., 40% CBA, 30% BHP, 30% CSL).
5. Calculate portfolio expected return, volatility, and Sharpe ratio.
6. Plot cumulative returns vs. benchmark.

## Results
- Visualized stock price trends over the last 1.5 years.
- Portfolio Sharpe ratio indicated risk-adjusted performance.
- Outperformed/underperformed S&P 500 depending on weighting.

## Description of matrices
1. Expected Return – The average return of the portfolio over time, representing how much an investor can expect to gain (or lose) on average.

2. Volatility – The standard deviation of returns, measuring the degree of fluctuation or risk. Higher volatility means greater uncertainty.

3. Sharpe Ratio – A risk-adjusted performance measure calculated as expected return divided by volatility. A higher Sharpe ratio indicates better return per unit of risk.


