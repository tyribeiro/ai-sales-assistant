# 📊 Executive Summary: AI Sales Assistant for Investment Firms

## 1. Project Overview & Business Purpose

The **AI Sales Assistant for Investment Firms** is a real-world portfolio project that demonstrates expert-level prompt engineering using OpenAI technologies. Designed for financial analysts, sales teams, and advisors, this solution transforms raw portfolio data into professional, pitch-ready insights using AI-generated summaries, risk analyses, and strategy recommendations.

The goal is to automate the translation of complex asset performance data into easy-to-understand, visually enhanced business intelligence that helps sales and advisory teams make data-driven decisions faster and with more confidence.

---

## 2. Prompt Summaries

### 🧠 Prompt 1: Portfolio Performance Summary

**📌 Goal**: Identify the top-performing and underperforming assets, rank them by return, and summarize portfolio trends.

**🧾 Final Prompt Structure**:
- System Role: `You are a senior portfolio strategist and OpenAI financial insights model.`
- Instructions:
  1. Calculate average monthly return
  2. Rank assets
  3. Flag high volatility or negative return
  4. Return markdown summary + 150-word executive paragraph

**📤 Outcome**:
- Top performers: `World Equities`, `Commodities`, `Real Estate`
- High volatility: `Commodities`, `Real Estate`
- Clear, slide-ready paragraph generated for presentation use

---

### ⚠️ Prompt 2: Risk Trend Analysis

**📌 Goal**: Classify asset classes by risk level and detect major drawdown months.

**🧾 Final Prompt Structure**:
- System Role: `You are a risk analytics specialist trained on hedge fund strategies.`
- Instructions:
  1. Detect drawdown spikes
  2. Classify assets as Low, Moderate, High risk
  3. Link risk patterns to regimes
  4. Return markdown table + client-facing insights

**📤 Outcome**:
- All numeric assets classified as Low Risk
- Max drawdown periods identified
- Strategic advisor paragraph and summary insights created

---

### 🧠 Prompt 3: Strategy Recommendations

**📌 Goal**: Generate two actionable, slide-ready strategies based on data trends.

**🧾 Final Prompt Structure**:
- System Role: `You are a financial sales strategist generating pitch-ready recommendations.`
- Instructions:
  1. Identify two opportunities
  2. Create bold headlines + short rationale
  3. Add advisor-friendly talking points
  4. Return markdown-formatted strategies

**📤 Outcome**:
- Strategy 1: **Capitalize on Global Equity Strength**
- Strategy 2: **Reassess Risk in Real Assets**

---

## 3. Key Insights

- **Performance**: Global Equities and Commodities are leading the portfolio with consistent returns.
- **Volatility**: Real assets like Real Estate are profitable but show higher risk—suggesting timing or trimming exposure.
- **Risk**: All measured assets were classified as Low Risk based on historical volatility.
- **Strategy**: Sales teams can reframe these findings into actionable investment positioning, boosting client confidence and differentiation.

---

## 4. Business Value

This AI-powered assistant enhances productivity for:
- **Sales teams** by generating ready-to-use investment narratives
- **Advisors** by offering data-backed talking points
- **Executives** by delivering insights faster and with consistency across teams

It enables financial professionals to reduce analysis time, improve client communication, and make real-time data actionable with minimal human input.

---

## 5. Visuals

### 📈 Average Monthly Returns  
[![Average Returns](../charts/avg_returns.png)](https://github.com/tyribeiro/ai-sales-assistant/blob/6d2e9c1d60f3780071becc895bee865f72187941/ai-sales-assistant/avg_returns.png)

---

### 📉 Volatility by Asset  
[![Volatility](../charts/volatility.png)](https://github.com/tyribeiro/ai-sales-assistant/blob/6d2e9c1d60f3780071becc895bee865f72187941/ai-sales-assistant/volatility.png)

---

### 📊 Risk Level Distribution  
[![Risk Level](../charts/risk_level_distribution.png)](https://github.com/tyribeiro/ai-sales-assistant/blob/6d2e9c1d60f3780071becc895bee865f72187941/ai-sales-assistant/risk_level_distribution.png)

---

### 📉 Max Drawdown Month by Asset  
[![Drawdowns](../charts/drawdown_months.png)
](https://github.com/tyribeiro/ai-sales-assistant/blob/6d2e9c1d60f3780071becc895bee865f72187941/ai-sales-assistant/drawdown_months.png)
---

## 6. Conclusion

The **AI Sales Assistant** transforms how investment professionals interact with portfolio data. With OpenAI prompt engineering at its core, this solution showcases the real-world business impact of generative AI — from risk insight to pitch delivery — and positions itself as a next-generation co-pilot for advisory and sales success.
