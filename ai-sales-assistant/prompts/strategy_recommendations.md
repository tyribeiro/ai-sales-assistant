# 🧠 strategy_recommendations.md

## 🎯 Purpose
Generate professional, slide-ready investment strategy recommendations based on historical performance and risk analysis of a multi-asset portfolio.

---

## 🧠 Final Prompt

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

# 🧠 Output: Strategy Recommendations Prompt

**Prompt:** [`prompts/strategy_recommendations.md`](../prompts/strategy_recommendations.md)

---

## 🧠 Strategy Recommendation 1
**Headline:** **Capitalize on Global Equity Strength**  
**Explanation:** Recent portfolio performance indicates consistent outperformance from World Equities. Allocating a higher weight to global markets may enhance return potential, especially given ongoing strength in international sectors.  
**Advisor Tip:** Position this as a diversification opportunity that also improves performance against domestic-only portfolios.

---

## 🧠 Strategy Recommendation 2
**Headline:** **Reassess Risk in Real Assets**  
**Explanation:** Although Real Estate and Commodities delivered strong returns, they also showed above-average volatility. Reducing concentrated exposure can help stabilize returns without sacrificing upside.  
**Advisor Tip:** Use regime data to explain when these assets perform best — and when to hedge.

---

These insights are derived from historical asset behavior and designed to enhance portfolio conversations.

---

## 📁 Required Input Files
- `Assets_7.csv` (historical performance)
- Risk summary from Prompt 2 (drawdowns, volatility levels)

---

## 🧠 Why This Prompt Works

| Feature | Description |
|--------|-------------|
| **Slide-ready formatting** | Clean sections with headlines and brief explanations |
| **Advisor Tips** | Adds usability for client conversations |
| **Business tone** | Matches language used in wealth management and HNW sales |
| **Flexibility** | Easy to plug into slides, emails, or CRM notes |

---

This prompt enables OpenAI to act as a strategic co-pilot, generating persuasive and data-backed strategies for financial advisors to deliver in client meetings.
