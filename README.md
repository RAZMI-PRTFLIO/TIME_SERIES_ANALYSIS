

---

# 📈 Simple Time Series Analysis

This repository contains a beginner-friendly introduction to **time series analysis** using Python. The notebook demonstrates data exploration, transformation, visualization, and seasonal decomposition techniques on real-world datasets such as **Bitcoin daily prices** and **monthly chocolate revenue**.

## 🚀 Features

* Load and prepare time series data (`pandas`)
* Resampling to different frequencies (daily, weekly, monthly, yearly)
* Rolling statistics (7-day and 30-day moving averages)
* Data cleaning (handling missing values, interpolation, filling methods)
* Feature engineering (lagged values, time-based features like year, month, weekday, weekend flags)
* Visualization:

  * Daily and rolling plots
  * Volume and price correlation
  * Monthly and quarterly seasonality plots
  * Autocorrelation (ACF/PACF) analysis
* Seasonal decomposition (trend, seasonality, residuals) with `statsmodels`

## 🗂️ Datasets

1. **Bitcoin Price Data (`bitcoin_price.csv`)**

   * Columns: `Date, Open, High, Low, Close, Adj Close, Volume`
   * Date range: 2014 – 2023

2. **Chocolate Monthly Revenue (`choco_monthly_revenue.csv`)**

   * Columns: `Date, Revenue`
   * Used for monthly seasonality and decomposition examples.

*(Note: Datasets should be placed in the working directory or mounted Google Drive path when running in Google Colab.)*

## 📚 Libraries Used

* [pandas](https://pandas.pydata.org/) – data manipulation
* [matplotlib](https://matplotlib.org/) – visualization
* [statsmodels](https://www.statsmodels.org/) – seasonal plots, decomposition, autocorrelation

## ▶️ Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/simple-time-series-analysis.git
   cd simple-time-series-analysis
   ```

2. Open the notebook in **Google Colab** or **Jupyter Notebook**.

3. Run the analysis step by step to explore:

   * Trends
   * Seasonality
   * Rolling averages
   * Autocorrelation

## 📊 Example Visualizations

* Daily Closing Price of Bitcoin
* Rolling averages (7-day, 30-day)
* Yearly trading volume trends
* Monthly and quarterly seasonal plots
* Seasonal decomposition into trend, seasonality, and residuals

## 🛠️ Next Steps

This repo can serve as a foundation for:

* Building predictive models (ARIMA, SARIMA, Prophet)
* Forecasting financial time series
* Exploring seasonality in retail/sales data

---
