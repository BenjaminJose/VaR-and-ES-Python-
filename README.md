# Value at Risk (VaR) and Expected Shortfall (ES/CVaR) Analysis

# Project Overview
This project implements a Python-based model to calculate Value at Risk (VaR) and Expected Shortfall (ES/CVaR) for a portfolio of 8 Indian stocks. The analysis uses 10 years of historical data from the Yahoo Finance API, focusing on risk assessment over a 10-day time horizon at multiple confidence levels (90%, 95%, and 99%).

# Libraries Used
**pandas**: For data manipulation and analysis. <br />
**numpy**: For numerical operations.<br />
**matplotlib**: For data visualization.<br />
**yfinance**: To retrieve stock price data.<br />
**datetime**: To handle date-related operations.<br />

# Portfolio and Time Horizon
**Portfolio**: Consists of 8 equally weighted Indian stocks.<br />
**Time Period**: 10 years of daily stock prices.<br />
**Time Horizon for VaR/ES**: 10 days.<br />

# Stocks Included:
TATASTEEL.NS<br />
BPCL.NS<br />
NTPC.NS<br />
TCS.NS<br />
INFY.NS<br />
RELIANCE.NS<br />
KOTAKBANK.NS<br />
HDFCBANK.NS<br />
