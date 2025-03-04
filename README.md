# Stock Portfolio Tracker

A simple Python program to track the value of a stock portfolio using real-time stock prices from Yahoo Finance.

## Features

- Add stocks to your portfolio with the number of shares owned.
- Remove stocks from your portfolio.
- Calculate the current total value of the portfolio based on real-time stock prices.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-portfolio-tracker.git
Navigate to the project directory:

bash
cd stock-portfolio-tracker
Install required dependencies:

bash
pip install yfinance
Run the program:

bash
python portfolio_tracker.py
Usage
The StockPortfolio class allows you to manage your stock portfolio.
Use the add_stock(symbol, shares) method to add a stock and the number of shares you own.
Use the remove_stock(symbol, shares) method to remove stocks from your portfolio.
Use the get_portfolio_value() method to get the current total value of your portfolio based on the latest stock prices.
Example usage:

python

portfolio = StockPortfolio()
portfolio.add_stock("AAPL", 10)
portfolio.add_stock("GOOG", 5)
print("Portfolio Value: $", portfolio.get_portfolio_value())
Requirements
Python 3.x
yfinance library to fetch real-time stock data
Install dependencies with:

bash
pip install yfinance
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Stock data is fetched using the yfinance library.
php
