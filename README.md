# Trader Performance vs Market Sentiment

## Objective
Analyze how market sentiment (Fear/Greed) influences trader behavior and profitability.

---

## Dataset
- Bitcoin Fear & Greed Index  
- Hyperliquid Trader Data  

---

## Methodology
- Cleaned and aligned datasets by date  
- Aggregated trader-level daily metrics:
  - PnL  
  - Trade count  
  - Average trade size  
- Merged datasets on date  
- Compared performance across sentiment regimes  

---

## Key Insights

## Key Insights

1. Traders achieve significantly higher profitability during Fear periods, suggesting that volatile market conditions create more exploitable opportunities than stable bullish trends.
2. Trade activity increases sharply during Fear, indicating that traders are more active and reactive during uncertain market conditions.
3. Extreme Greed is associated with a decline in median profitability, implying that overconfidence and trend-chasing behavior negatively impact performance.

---

## Strategy Recommendations

- Increase trading activity during Fear  
- Reduce risk and avoid overtrading during Greed  
- Apply segment-based strategies

---  

## Business Impact

Understanding trader behavior across sentiment regimes can help:
- Optimize trading strategies based on market conditions
- Reduce risk exposure during overconfident (Greed) phases
- Identify high-performing trader segments for scaling strategies
---

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebook/Data Science Assignment.ipynb
