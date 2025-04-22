
# 📈 Stock Market Analysis and Prediction
## 📄 Project Details
- **Name:** POOJA A
- **Company:** CODTECH IT SOLUTIONS
- **ID:** CT12DS2550
- **Domain:** DATA ANALYTICS
- **Duration:** SEPTEMBER 25th, 2024 to NOVEMBER 25th, 2024

---

### 🚀 Overview
This project performs a comprehensive **time series analysis and prediction** on historical stock market data, focusing on analyzing trends, identifying patterns, and forecasting future stock prices. Using machine learning and statistical modeling techniques, specifically the **ARIMA model**, this project aims to predict stock prices for the next 30 days based on historical data.

### 🔍 Features
- **Data Collection**: Utilizes `yfinance` to pull historical stock data for various companies.
- **Exploratory Data Analysis (EDA)**:
  - Visualizes stock price trends over time 📅.
  - Generates correlation matrices to analyze relationships between variables 📈.
- **Data Preprocessing**:
  - Checks for stationarity using the Augmented Dickey-Fuller test.
  - Differentiates non-stationary data to prepare it for time series modeling.
- **Time Series Forecasting**:
  - Implements an ARIMA model to fit historical stock data.
  - Forecasts future stock prices for 30 days.
- **Evaluation and Visualization**:
  - Plots predicted vs. actual prices for comparison 📊.
  - Calculates **Mean Squared Error (MSE)** to assess model accuracy.

### 📚 Dependencies
- **Python Libraries**:
  - `yfinance`: For downloading historical stock data.
  - `pandas`, `numpy`: For data manipulation and analysis.
  - `matplotlib`, `seaborn`: For data visualization.
  - `statsmodels`: For statistical tests and ARIMA model.
  - `scikit-learn`: For model evaluation metrics.

### 📂 Project Structure
1. **Data Loading**: Pulls historical stock data using `yfinance`.
2. **Exploratory Data Analysis (EDA)**:
   - Visualizes stock prices over time.
   - Generates a heatmap to analyze feature correlations.
3. **Data Preprocessing**:
   - Tests for stationarity and applies differencing if needed.
4. **ARIMA Modeling**:
   - Fits an ARIMA model to the processed data.
   - Generates a 30-day forecast.
5. **Evaluation and Visualization**:
   - Compares predicted prices with actual prices.
   - Calculates and displays Mean Squared Error (MSE).

### 🛠 Usage
To run the project:
1. **Install Required Libraries**:
   ```bash
   pip install notebook pandas numpy matplotlib seaborn statsmodels scikit-learn yfinance
   # Stock Market Analysis and Prediction

## Overview
This project performs analysis and prediction on historical stock data.




