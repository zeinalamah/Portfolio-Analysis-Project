# Portfolio Optimization and Performance Analysis

This Jupyter Notebook, **Portfolio Optimization and Performance Analysis**, was developed in 2020 as part of my Master's in Finance thesis at the **Lebanese University**. It represents my first academic research paper and explores the application of portfolio optimization techniques, risk-return metrics, and performance analysis using Python.

## Features

- **Portfolio Optimization**:
  - Monte Carlo simulation for portfolio weights.
  - Efficient Frontier construction.
  - Optimization for Maximum Sharpe Ratio, Minimum Variance, and Naive Portfolios.
- **Metrics Computation**:
  - Sharpe Ratio, Treynor Ratio, Jensen's Alpha, and Beta.
- **Statistical Analysis**:
  - Independent T-tests to compare portfolio and benchmark metrics.
- **Visualization**:
  - Correlation and covariance heatmaps.
  - Efficient frontier plots for portfolio and benchmark.
  - Allocation bar charts for optimal, naive, and minimum variance portfolios.

## Acknowledgments

This project would not have been possible without the guidance provided in **Yves Hilpisch's book, _Python for Finance_**. I am deeply grateful for the clarity and depth of the material, which laid the foundation for this work.

## Usage

1. **Install Required Libraries**:
   ```bash
   pip install numpy pandas yfinance scipy matplotlib seaborn dataframe_image
   ```
2. **Open the Notebook in Jupyter**:

   ```bash
   jupyter notebook Portfolio Simulator V1.0.ipynb
   ```
3. **Update the Notebook**:
    - Replace asset tickers and date ranges with your preferred inputs.
    - Adjust parameters such as the risk-free rate (Rf) or simulation count (simulations) if needed.
    
4. **Execute the Cells**:
   Run the notebook cell by cell to perform portfolio analysis and visualize the results.

## Notes
This notebook was developed as an academic project and may have areas for optimization and improvement.
It serves as an educational tool for understanding portfolio theory and financial modeling.
Feel free to adapt the script to suit your research or personal learning goals.

## Output
**The notebook generates**:

CSV files containing portfolio and benchmark returns, weights, and metrics.
**Visual outputs**, such as:
Correlation and covariance matrices.
Bar charts for portfolio and benchmark asset allocations.
Efficient frontier plots.

## Statistical Tests
The script conducts independent T-tests to compare expected returns, standard deviations, betas, Sharpe ratios, Treynor ratios, and Jensen's alpha between portfolios and benchmarks.

## Contact
If you have any questions or feedback, feel free to reach out.
