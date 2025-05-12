# 📈 1-Year Stock Price Forecast Using Facebook Prophet

This project forecasts stock prices 1 year into the future using Facebook Prophet.  
It focuses on long-term investment insights for top US equities and the S&P 500 index.

## 🧠 Stocks Analyzed
- NVIDIA (NVDA)
- Apple (AAPL)
- Microsoft (MSFT)
- Google (GOOGL)
- Berkshire Hathaway (BRK-B)
- S&P 500 Index (^GSPC)

## 📊 Methodology
- Historical daily stock data collected using `yfinance`
- Forecasts built using Facebook Prophet (`prophet` library)
- Visualized and compared 1-year forecast to current price

## ✅ Results Summary

| Ticker | Current Price | 1-Year Forecast | Growth (%) | Recommendation |
|--------|----------------|------------------|-------------|----------------|
| NVDA   | 137.48         | 224.35           | 63.19%      | ✅ Strong Buy   |
| AAPL   | 251.92         | 273.31           | 8.49%       | ⚠️ Hold         |
| GOOGL  | 191.02         | 223.22           | 16.86%      | ✅ Strong Buy   |
| MSFT   | 423.98         | 535.20           | 26.23%      | ✅ Strong Buy   |

## 📁 Files Included
- `forecast_stocks.ipynb`: Jupyter notebook with full code
- `1_year_stock_forecast.csv`: Forecast result table
- `images/`: Forecast plots

## 📦 Libraries Used
- `prophet`
- `yfinance`
- `pandas`, `matplotlib`

---


