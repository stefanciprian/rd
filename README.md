# R & D

This project focuses on analyzing stock prices, trading volumes, VIX using Python. The analysis is performed using Jupyter Notebooks, providing a comprehensive approach to examining financial data. The project can be used to extract insights from stock market trends by processing and visualizing price and volume data.

## Project Overview

This repository contains Python code for:

- Reading stock prices and trading volume data from CSV files or using yfinance
- Cleaning and preprocessing the data
- Calculating statistical summaries (e.g., moving averages, returns, etc.)
- Visualizing stock price movements and trading volume trends

## Installation

To run the notebooks, follow these steps:

### Clone the repository

```bash
git clone https://github.com/stefanciprian/rd.git
```

### Install the required dependencies

```bash
pip install -r requirements.txt
```

### Run the Jupyter Notebook

```bash
jupyter notebook prices_and_volumes.ipynb
```

## Files

- **prices_and_volumes.ipynb**: The main notebook file containing code for analyzing stock prices and volumes.
- **vix.ipynb**: Notebook with VIX tests.

## Features

- **Load Data**: Load historical stock data from CSV/yfinance.
- **ARIMA**: Implement AutoRegressive Integrated Moving Average for time series forecasting.
- **Bayesian**: Apply Bayesian methods for statistical analysis.
- **Chua's Circuit - Chaotic Algorithm**: Explore chaotic dynamics with Chua's Circuit.
- **Duffing Oscillator - Chaotic Algorithm**: Model chaotic behavior using the Duffing oscillator.
- **Fractional Gaussian Noise (fGn)**: Analyze data with fractional Gaussian noise characteristics.
- **Fractional Lévy Stable Motion (FLSM)**: Model data using fractional Lévy stable motion.
- **Fuzzy Logic**: Apply fuzzy logic for reasoning under uncertainty.
- **Heatmap**: Visualize data correlations and distributions with heatmaps.
- **Hénon Map - Chaotic Algorithm**: Study chaotic patterns with the Hénon map.
- **Higuchi Fractal Dimension**: Calculate the Higuchi fractal dimension for time series.
- **Hurst Exponent**: Estimate the Hurst exponent to assess long-term memory of time series.
- **Ikeda Map - Chaotic Algorithm**: Use the Ikeda map to explore complex chaotic systems.
- **Julia Sets - Chaotic Algorithm**: Visualize fractal structures through Julia sets.
- **Kalman Filter - Linear Quadratic Estimation**: Apply Kalman filtering for state estimation in linear systems.
- **Linear Regression**: Perform linear regression analysis on stock data.
- **Lorenz System**: Analyze the Lorenz system for chaotic behavior.
- **Markov**: Implement Markov models for predictive analysis.
- **Mackey-Glass Equation - Chaotic Algorithm**: Model time series using the Mackey-Glass equation for chaotic behavior.
- **Pearson**: Calculate Pearson correlation coefficients for data relationships.
- **Random Forest**: Use random forest algorithms for classification and regression tasks.
- **Rössler Attractor - Chaotic Algorithm**: Study chaotic dynamics with the Rössler attractor.
- **Standard Map (Chirikov-Taylor Map) - Chaotic Algorithm**: Model chaotic behavior with the standard map (Chirikov-Taylor map).

- **VIX Time Series with Highlighted Trend Changes**: Analyze VIX time series data and highlight significant trend changes for better insights.
- **Monte Carlo Shuffled Projection for VIX**: Use Monte Carlo simulations to create shuffled projections of VIX data, allowing for uncertainty quantification.
- **Monte Carlo Prediction of VIX**: Implement Monte Carlo methods to predict future VIX values based on historical data patterns.
- **MCMC Projections for VIX**: Apply Markov Chain Monte Carlo (MCMC) techniques to generate projections for VIX, enhancing predictive accuracy.
- **Markov Regime Switching Model**: Utilize a Markov regime switching model to identify different market regimes and their impact on VIX.
- **Perturbation Analysis and Future Projections for VIX**: Conduct perturbation analysis to assess the effects of small changes in parameters on future VIX projections.
- **Synthetic Control Method for VIX**: Implement the synthetic control method to estimate the causal effect of interventions on VIX.
- **Projections Using Latin Hypercube Sampling (LHS)**: Use Latin Hypercube Sampling to create projections for VIX, ensuring a more comprehensive exploration of uncertainty.
- **VIX Projections Using Geometric Brownian Motion (GBM)**: Model VIX projections using Geometric Brownian Motion to capture the stochastic nature of financial markets.
- **Recurrence Quantification Analysis (RQA)**: Perform Recurrence Quantification Analysis to study the dynamics of VIX time series and identify patterns.
- **VIX Forecast Using Chaos Neural Network**: Leverage chaos neural networks to forecast VIX, utilizing complex patterns in historical data.

## How to Use

After loading your stock data, the notebook will guide you through various analytical steps such as calculating statistics, applying technical indicators, and visualizing results.

## Contributing

Feel free to contribute to this project by submitting a pull request or reporting an issue.
