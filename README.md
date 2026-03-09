\# Monthly Realized Volatility Analysis for Stock Prices



\## Project Overview

This small project focuses on financial time series analysis, specifically calculating:

\- Daily logarithmic returns of stock prices (adjusted closing prices)

\- Monthly realized volatility based on daily returns

\- Annualized volatility conversion for cross-period comparison

\- Visualization of the relationship between stock price trends and volatility changes



The analysis is implemented in a Jupyter Notebook, making it easy to run step-by-step and visualize intermediate results.



\## Key Features

\- Data source: Yahoo Finance (via `yfinance` library)

\- Core metrics: Log returns, realized volatility (RV), annualized volatility

\- Visualization: Dual subplots comparing price trends and volatility

\- Data cleaning: Handling missing values, column renaming, and time-based grouping



\## Prerequisites

\### 1. Install Required Libraries

Run the following command in your terminal/command prompt to install dependencies:

```bash

pip install pandas numpy matplotlib yfinance jupyter

