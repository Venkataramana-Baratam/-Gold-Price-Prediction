# 🪙 Gold Price Prediction

This machine learning project aims to predict the price of gold based on various global financial indicators. It utilizes regression models to forecast future gold prices using historical data.

---

## 📌 Project Summary

This project includes:

- Data loading and exploratory data analysis (EDA)
- Feature correlation analysis using a heatmap
- Feature selection and scaling
- Model training using **Random Forest Regressor**
- Performance evaluation using regression metrics

---

## 📂 Files

- `Gold_Price_Prediction.ipynb` — Jupyter notebook with the complete code and analysis.
- `README.md` — Project overview and instructions.

---

## 📊 Dataset Info

- The dataset includes historical values of:
  - SPX (S&P 500)
  - USO (Crude oil prices)
  - SLV (Silver prices)
  - EUR/USD exchange rate
  - Gold price (target)

These features are used to predict the gold price.

---

## 📈 Model Used

### ✅ Random Forest Regressor
- Handles non-linearity and feature importance well
- Trained on selected financial indicators
- Model evaluation using metrics like R² score

---

## 📉 Evaluation Metrics

- **R² Score** — Measures the proportion of variance explained
- **Predicted vs Actual** visualization

---

## 📊 Visualization Highlights

- Correlation heatmap to understand feature relationships
- Line plot comparing actual vs predicted gold prices

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn` (RandomForestRegressor, train_test_split, metrics)

---

## ✅ Conclusion

The Random Forest model provides a reasonable estimation of gold prices based on macroeconomic and financial indicators. With more tuning and data, this approach could support real-world financial forecasting.

---

## 🚀 Future Work

- Hyperparameter tuning for better model performance
- Try other regressors like XGBoost or LSTM
- Deploy using Streamlit or Flask

---

## 📌 Author

**Venkataramana Baratam**

---
