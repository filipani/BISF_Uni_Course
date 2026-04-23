# Business Intelligence for Financial Services - Laboratory Project (2026)

This repository contains the individual project for the **Business Intelligence for Financial Services** course (A.Y. 2025/2026) at the University of Milano-Bicocca.

## 📌 Project Overview
The project demonstrates proficiency in financial data analysis using Python, focusing on:
* Data acquisition and visualization.
* Exploratory analysis of time series and portfolios.
* Return forecasting and trading strategies.

## 📊 Data & Scope
The analysis covers a 10-year period: **March 31, 2016 – March 31, 2026**.
The dataset includes:
* **Assets:** [Insert your choice: 6 S&P 500 stocks across 3 sectors OR 6 Sectoral ETFs].
* **Benchmark:** S&P 500 Index (Yahoo Finance Ticker: `^GSPC`).
* **Sources:** Automated downloads from Yahoo! Finance and Fama-French database.

## 🛠️ Project Structure

1. **Exploratory Data Analysis & Descriptive Statistics**
   
   * Calculation of cumulative, annual compounded, simple, and logarithmic returns.
   * Distribution analysis using 3-section diagnostic plots (Histogram/KDE, Boxplot, QQ-plot).
   * Annualized univariate statistics (Mean, Volatility, Skewness, Kurtosis).
   * Correlation analysis and scatter plots to evaluate sector relationships and market linkage.

2. **Forecasting & Technical Analysis**
   
   * **ARIMA Modeling:** Time-series forecasting using 80 months for training, 30 months for testing, and a 10-month forecast horizon.
   * **Trading Strategy:** Implementation and backtesting of an algorithmic strategy compared against a **Buy & Hold** benchmark.

3. **Risk Models & Portfolio Construction**
   
   * **Asset Pricing:** Calculation of **Beta** via CAPM and exposure to **Fama-French** risk factors.
   * **Dynamic Strategies:** Backtesting of investment strategies including **Equal Weight, Stop Loss, and CPPI/TPPI**.
   * **Portfolio Optimization:** Construction of a **Mean-Variance Optimal Portfolio** using analytical and simulation methods.

## 💻 Technical Requirements
Developed in **Python (>= 3.8)** using the following core libraries:
* `Pandas` & `Numpy`: Data manipulation.
* `Matplotlib` & `Seaborn`: Visualization.
* `Scikit-Learn`: Machine Learning.
* `StatsModels`: Statistical modeling and ARIMA.
* `yfinance`: Financial data retrieval.
