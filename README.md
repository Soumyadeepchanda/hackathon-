# 📈 AI-Powered Stock Recommendation LLM (Agentic Model)

This project is an **Agentic Large Language Model (LLM)** built using **Ollama** that provides intelligent **stock investment recommendations** based on company data, sector performance, and **6-month historical trends**.  

It uses **agentic reasoning** and **context-aware decision-making** to determine whether a user should **Invest**, **Hold**, or **Avoid** a stock — all by analyzing recent performance and market sentiment.

---

## 🚀 Overview

Unlike traditional models that rely solely on historical averages, this system dynamically assesses:
- The **company's performance** over the past 6 months  
- The **sector’s momentum**  
- **Market sentiment and risk stability**  

The result?  
A contextual, explainable, and data-driven recommendation powered by **AI reasoning**.

---

## 🧠 How It Works

1. User provides a **company name** and **sector**.  
2. The **Agentic Model** uses **Ollama LLM** to understand context and extract relevant insights.  
3. The system analyzes **6-month historical stock data**.  
4. The LLM outputs a recommendation:
   - ✅ **Invest** — Stock and sector showing strong growth  
   - ⚖️ **Hold** — Mixed or stable trends  
   - ❌ **Avoid** — Declining performance or weak sector outlook  

---

## 🧩 Key Features

- 🤖 **Agentic LLM reasoning** for smarter recommendations  
- 🕒 **6-month market trend analysis**  
- 💹 **Sector-based comparison** for deeper financial context  
- 🧠 **Ollama-powered local LLM** — works without cloud APIs  
- ⚙️ **Fully modular architecture** for data, reasoning, and recommendations  

---

## ⚙️ Tech Stack

- **Language Model:** Ollama (LLM backend)  
- **Framework:** Python  
- **Libraries:**  
  - `yfinance` → Stock data extraction  
  - `pandas`, `numpy` → Data cleaning and analysis  
  - `langchain` / `llama-index` → Agent orchestration  
  - `matplotlib` (optional) → Visualizations  

---
