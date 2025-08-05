# 📘 Prompt Engineering Evolution: From V1 to Expert-Level

This document outlines how the original prompt ideas were refined into professional-grade OpenAI prompts suitable for business applications — specifically for investment sales teams.

---

## 🔹 Prompt 1: Portfolio Performance Summary

### ❌ Version 1 (Basic)
> "Summarize the portfolio performance across all asset classes. Focus on best/worst performers and trends. Return 3 bullet points and a paragraph."

### 🔍 Why It Wasn’t Good Enough
- No guidance on how to calculate or rank performance
- Lacked precision and structure for automation
- Output format not defined — hard to reuse in presentations

### ✅ Final Version (Expert-Level)

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

---

## 🔹 Prompt 2: Risk Trend Analysis

### ❌ Version 1 (Basic)
> "Analyze for risk trends over time. Focus on volatility, risky assets, regime impact. Give 3 insights and actions."

### 🔍 Why It Wasn’t Good Enough
- No method for defining “risk” or thresholds
- Lacked structure for automation or table output
- Didn’t tailor the language for advisor or sales use

### ✅ Final Version (Expert-Level)

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

## 🔹 Prompt 3: Sales Strategy Recommendations

### ❌ Version 1 (Basic)
> "Give 2 strategy recommendations from the portfolio history. Include title and paragraph."

### 🔍 Why It Wasn’t Good Enough
- No structure for slide formatting
- Not tailored to sales pitch language
- No audience consideration (e.g., advisors, executives)

### ✅ Final Version (Expert-Level)

**System Prompt:**
```
You are a financial sales strategist generating pitch-ready recommendations based on historical portfolio performance. Your output should mirror what an investment sales team might include in a presentation to a high-net-worth client.
```

**User Prompt:**
```
Based on this portfolio return dataset and risk classification:

1. Identify two trends or anomalies that can be turned into strategic opportunities.
2. For each, write:
   - A slide headline (max 10 words, bold, sales-ready)
   - A 2–3 sentence strategy explanation (include rationale + benefit)
   - An optional tip for the advisor to use in conversation

Then return your output in this markdown format:

## 🧠 Strategy Recommendation 1
**Headline:** Bold Slide Title Here  
**Explanation:** ...  
**Advisor Tip:** ...

## 🧠 Strategy Recommendation 2
...

End with a final note: “These insights are derived from historical asset behavior and designed to enhance portfolio conversations.”
```

---

## 🧠 What Makes These Prompts Expert-Level?

| Element | Purpose |
|--------|---------|
| **System Role** | Sets tone and behavior for model |
| **Step-by-Step Tasks** | Minimizes ambiguity and hallucination |
| **Thresholds & Classifications** | Adds precision and automation logic |
| **Output Format Constraints** | Markdown or table-ready for slides |
| **Audience Awareness** | Makes output usable for real business teams |

---

These prompts transform OpenAI from a Q&A tool into a business co-pilot, aligning outputs with real-world deliverables used by investment and sales teams.
