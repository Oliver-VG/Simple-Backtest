# Simple-Backtest
Simple Moving Average Crossover Backtest

Overview
This project implements a basic backtest of a 50/200-day moving average crossover strategy on Apple (AAPL) stock from 2018 to 2024.
It demonstrates key elements of systematic trading including signal generation, transaction cost modeling, and performance evaluation.
The backtest includes:
- Realistic transaction cost penalties
- Calculation of Sharpe ratios
- Visualization of cumulative returns compared to a buy-and-hold strategy

Project Structure
Data Acquisition: Historical price data via yfinance

Signal Generation:
- Buy when 50-day MA crosses above 200-day MA
- Sell when 50-day MA crosses below 200-day MA

Performance Metrics:
- Sharpe ratio
- Final cumulative returns

Visualization:
Equity curve comparison (Strategy vs. Buy-and-Hold)

Libraries Used
- pandas
- numpy
- matplotlib
- yfinance

Install requirements with:
bash:
pip install pandas numpy matplotlib yfinance

Usage
1. Clone the repository:
bash:
git clone https://github.com/Oliver-VG/Simple-Backtest

3. Run the Jupyter Notebook:
simple_backtest.ipynb

4. Modify parameters easily:
- Change symbol, start_date, end_date
- Adjust short_window and long_window for different MA strategies
- Tweak transaction cost assumptions

About
This project was created as a demonstration of Python backtesting skills for quant internships and strategy research roles.
It can serve as a foundation for more advanced systematic trading strategies.
