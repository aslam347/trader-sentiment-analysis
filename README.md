# Trader Behavior Insights from Market Sentiment

This project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on the Hyperliquid platform.

## Objective

The goal of this project is to explore how market sentiment affects trader profitability, activity, and risk-taking behavior.

## Datasets

Two datasets were used in this analysis:

1. **Bitcoin Fear & Greed Index**
   - Contains daily market sentiment classification (Fear, Greed, Neutral, Extreme Fear, Extreme Greed).

2. **Hyperliquid Historical Trading Data**
   - Contains trader-level trade execution data including trade size, direction, and profit/loss.

## Project Workflow

1. Data Loading
2. Data Cleaning and Preparation
3. Timestamp Conversion and Dataset Alignment
4. Feature Engineering
5. Sentiment-Based Trading Analysis
6. Visualization and Insights

## Key Insights

- Trader profitability is highest during **Extreme Greed** periods.
- Trading activity increases during **Fear** market conditions.
- Traders tend to take **larger trade sizes during Fear periods**, indicating higher risk-taking behavior.

## Strategy Recommendations

- **Momentum Strategy:** Traders may benefit from following market momentum during Extreme Greed periods.
- **Risk Management Strategy:** Reduce position size and apply stricter risk management during Fear markets.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
