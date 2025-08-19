# Exploring the Bitcoin Cryptocurrency Market

## Overview
This project aims to analyze the growth and impact of Bitcoin and other cryptocurrencies by exploring their market capitalization. Using data from the CoinMarketCap API, the project employs Python to perform data extraction, manipulation, visualization, and exploratory data analysis. The focus is on understanding market trends and volatility in the cryptocurrency space, with a particular emphasis on Bitcoin's dominance and the performance of other major cryptocurrencies.

## Dataset
The project uses data sourced from the CoinMarketCap API, which provides information on various cryptocurrencies, including:
- **Market Capitalization**: The total market value of a cryptocurrency (e.g., Bitcoin reached over $200 billion on December 6, 2017).
- **Audio Features**: Metrics such as 24-hour trading volume, price in USD and BTC, percentage change over 1 hour, 24 hours, and 7 days, total supply, and more.
- **Cryptocurrencies Covered**: Includes Bitcoin, Ethereum, Ripple, Bitcoin Cash, EOS, and others, with data on up to 100 coins from a single API call.

**Note**: The cryptocurrency market is highly volatile, and this project is for informational purposes only, not investment advice.

## Features
- **Data Extraction**: Pulling real-time cryptocurrency data using the CoinMarketCap API.
- **Data Manipulation**: Cleaning and filtering data using `pandas` to focus on relevant metrics like market capitalization and percentage changes.
- **Data Visualization**: Creating visualizations (e.g., bar plots) with `matplotlib` and `seaborn` to illustrate market capitalization and volatility trends.
- **Exploratory Data Analysis (EDA)**: Analyzing market trends, such as identifying cryptocurrencies with market caps above $10 billion and visualizing top gainers and losers.
- **Volatility Analysis**: Examining price fluctuations using metrics like 24-hour and 7-day percentage changes.
- **Feature Engineering**: Querying and categorizing cryptocurrencies (e.g., large-cap coins) to simplify analysis.

## Requirements
To run the notebook, you need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `requests` (for API calls)

Install the dependencies using:
```bash
pip install pandas numpy matplotlib seaborn requests
