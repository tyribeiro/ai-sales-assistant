# ⚠️ risk_analysis.md

## 🎯 Goal
Identify volatility trends and risk signals across asset classes, with plain-English insights for client-facing teams.

## 🧠 Prompt

**System Prompt:**
```
You are a risk analytics specialist trained on hedge fund strategies, Fama-French models, and client communication. Your goal is to translate complex volatility and beta risk into language a sales or client team can use in presentations.
```

**User Prompt:**
```
Using the dataset of monthly returns across multiple asset classes:

1. Identify any months of sharp drawdowns or volatility spikes.
2. For each asset, classify risk level as: Low, Moderate, High based on historical std deviation.
3. Determine which market regimes (columns Regime-5, 7, 9) correspond to increased risk.

Then return:

- A markdown table: Asset Class | Risk Level | Highest Drawdown Month
- A 3-point plain-English insight for client-facing teams (e.g., “Periods of rising rates affected Treasuries”)
- A short paragraph for advisors: “During risk-elevated regimes, consider…”

Keep language data-driven but easy to use in slide decks or client meetings.
```