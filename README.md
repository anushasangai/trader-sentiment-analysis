# Trader Performance vs Market Sentiment Analysis

## Objective

This project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader behavior and performance on Hyperliquid.

The goal is to uncover behavioral patterns and derive actionable strategy insights based on sentiment regimes.

---

## Datasets Used

1. Bitcoin Market Sentiment (Fear/Greed Index)
2. Historical Trader Data (Hyperliquid)

---

## Methodology

1. Cleaned and aligned trade-level and sentiment datasets.
2. Converted timestamps to daily granularity.
3. Engineered trader-day level metrics:
   - Daily PnL
   - Win rate
   - Trade frequency
   - Average trade size
   - Long/short bias
4. Compared performance across Fear and Greed regimes.
5. Segmented traders into Frequent and Infrequent groups.
6. Derived strategy recommendations.

---

## Key Insights

- Fear regimes exhibit higher average daily PnL but lower win rates, suggesting volatility-driven profit opportunities.
- Frequent traders significantly outperform infrequent traders across both sentiment regimes.
- Greed regimes show higher win rates, favoring consistent directional strategies.

---

## Strategy Recommendations

1. Increase tactical trading activity during Fear regimes to capitalize on volatility.
2. Prioritize structured directional exposure during Greed regimes for consistent profitability.

---

## How to Run

1. Open the Jupyter Notebook file.
2. Install required packages: pandas, numpy, matplotlib.
3. Run all cells sequentially.
