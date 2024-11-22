# Algorithmic Trading Models 📈

This repository contains a collection of trading models designed to identify profitable opportunities in the market. These models are based on various strategies such as volatility, trend-following, and correlation analysis, and are tailored for markets like SET50.

## 📊 Available Models

### 1. **VIX-Based Models** 📉

**What it does:**  
The model uses feature engineering to calculate the **VIX index**, which measures market volatility. It sets upper and lower bounds for the VIX and applies machine learning to predict sell signals based on changes in market volatility.

**Performance:**  
Achieved an annual return of 6.76% with a max drawdown of -28.52%.

---

### 2. **Trend-Following Model** 📈

**What it does:**  
Identifies market trends (bullish or bearish) and provides signals for entering long or short positions based on the detected trend.

---

### 3. **Correlation Model (TFEX SET50)** 🔗

**What it does:**  
Specifically designed for the **TFEX SET50**, this model identifies opportunities based on the correlation between the **SET50 Index** and **SET50 Futures**.

**Performance (YTD):**  
Achieved a return of 14.16% with a max drawdown of 4.92% on **S50Z2024**.

---

### Credits

This project was created and maintained by [agehcx](https://github.com/agehcx).