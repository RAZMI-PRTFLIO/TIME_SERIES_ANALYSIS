# 📈 Simple Time Series Analysis

This repository contains a Jupyter Notebook for performing **time series analysis** on Bitcoin historical price data. The project demonstrates essential techniques for exploring, visualizing, and decomposing time series data using Python.

🚀 Features

* Load and preprocess Bitcoin price data from CSV
* Time series indexing and resampling (daily, weekly, monthly, quarterly, yearly)
* Exploratory data analysis with summary statistics
* Data visualization using **Matplotlib** and **Plotly** (interactive charts)
* Seasonal decomposition (trend, seasonality, residuals)
* Autocorrelation and Partial Autocorrelation (ACF/PACF) plots
* Insights into market patterns and anomalies

🛠️ Technologies Used

Python 3.x**
Pandas** – data manipulation
Matplotlib** – static visualization
Plotly** – interactive visualization
Statsmodels** – time series decomposition & statistical analysis

📂 Project Structure

```
├── SIMPLE_TIME_SERIES_ANALYSIS.ipynb   # Main Jupyter Notebook
├── bitcoin_price.csv                   # Dataset (Bitcoin historical prices)
└── README.md                           # Project documentation
```

📊 Dataset

The dataset (`bitcoin_price.csv`) contains daily historical price data for Bitcoin, including:

* `Date` – trading date
* `Open` – price at the beginning of the day
* `High` – highest price of the day
* `Low` – lowest price of the day
* `Close` – price at the end of the day
* `Adj Close` – adjusted closing price
* `Volume` – total trading volume


## 📈 Example Visualizations

* Bitcoin closing price trends
* Seasonal decomposition plots (trend, seasonality, residuals)
* Autocorrelation (ACF) and Partial Autocorrelation (PACF)
* Interactive price charts with **Plotly**

---

## 🔮 Future Improvements

* Add forecasting models (ARIMA, SARIMA, Prophet, etc.)
* Automate EDA with reusable functions
* Extend analysis to multiple cryptocurrencies


