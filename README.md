# Candlestick-Pattern-Trading-Bot

A Python-based trading bot that detects candlestick patterns like Bullish Engulfing, Bearish Engulfing, Hammer, Shooting Star, and more. The bot generates actionable "Buy" and "Sell" signals based on trend and volume validation.

---

## **Features**
- Detects multiple candlestick patterns, including:
  - **Bullish and Bearish Engulfing**
  - **Hammer and Shooting Star**
  - **Morning Star and Evening Star**
  - **Flag Patterns (Bullish & Bearish)**
  - **Doji, Spinning Top, and more**
- Validates signals using:
  - **20-day moving average** for trend confirmation.
  - **Volume above average** for volume confirmation.
- Plots **candlestick charts with buy/sell markers**.

---

## **Requirements**
Before running the bot, make sure you have the following installed:
- Python 3.x
- Required libraries: 
  - `pandas`, `numpy`, `yfinance`, `mplfinance`, `pandas-ta`

Install them using:
```bash
pip install -r requirements.txt
