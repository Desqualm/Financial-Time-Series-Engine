# Financial Time Series Engine: ARIMA, Prophet & VAR Models

## Project Overview
This repository focuses on advanced time series analysis and forecasting. It covers a wide range of scenarios, from univariate sales forecasting to multivariate stock market correlation analysis. The primary goal is to apply rigorous statistical methods to identify trends, seasonality, and interdependencies in temporal data.

## Key Projects & Notebooks

### 1. Multivariate Stock Analysis (VAR Model)
* **File:** `szeregi_czasowe_multi.ipynb`
* **Goal:** Analyzing and forecasting stock prices for tech giants (AAPL, GOOG, MSFT, NFLX).
* **Key Techniques:** * **Vector Autoregression (VAR):** Modeling interdependencies between multiple time series.
    * **Augmented Dickey-Fuller (ADF) Test:** Checking for stationarity before modeling.
    * **Granger Causality:** (Optional/Inherent in VAR) understanding how one stock influences another.

### 2. Retail Sales Forecasting (ARIMA vs. Prophet)
* **File:** `prognoza_szeregow_czasowych.ipynb`
* **Goal:** Predicting furniture sales for a "Superstore" dataset.
* **Key Techniques:**
    * **ARIMA:** Fine-tuning parameters (p, d, q) for classical statistical forecasting.
    * **Facebook Prophet:** Utilizing additive models for business-cycle forecasting with holidays and seasonality.
    * **Model Comparison:** Evaluating MSE/RMSE to choose the best-performing engine.

### 3. Classic Trend Analysis
* **File:** `szeregi_czasowe.ipynb`
* **Goal:** Baseline time series analysis using the classic Air Passengers dataset.
* **Key Techniques:** Seasonal decomposition (Trend, Seasonality, Residuals).

---

## Methodology
To maintain high engineering standards, every analysis follows a strict pipeline:
1.  **Exploratory Data Analysis (EDA):** Visualizing time-dependent patterns.
2.  **Stationarity Check:** Using the **ADF Test** and applying differencing/log-transformations where necessary.
3.  **Feature Engineering:** Lagging variables and creating date-based features.
4.  **Model Validation:** Using walk-forward validation or train-test splits suitable for time-series data.

---

## 💻 Tech Stack
* **Language:** Python 3.x
* **Libraries:** `statsmodels` (ARIMA, VAR, ADF), `prophet`, `pandas`, `numpy`, `matplotlib`, `seaborn`.

---

