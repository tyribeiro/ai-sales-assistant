# 🤖 AI Sales Assistant for Investment Firms

This project simulates a real-world AI-powered sales insight generator built for investment firms. It demonstrates expert-level prompt engineering using OpenAI to analyze multi-asset client portfolios and generate executive summaries, risk analysis, and sales strategy recommendations.

---

## 📌 Overview

The **AI Sales Assistant** converts portfolio performance data into slide-ready insights for financial advisors and sales teams. It simulates what a prompt engineer or analyst might build at firms like Robert Half to support client engagement and decision-making.

---

## 🔍 Key Features

- Analyze asset-level performance and return trends
- Detect risk volatility using historical regime data
- Generate markdown/JSON summaries and slide-friendly strategies
- Structure prompts using OpenAI best practices (roles, constraints, format control)

---

## 🧠 Prompt Engineering Highlights

This project showcases advanced prompt engineering:

- Role-based system prompts (`You are a portfolio strategist`)
- Step-by-step data instructions
- Output constraints (markdown tables, summaries, JSON)
- Business-ready recommendations

See [`docs/prompt_versions.md`](./docs/prompt_versions.md) for the evolution from basic to professional-grade prompts.

---

## 🗂️ Project Structure

```
ai-sales-assistant/
├── data/                   # Portfolio datasets
├── notebooks/              # Jupyter notebooks for exploration
├── outputs/                # Text and visual outputs
├── slides/                 # Exported PowerPoint/slide content
├── app/                    # OpenAI automation scripts
├── prompts/                # Prompt templates (.md)
├── docs/                   # Executive summary & prompt documentation
```

---

## 📁 Dataset Used

- `Assets_7.csv`: Simulated portfolio performance (US Equities, Bonds, Real Estate, etc.)
- `SP500.csv`, `Fama-French`, `Hedge Fund Indices`: For benchmarking and risk modeling

---

## 🚀 Example Use Cases

- Assist sales teams with pitch-ready talking points
- Help analysts summarize performance without manual effort
- Deliver personalized insights to high-net-worth clients

---

## 🧩 Future Work

- Add Streamlit or Gradio frontend for interactive demo
- Integrate chart exports using Matplotlib or Plotly
- Expand dataset ingestion and automation via Zapier or Make.com

---

## 🧾 License

MIT License