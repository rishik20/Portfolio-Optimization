# Portfolio Optimization - Indian Stocks

## 📊 Project Overview
This project implements **Modern Portfolio Theory (MPT)** to optimize a 5-stock Indian equity portfolio, maximizing risk-adjusted returns through mean-variance optimization. The optimized portfolio achieved **14.6% expected annual return** with a **Sharpe ratio of 0.32**, outperforming the NIFTY50 benchmark.

## 🎯 Key Features
- Fetches real-time stock data using Yahoo Finance API (yfinance)
- Calculates expected returns, volatility, and covariance matrix
- Implements Efficient Frontier analysis with Monte Carlo simulation (10,000+ portfolios)
- Optimizes portfolio for maximum Sharpe ratio (0.32 achieved)
- Compares performance against NIFTY50 benchmark (+1.3% outperformance)
- Generates interactive Plotly visualizations
- Provides discrete allocation for ₹1,00,000 portfolio

## 📈 Stocks Analyzed
| Symbol | Company | Optimal Weight |
|--------|---------|----------------|
| RELIANCE.NS | Reliance Industries | 71.3% |
| INFY.NS | Infosys | 28.7% |
| TCS.NS | Tata Consultancy Services | 0% |
| HDFCBANK.NS | HDFC Bank | 0% |
| ITC.NS | ITC Limited | 0% |

## 📊 Performance Results
| Metric | Optimized Portfolio | NIFTY50 Benchmark |
|--------|---------------------|-------------------|
| Expected Annual Return | 14.57% | 13.25% |
| Annual Volatility | 23.55% | 20.81% |
| Sharpe Ratio | 0.32 | 0.30 |
| Outperformance | +1.32% | - |

## 💰 Sample Portfolio Allocation (₹1,00,000)
- **RELIANCE.NS**: ~₹71,300 (based on optimal weights)
- **INFY.NS**: ~₹28,700
- **Remaining**: Kept as cash or rebalanced periodically

## 🛠️ Technologies Used
- **Python 3.10+**
- **Data Analysis**: pandas, numpy
- **Data Source**: yfinance
- **Optimization**: PyPortfolioOpt, scipy
- **Visualization**: matplotlib, plotly
- **Environment**: Google Colab / Jupyter Notebook

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/rishik20/Portfolio-Optimization.git
   cd Portfolio-Optimization
