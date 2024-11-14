# Stock Analysis Project

### Overview

This project involved collecting and consolidating data, creating key metrics in order to assess the market conditions, volatility, evaluation of risk to make informed trading decisions. Data was pre-processed in Excel and Python along with calculating KPIs and Tableau was utilized for data visualization.


### Objectives
The primary objectives of this analysis are:
1. To visualize stock performance across multiple metrics and timeframes for individual and comparative analysis.
2. To calculate and display key financial metrics (KPIs) that aid in understanding stock trends, volatility and potential trading signals.

### Data Source & Preprocessing
- **Data Source**: Historical data for 50 different stocks stored in separate CSV files. The data included fields such as Date, Adj Close, Close, High, Low, Open, Volume, and Stock.
- **Data Aggregation**: Using Python, the individual csv files were merged into a single dataset, creating a structured file for analysis.
- **Data Cleaning and Transformation**:
   - **Python** was used to calculate daily metrics like **Daily Returns** and **Cumulative Returns**.
   - **Excel** was used to further prepare derived columns for technical indicators such as **20-day and 50-day Moving Averages**, **Gain**, **Loss**, **Volatality** and **Relative Strength Index (RSI)**.


### Key Performance Indicators (KPIs)
Folowing KPIs were calculated for dashboard and calculations.

- **Current Stock Price**: The latest closing price of the stock.
- **Daily Change (%)**: The daily percentage change to understand current market movement.
- **Year-to-Date (YTD) Return**: Cumulative return since the beginning of the year to show yearly growth.
- **Cumulative Return (Since Start Date)**: Total return since the earliest available data.
- **52-Week High/Low**: Highest and lowest closing prices in the past year.
- **20-Day Volatility**: Rolling standard deviation of daily returns indicating volatility level.
- **RSI**: RSI(Relative strength Index) value to indicate potential overbought or oversold conditions.
- **14-Day Average gain/Loss**: Average gains and losses through 14 day window.


### Visualizations

- **Stock Price Over Time** (*Line Chart*):
   - Displays the historical **Close** price for each stock.
   - Includes overlay for 50-day Moving Averages** to show trends.
   - We can efficiently identify long-term and short-term trends.

- **Cumulative Daily Returns Over Time** (*Line Chart)*:
   - Tracks the daily return from the earliest data point in percent.
   - This provides a visual of long-term growth or decline of the stock.

- **Trading Volume Over Time** *(Area Chart)*:
   - This area chart displays trading volume over time, with spikes indicating higher trading activity.
   - It helps to Identify time durations and periods of high buying or selling of stock.

![Stocks_chart_1](https://github.com/user-attachments/assets/56bf34e9-e088-445d-a7b6-26774897a5dc)

- **Price vs. Volume** *(Line and Bar Chart)*:
   - Dual-axis chart with **Close Price** as a line and **Volume** as bars.
   - It helps to undertand the correlation between price and volume changes.

- **Relative Strength Index (RSI)** *(Line Chart*):
   - Shows reference lines at **30** (oversold) and **70** (overbought).
   - It indicates potential buying and selling points based on RSI thresholds.


![Screenshot 2024-11-14 184406](https://github.com/user-attachments/assets/6729e655-4b8b-498a-9948-73b73bb34238)


- **Volatility** *(Rolling Standard Deviation)*:
   - Line chart showing 20-day volatility.
   - This helps to assess periods of high and low risk of security by tracking volatility fluctuations.
 
### Results and Insights
- The Stocks data Analysis provided a comprehensive view of each stock's performance, allowing me to quickly **assess** overall stock performance through various KPIs and metrics mentioned above.
- **Analyse Trends** and identify support and resistance levels using moving averages and historical price data.
- Risk assessement and Evaluation of **volatility** with distribution of daily returns, RSI, and volatility chart.
- **Understand trading opportunities** with RSI and volume indicators in order to identify potential buy and sell.
