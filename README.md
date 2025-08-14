# Moving Average Crossover with ML Filter

A quantitative trading strategy that combines traditional moving average crossover signals with machine learning filtering to improve trade selection.

## Overview

This implementation compares a baseline MA(20/100) crossover strategy against an ML-enhanced version that uses a Gradient Boosting classifier to filter entry signals based on technical indicators.

## Features

- **Baseline Strategy**: Simple moving average crossover (20/100 periods)
- **ML Enhancement**: Gradient boosting classifier to filter low-probability trades
- **Technical Indicators**: MACD, RSI, Bollinger Bands, momentum, and volatility features
- **Risk Metrics**: CAGR, Sharpe ratio, maximum drawdown analysis
- **Visualization**: Comprehensive charts and performance comparisons

## Requirements

```bash
pip install yfinance pandas numpy scikit-learn ta matplotlib
```

## Usage

1. Open `ma_crossover_ml.ipynb` in Jupyter Notebook/Lab
2. Run all cells to execute the complete analysis
3. Modify the `TICKER` parameter to test different stocks
4. Adjust `PROBA_THRESHOLD` to change ML filtering sensitivity

## Output

- Performance metrics comparison
- Equity curve visualizations
- `equity_curves.csv` with backtest results

## Author

David Dagyei