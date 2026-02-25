# CFM-Group-Project | Model-Driven Portfolio Optimization
**Quantitative asset selection and risk analysis for modern portfolios.**

## 🛠 What We Made
A quantitative, model-driven investment portfolio designed to systematically outperform market benchmarks.
* **Modern Portfolio Theory (MPT):** Applied mean-variance optimization to determine efficient asset weights.
* **Performance Alpha:** Successfully outperformed the market benchmark by **~5% over a five-day testing window** through rigorous backtesting.
* **Stack:** Jupyter Notebooks, Python (Pandas/NumPy), and financial datasets (CSV).

## 🎯 Why We Made It
This was the cornerstone project for **CFM 101** at the University of Waterloo. The goal was to move beyond gut-feeling investing and build a rigorous, data-driven framework. We wanted to see if we could use computational finance techniques to identify alpha in real-market tickers.

## 🧠 What We Originally Thought
We originally thought that picking high-performing stocks was the key to victory. We focused on finding "winners" and assumed the math would simply confirm our choices.

## 📉 What Actually Happened
* **The Weighting Reality:** We realized that **asset weighting** and **covariance** (how stocks move together) were far more important than the individual stocks themselves. 
* **Risk Exposure:** Initial versions of our model were over-leveraged in specific sectors. We had to implement stricter risk constraints to ensure the portfolio didn't collapse during a sector-specific dip.
* **Data Cleaning:** Real financial data is messy. A large portion of our "quant" time was actually spent cleaning and normalizing CSV data to ensure our matrix calculations were accurate.

## 💡 What We Took Away
1. **Math > Intuition:** In finance, systemic models consistently beat emotional stock picking.
2. **Diversification is the Only Free Lunch:** Managing the correlation between assets is the most effective way to protect a portfolio.
3. **CFM Synergy:** This project was my first real experience seeing how **Computer Science** (data processing/modeling) serves as the engine for **Finance** (capital allocation/risk management).
