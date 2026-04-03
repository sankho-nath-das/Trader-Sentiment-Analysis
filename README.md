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

1. Traders perform better during Fear than Greed  
2. Trade activity increases significantly during Fear  
3. Extreme Greed leads to reduced profitability  

---

## Strategy Recommendations

- Increase trading activity during Fear  
- Reduce risk and avoid overtrading during Greed  
- Apply segment-based strategies  

---

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebook/analysis.ipynb
