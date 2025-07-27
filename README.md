# Sentiment-Driven Trader Behavior Analysis

This project analyzes how trader behavior — including profitability and trading volume — aligns with Bitcoin market sentiment using the Fear & Greed Index and Hyperliquid trader data.

---

## 📁 Project Structure

ds_<your_name>/
├── notebook_1.ipynb
├── csv_files/
│ ├── historical_data.csv
│ ├── fear_greed_index.csv
│ └── merged_data.csv
├── outputs/
│ ├── pnl_distribution.png
│ ├── avg_pnl_by_sentiment.png
│ └── volume_by_sentiment.png
├── ds_report.pdf
└── README.md


---

## ⚙️ How to Run

1. Open `notebook_1.ipynb` in Google Colab.
2. Ensure your `csv_files/` folder contains the two datasets.
3. Run the notebook cells to reproduce the plots and insights.

---

## 📈 Summary of Insights

- Higher trade volume and profitability observed during Greed periods.
- Most trades have neutral or small PnL.
- Traders react actively to sentiment shifts, especially during Greed.

---

## 📌 Notes

- Dataset did not contain leverage/margin data.
- All results are based on available fields: `closed_pnl`, `size_usd`, `classification`, etc.

