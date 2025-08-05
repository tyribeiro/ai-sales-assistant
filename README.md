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
ai-sales-assistant/
├── app/                          # Streamlit dashboard and OpenAI pipeline scripts
│   └── dashboard.py
├── charts/                       # Visual charts for embedding in reports
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
├── notebooks/                    # (Optional) Jupyter analysis or EDA
├── README.md                     # 🔹 You are here
```

---

## 🧠 Prompt Engineering Overview

This project includes 3 high-impact prompts:

| Prompt | Purpose |
|--------|---------|
| `performance_summary.md` | Analyzes top and underperforming assets, provides markdown summary |
| `risk_analysis.md` | Classifies risk levels, identifies drawdown periods, supports advisory insights |
| `strategy_recommendations.md` | Generates sales-friendly investment strategies based on trends |

See full details in [`docs/prompt_versions.md`](./docs/prompt_versions.md)

---

## 📈 Visual Samples

| Chart | Description |
|-------|-------------|
| ![Avg Returns](charts/avg_returns.png) | Average Monthly Returns |
| ![Volatility](charts/volatility.png) | Volatility by Asset |
| ![Risk Level](charts/risk_level_distribution.png) | Risk Level Distribution |
| ![Drawdowns](charts/drawdown_months.png) | Max Drawdown by Asset |

---

## 🧾 Executive Summary

A full investor-facing summary of the project, prompts, business impact, and visuals is available in:

👉 [`docs/executive_summary_report.md`](./docs/executive_summary_report.md)

---

## 🚀 Run the Dashboard

```bash
pip install streamlit
streamlit run app/dashboard.py
```

---

## 📤 Built With

- OpenAI (GPT-4 prompt engineering)
- Python (Pandas, Matplotlib, Seaborn)
- Streamlit (interactive dashboard)
- Markdown + Data Visualization

---

## 📄 License

MIT License. Use freely with credit.

---
