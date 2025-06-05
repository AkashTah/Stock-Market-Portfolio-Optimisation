# 📈 Stock Market Analysis and Portfolio Optimization

This project explores the performance of selected Indian stocks using historical data and applies portfolio optimization techniques to identify the most efficient allocation strategy. The goal is to combine data analysis and financial metrics to build a portfolio that offers the best trade-off between return and risk.

---

## 🗂️ Project Overview

The repository is structured into modular scripts for data collection, visualization, analysis, and optimization. Each script serves a specific purpose in the portfolio building pipeline:

- `data_collection.py` – Fetches and cleans historical price data using the `yfinance` API  
- `visualization.py` – Generates visual insights such as stock price trends, moving averages, volumes, and return distributions  
- `analysis.py` – Computes daily returns, correlation matrices, expected returns, and volatilities  
- `optimization.py` – Simulates multiple portfolios, calculates Sharpe Ratios, and selects the optimal asset allocation  

---

## 📊 Data Summary

- Collected stock data for: **Reliance**, **TCS**, **Infosys**, and **HDFC Bank**  
- Data was reshaped and cleaned for further analysis and visualization

---

## 📉 Visualizations

- **Price Trends** – Line plots of adjusted close prices  
- **Moving Averages** – 50-day and 200-day trend overlays  
- **Volume Charts** – Daily trading volume bar graphs  
- **Return Distributions** – Histograms with KDE plots for daily returns

---

## 📈 Statistical Analysis

- **Daily Returns** – Computed to understand volatility  
- **Correlation Matrix** – Heatmap to evaluate relationships between asset returns  
- **Expected Return & Volatility** – Estimated using historical performance

---

## 🧠 Portfolio Optimization

- Simulated over **10,000** portfolios with random weight combinations  
- Used the **Sharpe Ratio** to identify the best return per unit of risk  
- Final portfolio allocation:
  - HDFC Bank: 22.97%  
  - Infosys: 29.13%  
  - Reliance: 8.45%  
  - TCS: 39.45%

**Key Metrics:**
- Max Sharpe Return: 24.07%  
- Volatility: 15.85%  
- Sharpe Ratio: 1.52  

---

## ▶️ How to Run

Run the following scripts in order:

```bash
python data_collection.py  
python visualization.py  
python analysis.py  
python optimization.py  
