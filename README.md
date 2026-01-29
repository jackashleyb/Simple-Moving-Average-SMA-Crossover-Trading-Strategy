# Simple-Moving-Average-SMA-Crossover-Trading-Strategy
A beginner-friendly Python project that implements a Simple Moving Average (SMA) crossover trading strategy using historical market data. 


This project was built by following a hands-on tutorial(https://www.youtube.com/watch?v=PUk5E8G1r44) and serves as an introduction to algorithmic trading concepts. 
------------

What I Learnt throughout this project. 

- Time-series financial data
- Algorithmic trading logic
- Python data analysis workflows
- Translating trading ideas into code

--------------

The SMA crossover strategy uses two moving averages:
- Short-term SMA (fast)
- Long-term SMA (slow)

Trading signals are generated as follows:
- Buy Signal: Short-term SMA crosses above the long-term SMA
- Sell Signal: Short-term SMA crosses below the long-term SMA
- This is a classic trend-following strategy commonly used to identify potential market entry and exit points.

---------------

Features

- Calculates Simple Moving Averages using pandas
- Generates buy and sell signals based on SMA crossovers
- Visualizes price data, SMAs, and trading signals with matplotlib
- Easy to modify SMA periods and test different assets

-------------

Tech Stack
- Python
- pandas
- matplotlib
- Jupyter Notebook


This project is for my portfolio and does not constitute financial advice. The strategy is not backtested for live trading.


