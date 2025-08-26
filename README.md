# Apple Hourly Stock Data Analysis

This project analyzes **Apple (AAPL) hourly stock prices** using financial time series techniques, including **returns calculation, autocorrelation analysis, and volatility modeling with GARCH**.

## 📊 Project Overview
- **Data Source:** [Alpha Vantage API](https://www.alphavantage.co/)  
- **Ticker:** AAPL  
- **Interval:** 1-hour (intraday)  
- **Output Size:** Full historical dataset  

The analysis covers:
1. Fetching stock price data using the Alpha Vantage API.  
2. Cleaning and preparing data with **pandas**.  
3. Computing stock **returns**.  
4. Visualizing autocorrelation & partial autocorrelation (ACF & PACF).  
5. Modeling volatility with **ARCH/GARCH models**.  

## 🛠️ Tools & Libraries
- Python 3  
- `pandas` – Data handling  
- `matplotlib` – Visualization  
- `statsmodels` – ACF/PACF plots  
- `arch` – GARCH modeling  
- `requests` – API calls  

## 📈 Key Insights
- Stock returns exhibit volatility clustering.  
- GARCH models are applied to capture time-varying volatility.  
- The project demonstrates **practical financial engineering techniques** for market data analysis.  

