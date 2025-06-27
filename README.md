# 📊 RegimeRadar — Week 2: Feature Engineering

This notebook is part of the **RegimeRadar project** aimed at detecting financial market regimes using order book data.

## ✅ Week 2 Goals
- Extract financial features from `depth20` data
- Compute indicators for liquidity, volatility, and order book imbalance
- Prepare normalized features for clustering in Week 3

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `Week2.ipynb` | Main Jupyter notebook containing data loading, feature engineering, and visualizations |
| `features_week2.zip` | Zipped CSV of the final engineered features |

---

## 🛠 Features Engineered

- **Spread**: Ask Price L1 - Bid Price L1  
- **Mid-Price**: (Ask + Bid) / 2  
- **Order Book Imbalance (L1)**: Using Level 1 ask and bid quantities  
- **Full Depth Imbalance**: Using 20 levels of order book  
- **Rolling Volatility**: 20-period standard deviation of mid-price  

---

## 📊 Visualizations

- Spread over time  
- Mid-price over time  
- Order Book Imbalance (L1)  
- Rolling Volatility  

---

## 📦 Output for Week 3

- `features_week2.csv` contains the engineered features
- This will be used in clustering models in the next stage
