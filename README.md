
**Primetrade.AI**

Bitcoin market Sentiment vs Trader Performance – Data Science Project  

**Author: Kalyani Telu
**Date: September 2025  

**Project Overview:

This project explores the relationship between **market sentiment** and **trader performance** using two primary datasets:

1. **Bitcoin Market Sentiment Dataset**  
   - Columns: `Date`, `Classification` (`Fear` or `Greed`)

2. **Historical Trader Data from Hyperliquid**  
   - Columns: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.

The goal is to uncover **patterns, correlations, and potential insights** that can drive **smarter trading strategies** — particularly under different emotional states of the market (Fear vs. Greed).

---

## 🧠 Objectives

- Understand how trader behavior and performance vary during market **Fear** and **Greed** phases
- Analyze trading metrics like `PnL`, `position size`, `leverage`, and `side` across sentiment phases
- Visualize performance patterns over time
- Recommend strategies or flags for high-risk behavior based on sentiment

## 📁 Repository Structure

ds_kalyani
├── notebook_1.ipynb # Main Google Colab notebook with full workflow
├── csv_files/ # Data files (raw, cleaned, joined, etc.)
│ └── fear_greed_index (sentiment_data).csv
│ historical_data.csv
├── outputs/ # Graphs and chart outputs
│── ds_report.pdf # Final report summarizing methods and insights
└── README.md # This file

## 🔧 How to Run This Project

1. Open `notebook_1.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Upload CSV files from the `csv_files/` directory when prompted
3. Run the notebook step-by-step:
   - Data loading & cleaning
   - Merging sentiment and trading datasets
   - Exploratory Data Analysis (EDA)
   - Visualizations
   - Insights
4. Visual outputs will be saved in the `outputs/` directory
5. Final insights are available in `ds_report.pdf`

## 🛠️ Tools & Libraries Used

- `pandas` – Data manipulation
- `numpy` – Numerical analysis
- `matplotlib`, `seaborn` – Visualizations
- `datetime` – Time-based feature engineering

## 📊 Insights

- Traders using high leverage tend to incur larger losses during "Fear" sentiment phases
- Overall PnL volatility increases in "Greed" and Extreme Greed markets
- Short positions rise during peak Fear, but do not always lead to higher profits
- A contrarian strategy (buying during fear, selling during greed) may be profitable — though risk is also higher
- Traders appear to use less leverage during extreme sentiment, likely to reduce exposure
- Higher volumes during emotional markets (Fear and Greed) suggest more opportunities — but with increased risk

*(See `ds_report.pdf` for full details.)*

## 📬 Contact

Kalyani Telu

kalyani.telu05@gmail.com

https://github.com/Kalyani-Moram