#  Quantitative Portfolio Optimization

A data science research project applying Modern Portfolio Theory (MPT) to dynamically balance a basket of high-volatility assets (Cryptocurrencies) and traditional safe-haven assets (Gold, S&P 500). 

This notebook identifies the optimal asset weights to maximize the Sharpe Ratio, prioritizing capital preservation and risk-adjusted returns over pure directional bets.

##  Core Features
* **Data Ingestion:** Automated historical market data extraction via `yfinance`.
* **Monte Carlo Simulation:** Generates 10,000 random portfolio weight combinations to plot the Markowitz Efficient Frontier.
* **Optimal Allocation:** Mathematically extracts the exact portfolio weights that yield the highest Sharpe Ratio.
* **Risk Management Benchmarking:** Compares the optimized portfolio against "Equally Weighted" and "100% Bitcoin" strategies using simulated equity curves and Maximum Drawdown metrics.

##  Tech Stack
* **Environment:** Jupyter Notebook
* **Language:** Python 3.x
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `yfinance`

## Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/dimssrmdn01/quant-research.git
cd quant-research
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn yfinance
```

### 3. Run the Notebook
Open `portfolio.ipynb` in your preferred Jupyter environment (VS Code / JupyterLab) and run the cells sequentially.
