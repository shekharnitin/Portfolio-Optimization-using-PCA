# Portfolio Optimization using PCA
This repository demonstrates how Principal Component Analysis (PCA) can be leveraged to optimize a portfolio of stocks, reducing dimensionality and improving risk-adjusted returns. The project is built in Python and is intended for data scientists, quantitative analysts, finance students, and anyone interested in advanced portfolio management techniques.
# Project Overview
Traditional portfolio optimization can be challenging when dealing with a large number of correlated assets. By applying PCA, we can:
- Reduce the dimensionality of the asset space
- Identify the main drivers of portfolio risk and return
- Construct more robust portfolios by focusing on uncorrelated principal components

This notebook guides you through the entire process: from data collection, exploratory analysis, PCA transformation, to portfolio construction and performance evaluation.
# Features
- Data Acquisition: Downloads historical price data for Dow Jones 30 stocks using yfinance.

- Data Preprocessing: Cleans and prepares the data, handling missing values and calculating log returns.

- Exploratory Data Analysis: Visualizes price trends, returns, and correlations.

- Principal Component Analysis: Applies PCA to returns to identify key risk factors.

- Portfolio Construction: Builds portfolios based on principal components.

- Performance Evaluation: Compares optimized portfolios to traditional approaches using risk and return metrics.
# Project Structure
portfolio-optimization-pca/<br>
│<br>
├── Portfolio-Optimization.ipynb   (Main analysis notebook)<br>
├── requirements.txt               (Python dependencies)<br>
└── README.md                      (This file)<br>
# Dependencies
- numpy
- pandas
- matplotlib
- seaborn
- yfinance
- scikit-learn
- statsmodels
# Contributing 
Contributions are welcome! If you have suggestions, bug fixes, or additional features, feel free to open an issue or submit a pull request.
