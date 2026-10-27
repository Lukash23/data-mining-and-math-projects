# Data Mining

## crypto_price_volatility_analysis.ipynb

Exploratory analysis of daily XRP/USD price data, completed individually.

**What it does**
- Loads the dataset with pandas and checks its shape and null values.
- Removes rows with missing data.
- Extracts open, high, low, close, volume and adjusted close series.
- Computes daily returns and an annualized volatility series.
- Plots price over time, volatility over time, and volatility against closing price.
- Sorts the data by date and plots the XRP/USD closing price.

**Tools:** Python, pandas, NumPy, Matplotlib, Seaborn

**Data:** `XRP.csv` is included in this folder. It was downloaded from Kaggle (the original link is no longer available) and has these columns: Date, Open, High, Low, Close, Adj Close, Volume.

**Running it**
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook crypto_price_volatility_analysis.ipynb
```
