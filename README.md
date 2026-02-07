# Trader Performance vs Market Sentiment

## Objective

This project analyzes how market sentiment (Fear & Greed Index) impacts trader behavior and profitability on Hyperliquid.

The goal is to:
- Examine profitability across sentiment regimes
- Analyze behavioral changes during Fear vs Greed
- Segment traders based on frequency and consistency
- Build a lightweight predictive model for profitability

---

## Repository Structure

├── data/  
│   └── fear_greed_index.csv  
│  
├── notebook/  
│   └── trader_sentiment_analysis.ipynb  
│  
├── outputs/  
│   └── (generated visualizations & results)  
│  
└── README.md  

---

## Dataset Information

### 1. Fear & Greed Index
Daily sentiment classification:
- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

### 2. Hyperliquid Historical Trading Data

⚠️ Note:  
The historical trading dataset exceeds GitHub's file size limit and is therefore not uploaded in this repository.

To reproduce the analysis:
- Place the historical dataset CSV inside the `data/` folder
- Ensure the file name matches the notebook reference

---

## Key Analysis Performed

### 1. Sentiment-Based Performance Analysis
- Total PnL by sentiment regime
- Return percentage (PnL / Volume)
- Win rate across regimes
- Trade frequency analysis

### 2. Trader Segmentation

#### Frequency Segmentation
- High Frequency Traders
- Low Frequency Traders

#### Consistency Segmentation
- Consistent Traders
- Inconsistent Traders

Performance comparison across sentiment regimes was conducted for each segment.

### 3. Behavioral Insights
- Trade activity during fear vs greed
- Volume deployment patterns
- Profit concentration during extreme sentiment

---

## Bonus: Predictive Modeling

A lightweight Random Forest classifier was built to predict daily profitability using:

- Sentiment regime
- Trade count
- Average trade size

This demonstrates how behavioral and sentiment features can help anticipate trading outcomes.

---

## Key Insights

- Extreme Greed periods showed the highest return percentage.
- Fear regimes exhibited higher trading frequency.
- Consistent traders maintained stronger performance stability.
- Profitability varies significantly across sentiment intensity.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## How to Run

1. Clone the repository
2. Place datasets inside the `data/` folder
3. Open the notebook in Jupyter/Colab
4. Run all cells sequentially

---

## Author

Jaya  
Data Science Intern Candidate
