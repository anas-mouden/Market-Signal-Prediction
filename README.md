# Market Signal Prediction

Exploratory data analysis and machine learning pipeline for **financial mid-price movement prediction**.  
The project builds signals from high-frequency limit order book features, applies feature reduction via **PCA**, trains multiple classifiers, and backtests trading strategies with transaction costs.

---

## 🚀 Features
- **EDA & Preprocessing**
  - 600k+ rows, 89 features  
  - PCA factor extraction, top-loading feature selection  

- **Models Implemented**
  - Random Forest (RF)  
  - Logistic Regression (multinomial)  
  - XGBoost  
  - LightGBM  
  - CatBoost  

- **Backtesting Framework**
  - Custom conditional P&L rule (buy/sell/hold)  
  - Wealth evolution from $100 initial capital  
  - Net-of-transaction-cost scenarios (0.5 bps and 5 bps)  

- **Visualization**
  - Interactive Plotly dashboards for wealth and drawdowns  
  - Dropdown filters for gross/net models  

---

## 📂 Project Structure
│
├── data/ # Raw / processed data (not included in repo)
├── notebooks/ # Jupyter notebooks for EDA & modeling
├── scripts/ # Python scripts for model training & backtesting
├── results/ # CSV outputs, wealth curves, performance metrics
├── plots/ # Static / exported plots
├── strategy_results_all_models.csv # Main comparison output
├── README.md
