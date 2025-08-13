# gq-implied-volatility-forecasting
Time-series forecasting model predicting Ethereum's 10-second-ahead implied volatility using high-frequency order-book and cross-asset market data. Includes data cleaning, feature engineering, model training (LightGBM), and walk-forward validation for Kaggle competition submission.

# GQ Implied Volatility Forecasting

Forecasting Ethereum's 10-second-ahead implied volatility using high-frequency order-book and cross-asset market data.  
Developed as part of the [Kaggle Competition](https://www.kaggle.com/competitions/gq-implied-volatility-forecasting).

---

## 📌 Overview
This project builds a **time-series forecasting pipeline** to predict ETH implied volatility (IV) at t+10 seconds.  
Key steps:
- Data cleaning and preprocessing (missing timestamps, outliers).
- Feature engineering:
  - Order-book imbalance.
  - Rolling realized volatility.
  - Cross-asset returns.
- Model training using **LightGBM**.
- Rigorous walk-forward validation to avoid data leakage.
- Submission evaluation using **Pearson Correlation Coefficient**.

---

## 🛠 Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, LightGBM, Scikit-learn  
- **Platform:** Kaggle  

---

## 📂 Contents
- `notebook.ipynb` – Complete workflow (EDA → feature engineering → model training → validation → submission).  
- `README.md` – Project documentation.

---

## 📊 Results
- Achieved a high **Pearson correlation** score on the hidden private leaderboard.
- Designed a reproducible, competition-compliant pipeline.

---

## 📬 Contact
**Nishant Prasad**  
📧 [nishant10prasad10@gmail.com](mailto:nishant10prasad10@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/nishant-prasad-a58456283/) | [GitHub](https://github.com/nishant270)
