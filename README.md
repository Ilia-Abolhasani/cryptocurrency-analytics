# Cryptocurrency Correlation

This project aims to calculate the correlation between cryptocurrencies and select coins with the maximum correlation distance. The selected coins can then be used in a smart-rebalance bot. The project utilizes historical data fetched from Binance using the ccxt library.

<img src="https://github.com/Ilia-Abolhasani/cryptocurrency-correlation/blob/main/sample.png?raw=true" alt="Sample Image" width="600" height="600">



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
2. Open the `Code.ipynb` Jupyter notebook file.
3. Set your Binance API keys in the notebook.
4. Run the notebook cells to fetch the cryptocurrency historical data and calculate the correlation.

### Fetching Cryptocurrency Historical Data

Before calculating the correlation, you need to fetch the historical data for the desired cryptocurrencies from Binance. In the Jupyter notebook, you will find code cells with instructions and examples on how to use the ccxt library to fetch the data.

Make sure to replace the placeholders with your Binance API keys to authenticate the requests.

### Calculating Correlation

Once you have fetched the historical data for the desired cryptocurrencies, proceed to the correlation calculation. The notebook provides code cells that demonstrate how to calculate the correlation between the different coins.

You can modify the code to select the specific coins you are interested in. The correlation calculation can be customized to suit your requirements.

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

Special thanks to Ilia Abolhasani for creating and sharing this project.

## Disclaimer

This project is for educational purposes only and should not be considered as financial or investment advice. Use at your own risk.
