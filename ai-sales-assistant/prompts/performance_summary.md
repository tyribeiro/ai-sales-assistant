# 📈 performance_summary.md

## 🎯 Goal
Analyze asset-level portfolio data and summarize key performance trends for executives.

## 🧠 Prompt

**System Prompt:**
```
You are a senior portfolio strategist and OpenAI financial insights model. You analyze multi-asset client portfolios to uncover performance trends, outperforming segments, and drawdown patterns over time. Your output must be precise, objective, and formatted for executive use.
```

**User Prompt:**
```
Given the asset-level returns dataset below, perform the following:

1. Calculate the average monthly return for each asset class.
2. Rank them from highest to lowest performer.
3. Identify any assets with negative average return or high volatility (>1.5× portfolio std dev).
4. Output a professional summary in the format:

- 📈 Top 3 Performing Assets: [...]
- ⚠️ Underperformers or Volatile: [...]
- 🔍 Strategic Observation: One short, impactful insight about market behavior.

Then, provide a 100–150 word slide-ready paragraph summarizing the portfolio’s overall historical performance, trends, and implications.

Return your final output in markdown format.
```

# 📊 Output: Performance Summary Prompt

**Prompt:** [`prompts/performance_summary.md`](../prompts/performance_summary.md)

---

### 🔹 Summary of Key Metrics

- **Top Performing Assets**: World Equities, Commodities, Real Estate
- **Underperformers or Volatile Assets**: Commodities, Real Estate, World Equities
- **Portfolio Std Dev**: 720.7496
- **Volatility Threshold**: 1081.1244

---

### 🧠 Executive Summary

The portfolio demonstrates a strong performance from World Equities, Commodities, and Real Estate, which consistently delivered higher average returns over the measured period. However, caution is warranted with assets like Commodities, Real Estate, World Equities, which either underperformed or exhibited elevated volatility exceeding the risk threshold of 1081.12. 

This divergence in performance suggests an opportunity to rebalance exposure toward consistently outperforming sectors while reviewing high-risk positions. Historical data reveals stable performance under certain market regimes, indicating that strategic allocation shifts could improve both return consistency and risk control moving forward.
---

### 📊 Visuals

#### Average Monthly Returns by Asset Class
![Average Returns](../charts/avg_returns.png)

#### Volatility (Standard Deviation) by Asset Class
![Volatility](../charts/volatility.png)
