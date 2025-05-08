# Machine Learning for Market Making: An XGBoost-Based Trading Signal Framework

This repository contains the full project submitted to WEBB Traders💖, focused on developing a machine learning pipeline for generating and backtesting short-term trading signals using XGBoost. The project also benchmarks performance against Random Forest and Neural Network classifiers.
---
![image](https://github.com/user-attachments/assets/73263822-1d0d-418a-aef3-ccb774508a7c)

---

## 📁 Contents

- **Jupyter Notebooks**
  - `Indicators_XGBoost_Neural_Net.ipynb`: Feature engineering, model training, and evaluation
  - `XGBoost_Backtest.ipynb`: Signal conversion and strategy backtesting

- **Data**
  - `EURUSD_5min_sample.csv`: Sample 5-minute EUR/USD OHLCV data

- **Report**
  - `ML_FX_XGBoost_Signal_Backtest`: Final project report (LaTeX compiled)
 

---

## 🚀 Key Highlights

- ✅ Engineered features: EMA, ATR, slope, volatility thresholds, PCA
- ✅ XGBoost achieved a **9.4% return** with just **6% market exposure**
- ✅ Outperformed Random Forest and Neural Network benchmarks
- ✅ Backtested on 6 months of 5-minute EUR/USD data
- ✅ Full LaTeX report included

---

## ⚙️ Requirements

### Python (for notebooks)

```bash
pip install xgboost pandas scikit-learn matplotlib ta backtesting
