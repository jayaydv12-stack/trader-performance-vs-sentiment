# Trader Performance vs Market Sentiment

## Objective
Analyze how market sentiment (Fear/Greed) affects trader behavior and performance on Hyperliquid.

## Datasets
- Bitcoin Fear & Greed Index
- Hyperliquid historical trader data

## Methodology
- Data cleaning and preprocessing
- Daily alignment of trades with sentiment
- Feature engineering (PnL, win rate, leverage, trade frequency)
- Trader segmentation
- Comparative analysis across sentiment regimes

## Key Insights
- Trader performance differs between Fear and Greed periods
- Leverage and trade frequency change with sentiment
- High-leverage traders face higher downside risk during Fear days

## Strategy Recommendations
- Reduce leverage exposure during Fear periods
- Increase trade activity cautiously during Greed periods

## How to Run
Open `notebook/trader_sentiment_analysis.ipynb` and run all cells.
