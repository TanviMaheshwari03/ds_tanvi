# 📊 Web3 Trader Behavior & Sentiment Analysis

This project analyzes how trader behaviors (profitability, volume, risk) align or diverge from market sentiment phases (Fear vs Greed) using real-world Web3 datasets.

---

## 📁 Directory Structure

ds_Tanvi/
├── notebook_1.ipynb # EDA + Preprocessing
├── notebook_2.ipynb # Analysis + Clustering
├── csv_files/ # Original + merged datasets
├── outputs/ # All graphs and visual outputs
├── ds_report.pdf # Final summary of insights
└── README.md # This file
---

## 📌 Datasets Used

1. **Bitcoin Market Sentiment Index**  
   - Columns: `Date`, `Classification` (Fear / Greed)

2. **Hyperliquid Trader History**  
   - Columns: `size_usd`, `closed_pnl`, `direction`, `timestamp`, etc.

---

## 📈 Key Insights

- Greed phases saw higher trade sizes but more volatile PnL outcomes.
- KMeans clustering identified 3 distinct trading behaviors regardless of sentiment.
- Trader actions often diverge from prevailing market mood — revealing hidden inefficiencies.

---

## 📦 Deliverables

- 📓 All code in **Google Colab**, publicly viewable.
- 📊 All visuals saved under `outputs/`.
- 📝 Report includes:
  - Correlation matrix
  - Aggregation summaries
  - PCA-clustered behavior plots
  - Sentiment-cluster mapping

---

## 🚀 How to Reproduce

1. Clone the repo or download the `.zip`
2. Open `notebook_1.ipynb` in [Google Colab](https://colab.research.google.com/)
3. Run all cells in order to generate datasets
4. Continue with `notebook_2.ipynb` for insights

---

## 🔗 Colab Links

- [`notebook_1.ipynb`](https://colab.research.google.com/drive/1LItIgDNmJTcnfw12OP2PPGiWUnYDg5Ct#scrollTo=BV7QnILQK3SE)
- [`notebook_2.ipynb`](https://colab.research.google.com/drive/1zJDQzLb5OQbunlLSV40gnzFBjy4jVkWM#scrollTo=r0eQguP-rAqS)

> Set both notebooks to “Anyone with the link can view”

---

## 🧠 Author

**Tanvi Kansat**  
Business Analyst Intern @ Markytics.ai | AI & Web3 Enthusiast  
[LinkedIn](https://linkedin.com/in/your-profile) • [GitHub](https://github.com/TanviMaheshwari03)

---

## 🏁 Notes

- File paths are relative, so notebooks work seamlessly in Colab or locally.
- Please run notebook_1 first to generate the merged dataset.

