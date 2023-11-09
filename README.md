# Trading Portfolios

This GitHub project houses three distinct Jupyter Notebooks, each presenting a unique simulated trading portfolio strategy. Explore each notebook for insights into various trading and investment approaches.

## Unsupervised Learning Trading Strategy

Welcome to the "Unsupervised Learning Trading Strategy" Jupyter Notebook project! This project explores the application of unsupervised learning techniques to create a trading strategy for the S&P 500 stock data. Key highlights include:

- **Data Collection:** The project starts with downloading historical S&P 500 stock data, including a comprehensive list of S&P 500 companies.
- **Data Preprocessing:** Data preprocessing involves calculating technical indicators, aggregating data to a monthly level, and filtering for the top 150 most liquid stocks.
- **Monthly Returns:** Monthly returns are computed for different time horizons, enhancing the dataset for further analysis.
- **Rolling Factor Betas:** The project incorporates Fama-French factors to calculate rolling factor betas, helping to understand stock exposure to common risks.
- **K-Means Clustering:** Unsupervised learning is applied with K-Means clustering to group similar stocks based on their characteristics.
- **Portfolio Optimization:** Stocks are selected based on the K-Means clusters, and portfolio optimization is performed to maximize the Sharpe ratio for each month.
- **Comparison to S&P 500:** The portfolio returns are compared to the returns of the S&P 500 to evaluate the strategy's performance.

Feel free to explore this project to gain insights into how unsupervised learning can be used to create a trading strategy and potentially outperform the S&P 500.

## Twitter Engagement Based Portfolio

Welcome to the "Twitter Engagement Based Portfolio" Jupyter Notebook project! This project focuses on creating a stock portfolio strategy based on Twitter engagement data. Key highlights of this project include:

- **Data Collection:** The project begins with the collection of Twitter engagement data, calculating the engagement ratio, and filtering out stocks with low activity on Twitter.
- **Monthly Average Engagement:** The average engagement for each stock is calculated on a monthly level, and stocks are ranked based on their engagement levels for each month.
- **Selecting Top 5 Most Engaged Stocks:** The top 5 most engaged-with stocks are selected for each month based on their rankings.
- **Forming Monthly Portfolios:** Portfolios are formed at the beginning of each month based on the stocks with the highest engagement, creating a dynamic and responsive investment strategy.
- **Download New Stock Prices:** New stock prices for the selected stocks are downloaded from Yahoo Finance.
- **Calculating Monthly Portfolio Returns:** The notebook calculates monthly portfolio returns, and the performance is compared to NASDAQ.

This project provides insights into how social media engagement data can be leveraged to build a portfolio strategy and potentially outperform stock indices like NASDAQ.

## Intraday Trading Strategy (GARCH Model)

Welcome to the "Intraday Trading Strategy (GARCH Model)" Jupyter Notebook project! This project focuses on an intraday trading strategy that leverages a GARCH model for volatility prediction. Key highlights include:

- **GARCH Model for Volatility Prediction:** The notebook defines a function to fit a GARCH model to daily data and predict the following day's volatility in a rolling window fashion.
- **Prediction Premium and Daily Signal:** It calculates the prediction premium and forms a daily signal based on the premium.
- **Intraday Signal:** The intraday dataset is merged with the daily signal, and intraday technical indicators are calculated to form an intraday signal.
- **Position Entry and Daily Returns:** Entry positions are generated based on the daily and intraday signals, and returns are calculated at the end of the trading day.

Explore this notebook to gain insights into creating an intraday trading strategy using a GARCH model.

Each of these notebooks presents a unique trading portfolio strategy, providing valuable insights into different aspects of trading and investment. Feel free to dive into the notebooks to explore these strategies in detail.
