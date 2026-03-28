# 📊 Trader Behavior vs Market Sentiment Analysis

## 🔍 Objective

This project analyzes how Bitcoin market sentiment (Fear/Greed) influences trader behavior and performance on Hyperliquid.

---

## 📁 Datasets

* Bitcoin Market Sentiment (Fear/Greed Index)
* Historical Trader Data (Hyperliquid trades)

---

## ⚙️ Methodology

* Cleaned and standardized datasets (timestamps, duplicates, missing values)
* Converted timestamps and aligned both datasets at a daily level
* Merged sentiment data with trading data
* Created key metrics:

  * PnL (closed_pnl)
  * Win rate
  * Trade size (proxy for risk)
  * Trade frequency
* Performed segmentation:

  * Frequent vs Infrequent traders
  * Risk groups (based on trade size)

---

## 📊 Key Insights

* **Performance Stability:**
  Average PnL and win rates are similar across Fear and Greed periods.

* **Higher Risk in Fear:**
  PnL variability is significantly higher (~14%) during Fear periods.

* **Behavioral Shift:**
  Traders increase position sizes and show stronger long bias during Greed periods.

* **Consistency Matters:**
  Frequent traders demonstrate more stable performance compared to infrequent traders.

---

## 💡 Strategy Recommendations

1. Reduce position size during Fear periods due to higher volatility.
2. Avoid overexposure during Greed periods despite stable conditions.
3. Focus on consistent, smaller trades rather than large, high-risk positions.

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Mahesh-1304
/trader-sentiment-analysis.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirement.txt
   
   ```
3. Open notebook.ipynb in Jupyter or Google Colab
4. Run all cells

---

## 📌 Conclusion

Market sentiment does not significantly affect profitability but strongly influences trader behavior and risk exposure. Effective strategies should focus on adaptive risk management rather than sentiment-driven decisions.
