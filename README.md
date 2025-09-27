# Portfolio-Optimization - MA544; Final Project

This project applies **Modern Portfolio Theory (MPT)** to optimize asset allocation using stocks:
- Goldman Sachs (GS)
- BlackRock (BLK)
- Apple (AAPL)
- Microsoft (MSFT)
- Amazon (AMZN)

## 🚀 Features
- Data collection (Yahoo Finance or synthetic dataset fallback)
- Risk-return metrics (annualized returns, volatility, Sharpe Ratio)
- Monte Carlo simulation of 5000+ portfolios
- Optimal portfolios (Max Sharpe, Min Volatility)
- Value at Risk (VaR) & Conditional VaR
- Backtesting and rolling risk analysis
- Correlation heatmap & allocation pie chart
- Results exported as CSVs

## 📂 Files
- `portfolio_optimization.ipynb`: main notebook
- `stock_data.csv`: dataset
- `portfolio_summary.csv`: portfolio metrics
- `optimal_sharpe_weights.csv`: Max Sharpe allocation
- `optimal_volatility_weights.csv`: Min Vol allocation
