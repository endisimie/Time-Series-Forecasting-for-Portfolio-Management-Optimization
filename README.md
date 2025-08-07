# Time Series Forecasting and Portfolio Optimization

This project demonstrates a complete financial analysis workflow, from data acquisition and preprocessing to advanced time series forecasting and portfolio optimization. It's built to guide users through the process of developing a data-driven investment strategy and backtesting its performance on historical data.

---

# Features 🌟

Data Preprocessing and EDA: Loads and cleans financial data for key assets (TSLA, BND, SPY), performs Exploratory Data Analysis (EDA), and checks for data stationarity.

Time Series Forecasting: Develops and compares both a statistical model (ARIMA) and a deep learning model (LSTM) to forecast future stock prices for Tesla (TSLA).

Portfolio Optimization: Utilizes Modern Portfolio Theory (MPT) to construct an optimal portfolio by combining a forecasted asset with historical data-driven assets.

Strategy Backtesting: Simulates the performance of the optimized portfolio against a simple benchmark to validate the strategy's viability.

---

## 📦 Assets Used

- **TSLA** – High-growth, high-risk equity
- **SPY** – Diversified US stock index ETF
- **BND** – Bond market ETF for stability

Data collected using the `yfinance` Python API from **July 1, 2015 to July 31, 2025**.

---

## 🛠️ Tasks Completed

### ✅ Data Preprocessing & EDA
- Extracted historical data from YFinance
- Cleaned missing data, normalized inputs
- Performed trend, seasonality, and volatility analysis
- Computed daily returns, rolling stats, Sharpe Ratio, and VaR

### ✅ Time Series Forecasting
- Implemented ARIMA model using `statsmodels` or `pmdarima`
- Trained LSTM model using `TensorFlow/Keras`
- Compared both models using MAE, RMSE, and MAPE

### ✅ Forecast Analysis
- Forecasted TSLA prices for the next 6–12 months
- Visualized forecasts and analyzed confidence intervals
- Identified patterns, trends, and investment risks

### ✅ Portfolio Optimization
- Calculated expected returns and covariance matrix
- Used PyPortfolioOpt to optimize asset allocation
- Generated Efficient Frontier
- Identified Min Volatility and Max Sharpe portfolios

### ✅ Strategy Backtesting
- Defined a benchmark (60% SPY / 40% BND)
- Simulated portfolio returns over 2024–2025
- Compared cumulative returns and Sharpe Ratios
- Evaluated strategy performance vs. benchmark

---

## 📊 Tools & Libraries

- Python 3.11
- pandas, numpy, matplotlib, seaborn
- yfinance
- statsmodels / pmdarima
- scikit-learn
- PyPortfolioOpt
- TensorFlow / Keras

---

## 🧪 Results Summary

| Metric       | ARIMA     | LSTM      |
|--------------|-----------|-----------|
| MAE          | [value]   | [value]   |
| RMSE         | [value]   | [value]   |
| MAPE         | [value]   | [value]   |

- **Recommended Portfolio Weights:**
  - TSLA: [x]%
  - SPY: [y]%
  - BND: [z]%
- **Expected Annual Return:** [value]%
- **Portfolio Sharpe Ratio:** [value]

---


## 🚀 How Run Locally

```bash
# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run scripts or open notebooks
