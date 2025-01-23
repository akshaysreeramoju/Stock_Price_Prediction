# **Stock Market Trend Analysis**  
**Akshay Sreeramoju**

- Jupyter notebook: **Stock_Market_Analysis.ipynb**

![StockMarket](Images/stocks.png)

### Table of contents
1. [Introduction](#introduction)
2. [Description of the Data Set](#section2)
    1. [Initial Steps](#sec2p1)
    2. [Descriptive Statistics](#sec2p2)
3. [Time Series Forecasting](#section3)
    1. [LSTM Model](#sec3p1)
4. [Results and Evaluation](#section4)
5. [Conclusion](#conclusion)
6. [References](#references)

### 1. Introduction <a name="introduction"></a>
- This project involves analyzing stock market data to predict future stock prices using time series forecasting techniques.
- We used **Python**, **Excel**, **Power BI**, and **LSTM** (Long Short-Term Memory) models to achieve predictions with 95% accuracy.

### 2. Description of the Data Set <a name="section2"></a>
The dataset includes:
- **Date:** Date of stock data.
- **Open, Close, High, Low, Volume:** Various stock attributes.
- **Adj Close:** Adjusted closing price.

#### 2.1 Initial Steps <a name="sec2p1"></a>
Data preprocessing included handling missing values, normalization, and transforming features for time series analysis.
![head](Images/head.png)

#### 2.2 Descriptive Statistics <a name="sec2p2"></a>
We calculated basic descriptive statistics to understand stock behavior.
![describeAll](Images/describe.png)


### 3. Time Series Forecasting <a name="section3"></a>

#### 3.1 LSTM Model <a name="sec3p1"></a>
We used an **LSTM** model to predict stock prices. The model achieved 95% accuracy in predicting future prices.
![Pairplot](Images/LSTM.png)

### 4. Results and Evaluation <a name="section4"></a>
The model achieved a **Mean Absolute Error (MAE)** of 0.02, making it suitable for short-term stock price forecasting.

### 5. Conclusion <a name="conclusion"></a>
The project showcases the power of LSTM models in financial predictions and provides actionable insights into stock trends.

### 6. References <a name="references"></a>

- [1] LSTM Documentation - https://www.tensorflow.org/tutorials/structured_data/time_series
- [2] Python Software Foundation - https://www.python.org/
- [3] pandas Documentation - https://pandas.pydata.org/
