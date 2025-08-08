# Trader Behavior vs. Market Sentiment 📊

This project explores how **market sentiment** (Fear/Greed Index) affects **trader behavior and performance** using real historical data from Hyperliquid and Bitcoin's Fear-Greed index.

## 🔍 Objective

To uncover hidden behavioral patterns and performance trends in different market sentiment phases, ultimately enabling smarter crypto trading strategies.

---

## 📁 Dataset Sources

- **Hyperliquid Trader Data**: Real trading records including execution price, direction, size, PnL, etc.
- **Bitcoin Fear-Greed Index**: Daily sentiment classification (Fear, Greed, Neutral, etc.)

---

## 🧠 Key Insights

- 📈 **Greed periods** had the highest win rate (42%) and total PnL — traders performed better here.
- 😨 **Fear periods** saw larger trade sizes but slightly lower win rates.
- 😐 **Neutral periods** had the lowest performance metrics.
- ❗ **Sentiment-aware trading** may improve profitability and risk management.

---

## 📊 Visualizations

- Bar plots: Total PnL, Win Rate, and Avg Trade Size by sentiment
- Boxplot: Distribution of PnL under each sentiment
- Aggregated tables showing performance trends

---

## ⚙️ Tools Used

- Python, pandas, seaborn, matplotlib
- Google Colab
- GitHub

---

## 📊 Key Insights & Strategy Suggestions

- **Traders perform better during Greed sentiment**, with higher average PnL and win rate.
- **Fear periods are more volatile**, with lower win rate and higher average fees.
- **Strategy Recommendations:**
  - Reduce position size and risk during Fear.
  - Trade more confidently in Greed periods.
  - Avoid overtrading in Neutral phases to minimize fees.
  - Be cautious with trades where sentiment data is missing or unknown.

---

## 🧪 How to Run

1. Open the [notebook file](./sentiment_analysis.ipynb)
2. Run all cells (data already merged)
3. See EDA, charts, and insights at the bottom

---

## 👤 Author

- **Rithish H R**
- GitHub: https://github.com/rithishhr
