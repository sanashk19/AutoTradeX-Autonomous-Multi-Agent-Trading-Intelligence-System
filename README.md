<div align="center">
  <h1>🧠 AutoTradeX</h1>
  <p><strong>Autonomous Multi-Agent Trading Intelligence System</strong></p>

  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/LLMs-8A2BE2?style=for-the-badge&logo=openai&logoColor=white" alt="LLMs" />
  <img src="https://img.shields.io/badge/Binance_API-FCD535?style=for-the-badge&logo=binance&logoColor=black" alt="Binance" />
</div>

<br />

## 📖 About The Project

AutoTradeX is a fully autonomous multi-agent trading intelligence system that designs, validates, backtests, optimizes, and explains trading strategies using a coordinated team of specialized AI agents. The system automates the complete quantitative trading lifecycle—from strategy generation to final deployment insight—while remaining fully explainable and human-readable.

### ✨ Key Capabilities
* **End-to-End Automation:** Compresses a workflow that typically takes days into seconds by eliminating manual strategy coding and trial-and-error backtesting.
* **LLM-Augmented Validation:** Utilizes strict structural schema validation and Gemini-powered semantic analysis to ensure only logically safe strategies proceed.
* **Advanced Optimization:** Applies Genetic Algorithm optimization to adapt strategies across different market regimes.
* **Real-Time Execution:** Built-in support for live market execution via Binance WebSockets.
* **Explainable AI:** Transforms raw quantitative metrics into human-readable trading reports and clear deployment recommendations.

---

## 🤖 The Multi-Agent Architecture

AutoTradeX is built as a modular agent ecosystem, where each agent performs one clearly defined role:

1. **Agent-1 (Strategy Generator):** Generates strictly formatted trading strategies (like SMA crossovers and RSI) based on market condition snapshots and risk profiles.
2. **Agent-2 (Validator & Semantic Auditor):** Performs structural validation, indicator normalization, and auto-corrects missing defaults to ensure statistical validity.
3. **Agent-3 (Backtesting & Execution):** Handles historical OHLCV backtesting, Genetic Algorithm optimization, and real-time Binance WebSocket trading.
4. **Agent-4 (Signal Scanner):** Processes outputs to extract clean numerical performance metrics like drawdown, return, and final equity.
5. **Agent-5 (Insight Engine):** Converts raw quant outputs into decision-ready intelligence, generating profitability summaries and risk classifications.

---

## 💻 Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Data & Markets:** `yfinance` (Market Fetching Engine), Binance WebSockets
* **AI & Logic:** LLMs (Gemini), Genetic Algorithms, Multi-Agent Coordination

---

## 🚀 Getting Started

To run the multi-agent pipeline locally:

### 1. Clone the Repository
```bash
git clone [https://github.com/sanashk19/AutoTradeX.git](https://github.com/sanashk19/AutoTradeX.git)
cd AutoTradeX
```
### 2. Install Dependencies
```Bash
pip install -r requirements.txt
```
### 3. Launch the Notebook
Open AutoTradeX_Main.ipynb in Jupyter Notebook or VS Code and run the cells sequentially to trigger the end-to-end pipeline flow.

### 📸 Pipeline Execution Preview
Note to self: Drop a screenshot of a generated strategy report, an equity curve graph, or the agent logs here!

### 📫 Contact
Sana Shaikh - sanashk019@gmail.com
