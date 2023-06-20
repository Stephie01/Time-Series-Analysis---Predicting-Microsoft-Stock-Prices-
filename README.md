![image](https://github.com/Mugangasia/Time-Series-Analysis---Predicting-Microsoft-Stock-Prices-/assets/98708792/0a8e383e-e60a-489d-a9d3-424c892d24ea)

## Background Information

The stock market encompasses a series of markets and exchanges wherein the buying, selling, and issuance of publicly traded company shares occur. These financial activities are conducted through institutionalized formal exchanges or over-the-counter (OTC) marketplaces, which adhere to established regulations. Within a country or region, there may exist numerous stock trading venues that facilitate transactions involving stocks and various other types of securities.

## Problem Statement 
Misinformation and obsolete data in making analysis in the money markets across the world has been and continue to be a problem. The required information to make informed decision, at times becomes too technical for some players in the stock market industry despite the industry players craving for information to accurately make predictions. Our client, a an asset management firm, needs proper analysis on prices on Microsoft's Stock to make informed investment decisions and optimize their trading strategies as they carry out their operations as well as forecast for strategic directions and decisions.

# Objectives 
* ```Develop a predictive model:``` To Build a robust time series model to generate accurate predictions of Microsoft's future stock prices.

* ```Improve investment decision-making:``` To Provide reliable predictions to assist investors in making informed investment decisions, optimizing portfolio allocation, and managing risk.

* ```Optimize trading strategies:``` To Enable traders to enhance their trading strategies by incorporating the predicted stock prices into their decision-making processes.

* ```Provide actionable insights:``` Extract meaningful insights from the analysis of historical stock market data and communicate them effectively to stakeholders.

* ```Enhance decision support tools:``` To create user-friendly interfaces to facilitate easy access to predictions and insights

# Data Understanding

The dataset used in this project contains Microsoft stock market information from 01/01/2015 through 01/19/2021. It is acquired from Yahoo Finance and consists of several columns that provide valuable insights into the stock's performance and trading activity. The key columns in the dataset are as follows:

* ```Date:``` This column represents the date in the format yy-mm-dd, indicating the trading day for which the stock information is recorded.

* ```Open:``` The "Open" column denotes the price of Microsoft stock at the market open, reflecting the initial trading price for the day.

* ```High:``` The "High" column indicates the highest price reached by Microsoft stock during the trading day, capturing the peak value achieved.

* ```Low:``` The "Low" column represents the lowest price reached by Microsoft stock during the trading day, providing insight into the minimum value observed.

* ```Close:``` The "Close" column signifies the final price of Microsoft stock at the market close, reflecting the last traded price of the day.

* ```Volume:``` The "Volume" column denotes the number of shares traded for Microsoft stock on a given trading day, indicating the level of market activity.

* ```Adj Close:``` The 'Adj Close' column refers to the adjusted closing price of a stock. It is a modified version of the closing price that takes into account various factors such as dividends, stock splits, and other corporate actions

By analyzing this dataset, we can gain a comprehensive understanding of Microsoft's stock market performance, including the opening and closing prices, the range of prices throughout the day (high and low), and the trading volume. These features are crucial for identifying patterns, trends, and factors that may influence the stock's price movements.

The dataset covers a significant time period, allowing for the exploration of long-term trends and capturing various market conditions. It provides a valuable resource for conducting time series analysis and developing predictive models to forecast future stock prices.

# Sucess Metrics 

* ```Prediction Accuracy:``` The model's ability to accurately forecast Microsoft stock prices will be assessed using appropriate statistical measures such as mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE). The lower these values, the higher the prediction accuracy.
* ```Stability and Robustness:``` The model should demonstrate stability and robustness by consistently providing accurate predictions across different time periods, including both normal and volatile market conditions.
* ```Insights and Interpretability:``` The project's success also lies in the generation of meaningful insights and interpretations regarding the factors influencing 
* ```Microsoft's stock prices.```` The ability to identify key patterns and relationships can contribute to a better understanding of the stock market dynamics and aid decision-making processes.
