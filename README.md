# Multi-Factor Equity Model + Portfolio Construction Backtester

Systematic equity investing and portfolio construction framework for Nifty 500 stocks using 10 years of historical market and fundamental data.

## Factor Construction
Built and tested five equity factors from scratch:
- Value (P/B, EV/EBITDA)
- Momentum (12-1 month returns)
- Quality (ROE stability, accrual-based measures)
- Low Volatility (realized volatility)
- Size (market capitalization)

## Data Sources
- yfinance
- NSE Bhavcopy
- screener.in
- Tijori Finance
- BSE filings

## Strategy Framework
- Monthly stock scoring and ranking using composite factor scores
- Long-only and long-short quintile portfolio construction
- Monthly portfolio rebalancing
- Transaction cost modeling
- Backtesting framework designed to avoid lookahead bias

## Analysis
- Factor attribution against market beta
- Factor cyclicality analysis across market regimes
- Risk and performance metrics including Sharpe Ratio, Maximum Drawdown, and Information Ratio
- Fama-MacBeth cross-sectional regression to evaluate factor premia and statistical significance

## Tools
- Python
- pandas
- numpy
- statsmodels
- scikit-learn
- matplotlib
