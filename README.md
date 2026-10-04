# Youssef EL OUARDIGHI

Finance and data, in Paris. MSc International Finance at Paris School of Business (since September 2025), MSc Artificial Intelligence & Data Science from Bahçeşehir University (2021 to 2023). Looking for an end-of-studies internship in Paris.

I build small tools where finance meets machine learning, and I try to make each one say when it does not know.

## Experience

- Financial management and reporting assistant, Fiduciaire Générale de Tanger (wealth management), November 2025 to August 2026.
- Data Analyst BI, D&A Technologies, Casablanca, May 2024 to July 2025 (14 months, internship then fixed-term contract).

## Selected work

**Quant Portfolio Platform** (private, demo on request). End-to-end pipeline on an S&P 500 universe: screening, LLM-assisted fundamental research (BUY / HOLD / SELL with a confidence score), and portfolio optimization with four methods (Black-Litterman, Risk Parity, Min-CVaR, discrete share allocation). The research output feeds the Black-Litterman views directly, with no manual input. Streamlit dashboard, French and English.

**Annual Report Analyst** (private, built with AI assistance). Reads annual report PDFs and extracts key indicators (revenue, operating income, net income, net debt, margins) with the source page cited. Each figure is read twice by two different methods and cross-checked. When they disagree, the tool shows both values instead of publishing one as fact. It abstains when the information is absent. Tested on 4 public annual reports from 3 companies with 90 tests, including hallucination and abstention cases. No success rate is claimed: the rules were adjusted after the first failures and no blind test remains. Known limits: no OCR, one source text for both reads, and the second read depends on an LLM.

**Equity Research Copilot** (private). Web app for equity research across US, European, Asian and African markets: fundamental ratios, news sentiment and a structured research note, with a FastAPI and LLM pipeline.

**[autonomous-ai-agent](https://github.com/YoussElo/autonomous-ai-agent)**. A tool-use agent in about 450 lines of Python. A separate verifier call, which sees only the task and the trace of actions, decides whether the task is done. Tools are confined to one folder, every call is logged append-only, and the tests run without an API key. Small and early: one commit, tests cover the demo mode only.

**[AI-Finance-Portfolio](https://github.com/YoussElo/AI-Finance-Portfolio)**. Coursework and research notebooks, including card fraud detection (XGBoost with SMOTE, AUC-ROC 0.98).

**MSc capstone** (in progress). Credit default prediction: machine learning models against logistic regression, framed by Basel and SR 11-7.

## Tools

Python (pandas, NumPy, scikit-learn, XGBoost, PyTorch, FastAPI), R, SQL, Jupyter, Power BI, Tableau, Bloomberg Terminal.

## Contact

[LinkedIn](https://linkedin.com/in/youssef-el-ouardighi) · youssef.elouardighi@outlook.fr · French and Arabic native, English C1.
