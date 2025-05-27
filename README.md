# Monte Carlo Simulation of Portfolio Risk

This project uses Monte Carlo methods to simulate the behavior of a portfolio over time under uncertain market conditions. It calculates key financial risk metrics such as expected return, volatility, and Value at Risk (VaR) using normally distributed daily returns. The simulation is implemented in Python using NumPy and Matplotlib.

## 📊 Objective

- Simulate price paths for assets using Geometric Brownian Motion
- Evaluate portfolio return distributions
- Calculate:
  - Expected return
  - Standard deviation
  - Value at Risk (VaR) at 95% and 99% confidence
  - Sharpe ratio

## ⚙️ Tools Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn

## 📁 Structure
monte-carlo-portfolio-risk/
├── src/
│ └── simulate.py
├── notebook/
│ └── analysis.ipynb
├── plots/
│ └── returns_hist.png
├── README.md
└── requirements.txt


## 🚀 How to Run

```bash
python src/simulate.py


