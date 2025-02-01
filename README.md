# Cascaded-LSTM-PPO-Stock-Trading

# Cascaded LSTM PPO - Deep Reinforcement Learning for Automated Stock Trading

This repository implements a novel **Deep Reinforcement Learning (DRL)** based automated stock trading system using **cascaded LSTM networks** in combination with the **Proximal Policy Optimization (PPO)** algorithm. The model is designed to optimize trading strategies and decision-making in the stock market, particularly for the **Dow 30 stocks**. The system employs a two-stage architecture:

## Features

- **Cascaded LSTM Architecture**: Utilizes **LSTM networks** for feature extraction, capturing temporal dependencies in stock price data and technical indicators.
- **PPO-based Trading Agent**: Implements **Proximal Policy Optimization (PPO)** to optimize trading strategies for the agent.
- **Dow 30 Stocks**: The model uses **historical data** of the 30 stocks in the **Dow Jones Industrial Average** for training and testing.
- **Technical Indicators**: Includes various **technical indicators** such as **RSI**, **MACD**, and **Moving Averages** for decision-making.
- **Risk Management**: Implements **risk management** using financial turbulence indices like **CCI** and **ADX**.

## Architecture Overview

### 1. **LSTM for Feature Extraction**:
   - The model uses **LSTM (Long Short-Term Memory)** networks to extract and model the temporal dependencies in historical stock data, including technical indicators and price movements.

### 2. **PPO for Policy Optimization**:
   - The **PPO algorithm** is used to optimize the agent's trading decisions, updating the policy for better performance in the trading environment.

## Evaluation Metrics

The model’s performance is evaluated using the following key metrics:

- **Cumulative Return**: The total return achieved over the testing period.
- **Sharpe Ratio**: A risk-adjusted return metric.
- **Maximum Drawdown**: The greatest peak-to-trough decline in the trading performance.
- **Profit per Trade**: The average return for each individual trade made by the model.
- **Maximum Earning Rate**: The highest return rate achieved during a specific time period or set of trades.


## References

For a detailed explanation of the approach and methodology behind this project, please refer to the original paper:

- **[Cascaded LSTM and PPO-based Stock Trading System (arXiv)](https://arxiv.org/abs/2212.02721)**.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.


