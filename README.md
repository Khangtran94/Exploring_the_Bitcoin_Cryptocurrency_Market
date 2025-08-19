# Exploring the Bitcoin Cryptocurrency Market

## Overview
This project aims to analyze the growth and impact of Bitcoin and other cryptocurrencies by exploring their market capitalization. Using data from the CoinMarketCap API, the project employs Python to perform data extraction, manipulation, visualization, and exploratory data analysis. The focus is on understanding market trends and volatility in the cryptocurrency space, with a particular emphasis on Bitcoin's dominance and the performance of other major cryptocurrencies.

## Dataset
The project uses data sourced from the CoinMarketCap API, which provides information on various cryptocurrencies, including:
- **Market Capitalization**: The total market value of a cryptocurrency (e.g., Bitcoin reached over $200 billion on December 6, 2017).
- **Audio Features**: Metrics such as 24-hour trading volume, price in USD and BTC, percentage change over 1 hour, 24 hours, and 7 days, total supply, and more.
- **Cryptocurrencies Covered**: Includes Bitcoin, Ethereum, Ripple, Bitcoin Cash, EOS, and others, with data on up to 100 coins from a single API call.

**Note**: The cryptocurrency market is highly volatile, and this project is for informational purposes only, not investment advice.[](https://lkmh.github.io/Exploring-the-Bitcoin-cryptocurrency-market/)[](https://github.com/pandansh/Exploring-the-Bitcoin-Cryptocurrency-Market)

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
```

## Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Khangtran94/Exploring_the_Bitcoin_Cryptocurrency_Market.git
   cd Exploring_the_Bitcoin_Cryptocurrency_Market
   ```

2. **Obtain API Access**:
   - Sign up for a CoinMarketCap API key at [https://coinmarketcap.com/api/](https://coinmarketcap.com/api/).
   - Add your API key to the notebook or a configuration file as instructed.

3. **Run the Notebook**:
   - Open `Exploring_the_Bitcoin_Cryptocurrency_Market.ipynb` in Jupyter Notebook or a compatible environment.
   - Follow the steps to fetch data, process it, and generate visualizations.

4. **View Results**:
   - The notebook includes visualizations like bar plots of market capitalization and tables of large-cap cryptocurrencies (market cap > $10 billion).
   - Volatility analysis highlights significant price changes, such as extreme losses (e.g., FlappyCoin with -95.85% in 24 hours).[](https://github.com/pandansh/Exploring-the-Bitcoin-Cryptocurrency-Market)

## Results
The project provides insights into:
- **Bitcoin's Dominance**: Bitcoin's market capitalization significantly outpaces other cryptocurrencies, though competition is increasing.[](https://github.com/prouast/cryptocurrency-analysis)
- **Market Volatility**: Cryptocurrencies exhibit extreme price fluctuations, with some coins losing or gaining substantial value in short periods.[](https://github.com/pandansh/Exploring-the-Bitcoin-Cryptocurrency-Market)
- **Top Performers**: Identification of large-cap cryptocurrencies (e.g., Bitcoin, Ethereum, Bitcoin Cash, IOTA) and their market trends.[](https://github.com/rrmolin/Exploring-the-Bitcoin-Cryptocurrency-Market-DataCamp-project/blob/master/notebook.ipynb)

Visualizations include:
- Bar plots of top 10 cryptocurrencies by market capitalization with a logarithmic scale for clarity.
- Analysis of 24-hour and 7-day percentage changes to highlight volatility.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- CoinMarketCap for providing the API and dataset.
- DataCamp for inspiring the project structure and goals.
- The open-source community for tools like `pandas`, `matplotlib`, and `seaborn`.

## Disclaimer
The cryptocurrency market is exceptionally volatile, and any investments carry significant risk. This project is for educational purposes only and should not be considered financial advice. Always conduct your own research before investing.[](https://github.com/MrambaGadi/Exploring-the-Bitcoin-cryptocurrency-market)
