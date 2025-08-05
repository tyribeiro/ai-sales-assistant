# Prompt Engineering Evolution: From V1 to Expert-Level

This document shows how we evolved the core prompts used in the AI Sales Assistant project, upgrading them from basic natural language to structured, professional-grade prompt engineering.

---

## 🔹 Prompt 1: Portfolio Performance Summary

**Version 1 (V1):**
> "Summarize the portfolio performance across all asset classes. Focus on best/worst performers and trends. Return 3 bullet points and a paragraph."

**Problems:**
- Too vague: No rules on how to rank assets
- No formatting guidance
- No instruction on calculating returns
- Not reusable or extensible

**Version 2 (Expert):**
- Adds system prompt (role = senior strategist)
- Gives 4 exact instructions (avg return, ranking, volatility filter, output format)
- Uses markdown output
- Slide-ready, structured format

---

## 🔹 Prompt 2: Risk Trend Detection

**Version 1 (V1):**
> "Analyze for risk trends over time. Focus on volatility, risky assets, regime impact. Give 3 insights and actions."

**Problems:**
- No method of identifying high risk
- No data structure expectations
- No client-facing language constraints
- Weak actionability

**Version 2 (Expert):**
- Defines volatility threshold (e.g., 1.5× std dev)
- Requires table: Risk Level, Drawdown Month
- Adds advisor-specific phrasing
- Encourages slide reuse and risk classification

---

## 🔹 Prompt 3: Strategy Generator

**Version 1 (V1):**
> "Give 2 strategy recommendations from the portfolio history. Include title and paragraph."

**Problems:**
- Not sales-specific
- No formatting or constraints
- Doesn't reflect financial pitch tone
- No optional context for advisor

**Version 2 (Expert):**
- Bold slide title + short explanation + optional advisor tip
- Structured markdown with headers
- Includes callout to make it client-ready

---

## 🧠 Lessons

- Define **role + tone**: “You are a financial strategist”
- Provide **format examples**: JSON, markdown, tables
- Add **clear constraints**: word count, output length, flags
- Make it **reusable** for pipelines or UIs

This evolution proves mastery of prompt architecture for business-grade applications.