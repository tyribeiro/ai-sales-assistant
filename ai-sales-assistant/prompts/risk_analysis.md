# ⚠️ risk_analysis.md

## 🎯 Purpose
To classify and detect volatility trends in asset classes using historical returns, and generate insights tailored for client-facing sales and advisory teams.

---

## 🧠 Final Prompt

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

---

## 📊 Visuals

### Risk Level Distribution
[![Risk Levels](../charts/risk_level_distribution.png)](https://github.com/tyribeiro/ai-sales-assistant/blob/defd508dd189294dcb50a73585084d1381fbb798/ai-sales-assistant/risk_level_distribution.png)

### Max Drawdown Month by Asset Class
[![Drawdowns](../charts/drawdown_months.png)](https://github.com/tyribeiro/ai-sales-assistant/blob/defd508dd189294dcb50a73585084d1381fbb798/ai-sales-assistant/drawdown_months.png)

---

## 📁 Required Input File
- `Assets_7.csv` (numeric columns only)

---

## 🧠 Why This Prompt Works
| Element | Description |
|--------|-------------|
| **Role Definition** | Ensures consistent tone and output framing |
| **Statistical Thresholds** | Adds clarity to risk classification |
| **Structured Output Format** | Returns usable markdown tables |
| **Client Language** | Matches real advisory conversations |

---

This prompt bridges quantitative analysis with executive communication, delivering outputs that advisors can actually use in meetings and presentations.
