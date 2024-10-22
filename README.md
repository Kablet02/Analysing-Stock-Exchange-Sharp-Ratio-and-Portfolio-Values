 Stock Exchange Analysis: Sharpe Ratio and Portfolio Values

This repository focuses on analyzing stock exchange data to evaluate portfolio performance using key metrics such as the **Sharpe Ratio**. The project demonstrates how to assess risk-adjusted returns and visualize portfolio values over time.

Project Overview

The goal of this project is to:

- Analyze historical stock prices
- Calculate portfolio returns and volatility
- Compute the Sharpe Ratio for evaluating risk-adjusted returns
- Visualize portfolio values and compare different asset allocations
 Key Concepts

1. Sharpe Ratio
   The **Sharpe Ratio** is a measure of risk-adjusted return, defined as:
   \[
   \text{Sharpe Ratio} = \frac{R_p - R_f}{\sigma_p}
   \]
   Where:
   - \( R_p \) is the expected portfolio return
   - \( R_f \) is the risk-free rate
   - \( \sigma_p \) is the portfolio standard deviation (risk)

   A higher Sharpe Ratio indicates better risk-adjusted performance.

2. Portfolio Values
   - Historical portfolio values are tracked based on stock price movements and asset allocations.
   - Comparison of different portfolio strategies such as equal-weighted vs. market-weighted allocations.
Process

 1. Data Collection
   - Historical stock prices are collected using APIs such as Yahoo Finance or Alpha Vantage.
   - Adjusted closing prices are used for accurate portfolio valuation.

2. Portfolio Construction
   - Create a portfolio of stocks with specified weight allocations.
   - Calculate daily portfolio returns based on stock price changes and weights.

3. Sharpe Ratio Calculation
   - Calculate daily and cumulative returns for the portfolio.
   - Compute the portfolio's standard deviation and the Sharpe Ratio to evaluate risk-adjusted returns.

 4. Visualize Portfolio Performance
   - Plot portfolio value trends over time to assess growth.
   - Compare portfolios with different allocations or risk levels.

Requirements

To run the analysis, you'll need the following Python packages:

- `pandas`
- `numpy`
- `matplotlib`
- `yfinance` (for fetching stock data)
- `scipy` (for statistical calculations)

Install the dependencies with:

```bash
pip install pandas numpy matplotlib yfinance scipy
