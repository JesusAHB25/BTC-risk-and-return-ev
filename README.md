# BTC-risk-and-return-ev

Financial time series analysis of historical Bitcoin (BTC) price data, demonstrating basic skills in data analysis, risk assessment, and quantitative strategy backtesting.

# Bitcoin Risk and Return Evaluation

## Project Overview

This project provides a comprehensive financial analysis of historical Bitcoin (BTC) price data. The core focus is to assess the asset's risk profile and then use those findings to design a trading strategy for managing capital in highly volatile markets.

## Objective
 
- **Quantify and Visualize Risk:** Analyze daily returns and 30 day volatility.
- **Identify Financial Flaws:** Use the Return Distribution Histogram to diagnose why traditional Wall Street risk models are unsuitable for crypto.
- **Develop Trading Logic:** Implement and backtest the 50 to 200 day Moving Average Crossover strategy.
- **Provide Actionable Critique:** Critically evaluate the strategy's performance, focusing on its vulnerability, and recommend necessary volatility filters for protection.

## Tools used

- **Python**: Core language for all calculations and analysis.
- **Pandas**: Data cleaning, financial transformations, and time series manipulation.
- **Seaborn & Matplotlib**: Data visualization of time series and statistical distributions.
- **PyCharm**: 

## Key Insights

- **Tail Risk is Severe:** The Return Distribution Histogram confirmed fat tails, meaning extreme daily losses/gains more frequently than standard finance models predict. This mandates specialized risk modeling.
- **Volatility Clustering:** High-risk periods tend to persist, suggesting risk budgeting should be dynamic, not fixed.
- **Strategy Vulnerability:** The 50 200 Moving Average Crossover is effective in strong trends but highly vulnerable to losses during non-trending markets.
- **Recommendation:** Any crypto trading strategy must be protected by filters based on the volatility metric to reduce exposure when the risk is spiking, making the analysis (Phase 2) the foundation for the strategy (Phase 3).
