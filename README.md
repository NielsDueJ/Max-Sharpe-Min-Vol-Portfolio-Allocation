# Max-Sharpe-Min-Vol-Portfolio-Allocation
Performing portfolio optimization using Monte Carlo simulation method to build Maximum Sharpe Ratio and Minimum Volatility Portfolios. I simulate the future values of these portfolios and calculates Value at Risk (VaR) and Conditional Value at Risk (CVaR). These results are visualized using Seaborn (because Im low key a Seaborn fan) and Matplotlib.

## Import Libraries
The script starts by importing the necessary libraries for data handling, numerical operations, optimization, and visualization.

## Configuration
Suppress future warnings, set the plot style, and specify the list of stock tickers.

## Historical Data
Fetch historical data for the specified tickers from an API

## Portfolio Optimization
Define functions for calculating portfolio performance and generating random portfolios. Identify and display the Maximum Sharpe Ratio and Minimum Volatility portfolios.

## Monte Carlo Simulation
Simulate the future values of the Maximum Sharpe Ratio and Minimum Volatility portfolios over a 10-year period.

## Value at Risk (VaR) and Conditional Value at Risk (CVaR)
Calculate and display the VaR and CVaR values for risk assessment of the simulated portfolios.

## Visualization
Use Seaborn and Matplotlib to visualize the portfolio performance, Monte Carlo simulations, and the correlation matrix of stock returns.
