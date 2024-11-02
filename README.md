# Netflix vs Disney Stock Analysis

This project analyzes stock data for Netflix and Disney, covering various financial metrics and visualizations. Through this analysis, we aim to understand the trends, volatility, and overall performance of both companies over time.

## Project Overview

This notebook explores the stock prices of Netflix and Disney using time-series data. Key analyses include:
- Price trends over time
- Daily returns and cumulative returns
- Moving averages and volatility
- Correlation between Netflix and Disney stock prices
- Relationship between volume and stock price

By the end of this analysis, we aim to gain insights into the stock performance of these companies and their financial trends over recent years.

## Data

The project uses four datasets:
1. **Disney Stock Price**: `DIS_stock_price.csv`
2. **Netflix Stock Price**: `NFLX_stock_price.csv`
3. **Disney Stock Split**: `DIS_stock_split.csv`
4. **Netflix Stock Split**: `NFLX_stock_split.csv`

Each dataset includes:
- `Date`: The date of each stock price record
- `Close Price`: The closing price on that date
- `Volume`: The number of shares traded on that day

## Key Analyses

1. **Data Loading and Initial Exploration**: Load data, inspect basic information, and check for missing values.
   
2. **Daily Returns Calculation**: Calculate daily percentage returns for both stocks to measure day-to-day performance.

3. **Trend Visualization**: Plot the closing prices of Netflix and Disney over time to visualize overall trends.

4. **Moving Averages**: Calculate 30-day moving averages to smooth out fluctuations and observe long-term trends.

5. **Volatility Analysis**: Use a 30-day rolling window to compute stock price volatility, a metric that reflects risk.

6. **Cumulative Returns**: Calculate cumulative returns for both stocks, providing insight into the total returns over time.

7. **Correlation Analysis**: Examine the correlation between Disney's and Netflix's stock prices to assess how closely they move together.

8. **Volume and Price Relationship**: Calculate correlations between trading volume and stock price, offering insights into trading behavior.

9. **Annual and Quarterly Averages**: Compute average close prices by year and quarter for a segmented time analysis.

## Requirements

To run this notebook, you need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `warnings`

## Installation

You can install the required libraries using:
```bash
pip install pandas numpy matplotlib seaborn
```

## How to Use

1. Load the notebook and run each cell sequentially.
2. Explore the visualizations and analysis to gain insights into the stock price trends and relationships.
3. Modify or extend the analysis to include other metrics or visualizations as desired.

## Insights

Key takeaways from this analysis include:
- **Price Trends**: Netflix and Disney have distinct price trends, reflecting their individual growth patterns.
- **Volatility**: Netflix generally shows higher volatility, potentially due to its tech sector classification.
- **Correlation**: The correlation between Netflix and Disney stock prices provides insight into their relationship within the stock market.
