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
