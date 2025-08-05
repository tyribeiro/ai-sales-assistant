# 🤖 AI Sales Assistant for Investment Firms

A portfolio-ready project demonstrating expert-level **prompt engineering** and **OpenAI integration** to analyze investment data, detect risk, and generate sales-ready insights and strategies.

---

## 📌 Project Purpose

This assistant simulates how financial analysts and investment sales teams can use AI to:

- Summarize asset performance from raw return data
- Classify risk levels and detect market regime shifts
- Generate slide-ready sales strategies
- Support advisors with real-time insights and talking points

---

## 📁 Folder Structure

```
ai-sales-assistant/                      # Visual charts for embedding in reports
│   ├── avg_returns.png
│   ├── volatility.png
│   ├── risk_level_distribution.png
│   └── drawdown_months.png
├── data/                         # Core financial datasets
│   └── Assets_7.csv
├── docs/                         # Executive documentation and prompt commentary
│   ├── executive_summary_report.md
│   ├── executive_summary_prompt.md
│   ├── prompt_versions.md
│   └── README_images/
├── outputs/                      # Final AI-generated markdown outputs
│   ├── performance_summary_output.md
│   ├── risk_summary.csv
│   └── strategy_recommendations_output.md
├── prompts/                      # Final system + user prompt instructions
│   ├── performance_summary.md
│   ├── risk_analysis.md
│   └── strategy_recommendations.md
├── README.md                     # 🔹 You are here
```

---

## 🧠 Prompt Engineering Overview

This project includes 3 high-impact prompts:

| Prompt | Purpose |
|--------|---------|
| [`performance_summary.md`](https://github.com/tyribeiro/ai-sales-assistant/blob/c0178b9244a7a413f7215fb42c499924e05f5eb2/ai-sales-assistant/prompts/performance_summary.md) | Analyzes top and underperforming assets, provides markdown summary |
| [`risk_analysis.md` ](https://github.com/tyribeiro/ai-sales-assistant/blob/c0178b9244a7a413f7215fb42c499924e05f5eb2/ai-sales-assistant/prompts/risk_analysis.md)| Classifies risk levels, identifies drawdown periods, supports advisory insights |
| https://github.com/tyribeiro/ai-sales-assistant/blob/c0178b9244a7a413f7215fb42c499924e05f5eb2/ai-sales-assistant/prompts/strategy_recommendations.md | Generates sales-friendly investment strategies based on trends |

See full details in [[`docs/prompt_versions.md`](./docs/prompt_versions.md)](https://github.com/tyribeiro/ai-sales-assistant/blob/c0178b9244a7a413f7215fb42c499924e05f5eb2/ai-sales-assistant/docs/prompt_versions.md)

---

## 📈 Visual Samples

| Chart | Description |
|-------|-------------|
| [![Average Returns](../charts/avg_returns.png)](https://github.com/tyribeiro/ai-sales-assistant/blob/6d2e9c1d60f3780071becc895bee865f72187941/ai-sales-assistant/avg_returns.png) | Average Monthly Returns |
| [![Volatility](../charts/volatility.png)](https://github.com/tyribeiro/ai-sales-assistant/blob/6d2e9c1d60f3780071becc895bee865f72187941/ai-sales-assistant/volatility.png)| Volatility by Asset |
| [![Risk Level](../charts/risk_level_distribution.png)](https://github.com/tyribeiro/ai-sales-assistant/blob/6d2e9c1d60f3780071becc895bee865f72187941/ai-sales-assistant/risk_level_distribution.png) | Risk Level Distribution |
| [![Drawdowns](../charts/drawdown_months.png)
](https://github.com/tyribeiro/ai-sales-assistant/blob/6d2e9c1d60f3780071becc895bee865f72187941/ai-sales-assistant/drawdown_months.png)| Max Drawdown by Asset |

---

## 🧾 Executive Summary

A full investor-facing summary of the project, prompts, business impact, and visuals is available in:

👉 [[`docs/executive_summary_report.md`](./docs/executive_summary_report.md)](https://github.com/tyribeiro/ai-sales-assistant/blob/c0178b9244a7a413f7215fb42c499924e05f5eb2/ai-sales-assistant/docs/executive_summary_report.md)


## 📤 Built With

- OpenAI (GPT-4 prompt engineering)
- Streamlit (interactive dashboard)
- Markdown + Data Visualization
---

