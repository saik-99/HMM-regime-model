# Financial Regime Detection with HMM, HSMM, and MS-VAR

This repository provides a complete framework for **financial regime analysis** using probabilistic time series models.  
It includes implementations of:
- **Hidden Markov Models (HMM)**
- **Hidden Semi-Markov Models (HSMM)**
- **Markov-Switching Vector Autoregression (MS-VAR)**

These models are applied to **synthetic data** and **real financial market data** (via Yahoo Finance) to detect market states such as bull, bear, and sideways regimes.

---

## 🚀 Features

- **HMM & HSMM Frameworks**  
  Detect hidden regimes in financial time series with Gaussian emissions and duration modeling.
- **MS-VAR Model**  
  Multivariate regime-switching VAR for cross-asset dynamics.
- **Yahoo Finance Integration**  
  Automatic data loading for tickers like AAPL, MSFT, TSLA, SPY, etc.
- **Financial Analysis Tools**  
  Calculates Sharpe ratios, volatility, mean returns, and duration per regime.
- **Trading Strategy Backtest**  
  Compare buy-and-hold vs regime-aware strategies.
- **Performance Benchmarking**  
  Measures computational efficiency of HMM vs HSMM.
- **Visualization Suite**  
  Regime plots, volatility heatmaps, and transition matrices.

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/financial-regime-detection.git
cd financial-regime-detection
pip install -r requirements.txt

🧩 Project Structure
financial-regime-detection/
│
├── untitled13.py              # Main project script (Colab-exported)
│   ├── BasicHMM               # Hidden Markov Model implementation
│   ├── HiddenSemiMarkovModel  # HSMM with duration modeling
│   ├── MSVARModel             # Markov Switching VAR
│   ├── StockMSVAR             # Multivariate stock regime analysis
│   ├── test_hsmm_on_stock_data()
│   ├── test_msvar_synthetic()
│   └── trading_strategy_backtest()
│
├── requirements.txt
└── README.md
