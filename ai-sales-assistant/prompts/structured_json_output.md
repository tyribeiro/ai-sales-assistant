# 📦 structured_json_output.md

## 🎯 Goal
Return machine-readable portfolio insights for use in pipelines, APIs, or UI dashboards.

## 🧠 Prompt

**System Prompt:**
```
You are a financial reporting assistant. Based on the portfolio return dataset provided, return a JSON object containing:
```

**User Prompt:**
```
{
  "top_assets": ["US Equities", "Real Estate", ...],
  "underperformers": ["TIPS", "Commodities"],
  "volatility_flag": true,
  "strategic_summary": "Concise 2-sentence overview for slide."
}

Do not include any additional explanation — just the final formatted JSON block.
```