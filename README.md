# AlgoBulls_Python_Developer_Coding_Assignment
This repository contains code for fetching and analyzing US stock data using Alpha Vantage.

1. Fetching US Stock Data

Run the cells in the notebook to fetch intraday data for the desired US stock scripts using Alpha Vantage API.
The fetched data will be stored as it is.
Converting Fetched Data to Pandas DataFrame

2. Open the Jupyter Notebook convert_data.ipynb.

Run the cells in the notebook to convert the fetched data to a Pandas DataFrame with the required columns.
The converted DataFrame will be referred to as 'df' in the subsequent steps.

3. Computing Indicator Data

Run the cells in the notebook to compute the indicator data based on the 'close' column of 'df'.
The computed indicator data will be referred to as 'indicator_data' in the subsequent steps.

4. Strategy Analysis

Run the cells in the notebook to perform strategy analysis using the fetched data and computed indicator data.
The analysis includes generating 'signals' DataFrame based on the indicator and close data, and printing the rows with 'BUY' or 'SELL' signals.

5. Candlestick Chart

Run the cells in the notebook to plot a candlestick chart of 'df' and 'indicator_data' using the 'pyalgotrading' package.
