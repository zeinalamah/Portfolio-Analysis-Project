# Portfolio Optimization and Performance Analysis

This Jupyter Notebook was initially written in 2020 as part of my first academic research paper for my Master’s in Finance at the Lebanese University. The project focuses on portfolio optimization, risk metrics, and performance analysis, integrating concepts like Monte Carlo simulations, the efficient frontier, and Sharpe and Treynor Ratios.

## Features
- 📈 Downloads historical price data for assets using Yahoo Finance.
- 🔄 Simulates portfolios using Monte Carlo methods.
- 📊 Calculates portfolio metrics, including:
  - Expected returns and volatility
  - Beta, Sharpe Ratio, Treynor Ratio, and Jensen's Alpha
- 🛠️ Optimizes portfolios for:
  - Maximum Sharpe Ratio
  - Minimum variance
- 📉 Visualizes the efficient frontier and portfolio metrics.
- 📊 Performs statistical analysis on portfolio returns.

## Acknowledgments
This project would not have been possible without the book **_Python for Finance_** by **Yves Hilpisch**. His clear explanations and practical examples were invaluable in helping me navigate financial modeling and Python programming. I am deeply grateful for his work.

## Usage
1. Install the required libraries:
   ```bash
   pip install numpy pandas yfinance scipy matplotlib statsmodels
2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Portfolio_Optimization.ipynb
3. Replace asset tickers and date ranges with your preferred inputs.
4. Execute the cells step by step to perform portfolio analysis and visualize results.
