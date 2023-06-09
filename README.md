# Cryptocurrency Correlation

This project aims to provide users with powerful analytical tools for cryptocurrencies, including correlation analysis and volatility calculation. By utilizing historical data from Binance through the ccxt library, users can gain insights into the relationships between different cryptocurrencies and assess their price movements over time.

The correlation analysis feature allows users to quantify the statistical relationship between pairs of cryptocurrencies. This information is valuable for diversifying cryptocurrency portfolios and understanding potential dependencies among different assets. Moreover, the volatility calculation feature helps users assess the magnitude and frequency of price fluctuations for individual cryptocurrencies, providing them with an understanding of the potential risks and opportunities associated with different crypto assets.

The selected coins resulting from the correlation analysis and volatility calculation can be used in a smart-rebalance bot. This bot automatically adjusts the allocation of assets in a portfolio based on the chosen cryptocurrencies, aiming to maintain a desired risk-reward profile. By incorporating these analytical tools into the bot's decision-making process, users can optimize their portfolio management strategies and potentially enhance their investment outcomes.


## Installation

To use this project, you'll need to have Python 3.x installed. Clone the repository and navigate to the project directory:

```shell
git clone https://github.com/Ilia-Abolhasani/cryptocurrency-correlation.git
cd cryptocurrency-correlation
```

Next, install the required dependencies using pip:
```shell
pip install -r requirements.txt
```

## Usage

1. Ensure you have obtained API keys from Binance to access their data.
2. Open the Correlation.ipynb or Volatility.ipynb Jupyter notebook file.
3. Set your Binance API keys in the notebook (only if fetching more than 1000 rows of historical data).
4. Run the notebook cells to fetch the cryptocurrency historical data and calculate the correlation.

### Fetching Cryptocurrency Historical Data

Before calculating the correlation, you need to fetch the historical data for the desired cryptocurrencies from Binance. In the Jupyter notebook, you will find code cells with instructions and examples on how to use the ccxt library to fetch the data.

If you plan to fetch more than 1000 rows of historical data for cryptocurrencies, it is necessary to set your Binance API keys in the notebook. This will allow you to authenticate the requests and access the required data from the Binance exchange. However, if you are fetching a smaller amount of data, setting the API keys may not be necessary.

Please note that using API keys comes with certain responsibilities and risks. Make sure to follow Binance's API guidelines and keep your keys secure. It's essential to understand the terms and conditions of Binance's API usage and comply with any applicable regulations.

If you are unsure about the number of rows you need to fetch or have any questions regarding API key usage, please refer to Binance's documentation or seek appropriate guidance.

### Calculating Correlation
Once you have fetched the historical data for the desired cryptocurrencies, proceed to the correlation calculation. The notebook provides code cells that demonstrate how to calculate the correlation between different coins.

You can modify the code to select the specific coins you are interested in. The correlation calculation can be customized to suit your requirements.

### Calculating Volatility
In addition to correlation analysis, this project also includes the Volatility.ipynb Jupyter notebook file. This notebook calculates the percentage change per day and the Average True Range (ATR) for each crypto asset. This analysis helps identify the crypto asset with the maximum change per day.

Open the Volatility.ipynb notebook and run the cells to calculate the volatility metrics.

### Smart-Rebalance Bot

After obtaining the correlation values, you can use the selected coins with the maximum correlation distance in a smart-rebalance bot. The specific implementation of the bot is not included in this project but can be built based on the selected coins.

Ensure that you have a clear understanding of the smart-rebalance bot's mechanics and the associated risks before implementing it.

Note: It's essential to perform your due diligence and evaluate the results before making any financial decisions or executing any trading strategies.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

This project utilizes the following libraries:

- [ccxt](https://github.com/ccxt/ccxt) - A unified crypto trading API.
- [pandas](https://pandas.pydata.org/) - A powerful data analysis library for Python.
- [numpy](https://numpy.org/) - A fundamental package for scientific computing with Python.
- [matplotlib](https://matplotlib.org/) - A plotting library for creating visualizations in Python.
- [seaborn](https://seaborn.pydata.org/) - A data visualization library based on Matplotlib for enhancing visual aesthetics.

## Disclaimer

This project is for educational purposes only and should not be considered as financial or investment advice. Use at your own risk.



<img src="https://github.com/Ilia-Abolhasani/cryptocurrency-correlation/blob/main/sample.png?raw=true" alt="Sample Image" width="600" height="600">

<img src="https://github.com/Ilia-Abolhasani/cryptocurrency-correlation/blob/main/sample.png?raw=true" alt="Sample Image" width="600" height="600">

<img src="https://github.com/Ilia-Abolhasani/cryptocurrency-correlation/blob/main/sample.png?raw=true" alt="Sample Image" width="600" height="600">
