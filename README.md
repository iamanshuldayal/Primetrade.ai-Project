# Trader Performance vs Market Sentiment Analysis

## Objective

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader behavior on Hyperliquid.
The goal is to understand how emotional market conditions affect profitability, risk-taking behavior, and trading activity, and to derive actionable trading strategies.

---

## Data Preparation

Two datasets were used:

1. Bitcoin Market Sentiment (Fear & Greed Index)
2. Historical Trader Execution Data

### Processing Steps

* Converted timestamps and aligned both datasets at daily level
* Removed trades without sentiment labels to avoid biased analysis
* Created key metrics:

  * Daily PnL per trader
  * Win rate
  * Average trade size
  * Trading frequency
  * Long/short ratio

### Trader Segmentation

* High-risk vs Low-risk (based on trade size)
* Frequent vs Infrequent traders
* Consistent winners vs others

---

## Key Findings

### 1. Sentiment strongly impacts profitability

High-risk traders achieved the highest profits during **Extreme Greed** but showed weak performance during **Fear and Extreme Fear** conditions, indicating strong dependence on bullish momentum.

### 2. Risk-taking amplifies market emotions

During optimistic sentiment, traders increased position size and generated larger gains.
During fearful sentiment, the same behavior reduced performance due to volatility and reversals.

### 3. Conservative trading improves stability

Low-risk traders showed relatively stable returns across all sentiment regimes, suggesting disciplined trading behavior rather than emotional decision-making.

---

## Strategy Recommendations

### Adaptive Risk Control

Reduce position size by 40–60% during Fear and Extreme Fear markets to limit drawdowns.

### Aggressive Trading in Bullish Conditions

Allow larger exposure only during Extreme Greed periods where trend continuation probability is higher.

### Neutral Market Safe Mode

Use a low-risk strategy during Neutral sentiment for consistent performance.

---

## Business Impact

Sentiment-aware position sizing can improve trading performance by:

* Increasing profitability in bullish conditions
* Reducing losses in bearish markets
* Stabilizing long-term returns

This demonstrates that combining behavioral indicators with trading activity enables smarter and adaptive trading strategies.
