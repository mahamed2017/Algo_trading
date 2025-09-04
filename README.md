# Algo_trading
# Multi-Asset Momentum Trading Project

## Overview
A **multi-asset trading strategy** using **Bollinger Bands** to generate buy/sell signals.  
The strategy is backtested on historical stock data for **AAPL, MSFT, AMZN and NVDA**, evaluating metrics such as **Sharpe ratio**, **max drawdown**, and **total return**.

---

## Features
- Fetch historical stock prices from **Yahoo Finance**  
- Calculate **Bollinger Bands** and generate trading signals  
- Backtest multi-asset portfolio with **equal allocation and transaction fees**  
- Compute portfolio metrics using **VectorBT**  
- Visualize **equity curve** and individual stock prices (static + interactive plots)  

---

## Dataset
- Daily closing prices from **2018-01-01** to **2025-01-01**  
- Tickers: `AAPL`, `MSFT`, `AMZN`,  `NVDA`

---

## Installation
```bash
pip install pandas numpy yfinance matplotlib plotly vectorbt
