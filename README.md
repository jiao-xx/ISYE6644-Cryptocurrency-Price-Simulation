# Project Title: Cryptocurrency Price Simulation

## Overview
This project investigates trading strategies tailored to the volatile cryptocurrency market by leveraging Monte Carlo simulations, Hidden Markov Models (HMM), and historical pricing data. The focus is on simulating price behaviors and evaluating the performance of trading strategies across various cryptocurrencies, such as Bitcoin, Ethereum, Dogecoin, and Shiba Inu.

## Key Features
- **Monte Carlo Simulations**: Used for forecasting potential price paths and understanding the risks and returns of trading strategies.
- **Hidden Markov Models**: Applied to classify market states (bull, bear, stagnant) and adapt trading strategies accordingly.
- **Moving Average Crossover Strategy**: Implemented to generate buy and sell signals based on short-term and long-term moving averages.
- **News Event Integration**: Incorporated historical news data to enhance strategy realism and capture the impact of significant events on cryptocurrency prices.
- **Performance Metrics**: Evaluated strategies using ROI, Sharpe Ratio, and Maximum Drawdown.

## Tools and Technologies
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, hmmlearn.
- **Jupyter Notebook**: For implementation and visualization.
- **Data Sources**: Historical pricing data from Yahoo Finance and news data from Google News and CryptoPanic.

## Workflow
1. **Data Collection and Preprocessing**:
   - Collected historical price data for six cryptocurrencies: BTC, ETH, DOGE, SHIB, PEPE, and WIF.
   - Preprocessed data to ensure consistency, removing null values and formatting for analysis.

2. **Simulation and Modeling**:
   - Applied the Moving Average Crossover Strategy to simulate trading decisions.
   - Used Hidden Markov Models to identify market states and adapt strategies.
   - Conducted Monte Carlo simulations to generate future price scenarios.

3. **Performance Evaluation**:
   - Assessed strategies using metrics like ROI, Sharpe Ratio, and Maximum Drawdown.
   - Visualized portfolio performance and trading signals.

4. **News Impact Analysis**:
   - Analyzed the influence of major news events on price movements for BTC and ETH.

## Results
- **BTC**: Demonstrated stability with limited growth potential, suitable for risk-averse investors.
- **ETH**: Showed moderate growth with minimal volatility, offering balanced risk-adjusted returns.
- **DOGE & SHIB**: Exhibited high returns but significant volatility, appealing to high-risk investors.
- **PEPE & WIF**: Indicated poor performance with high risks, cautioning against investment.

### Example Visuals:
- **Price Simulations**: Compared historical price paths with simulated outcomes.
- **Trading Signals**: Visualized buy and sell points based on moving averages.
- **Impact Analysis**: Highlighted price changes following major news events.

## Repository Structure
- **Crypto Part 1.ipynb**: Data preprocessing and Moving Average Crossover Strategy.
- **Crypto Part 2.ipynb**: HMM implementation, Monte Carlo simulations, and news impact analysis.
- **Visualization**: [Poster](https://github.com/jiao-xx/ISYE6644-Cryptocurrency-Price-Simulation/blob/main/Final%20Poster.pdf)

## Future Enhancements
- Expand the dataset to include more cryptocurrencies and longer time periods.
- Incorporate real-time data and predictive analytics.
- Explore hybrid models combining technical and sentiment analysis.
