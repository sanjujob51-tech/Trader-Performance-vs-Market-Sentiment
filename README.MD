# 📊 Trader Performance vs Market Sentiment Analysis

## Overview

This project analyzes the relationship between Bitcoin Market Sentiment (Fear & Greed Index) and Hyperliquid trader performance. The objective is to identify how market sentiment influences trader behavior, profitability, trading frequency, and overall trading performance.

This project was completed as part of the Primetrade.ai Data Science Intern Round-0 Assignment.

---

# Project Objectives

- Analyze trader performance across different market sentiment conditions.
- Compare Fear vs Greed market behavior.
- Measure profitability, trading frequency, and win rate.
- Identify different trader segments.
- Generate actionable trading recommendations.

## Key Visualizations

### Long vs Short Trades
![Long vs Short](Long%20vs%20short.png)

### Average Profit/Loss
![Average Profit](Average%20profit%20loss.png)

### Total Trades
![Total Trades](total%20trades.png)
---

# Datasets

### 1. Bitcoin Market Sentiment
- Date
- Classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)

## Dataset
The datasets used in this project were provided as part of the Primetrade.ai Round-0 assignment.
Due to file size constraints and repository size optimization, the datasets are not included in this repository.
Please use the original assignment datasets to run the notebook.

### 2. Hyperliquid Historical Trader Data
- Account
- Symbol
- Side
- Closed PnL
- Size
- Fee
- Trade Time
- Execution Price

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

# Methodology

The project was completed using the following workflow:

1. Data Loading
2. Data Cleaning
3. Data Preparation
4. Dataset Merging
5. Feature Engineering
6. Exploratory Data Analysis (EDA)
7. Sentiment Analysis
8. Trader Segmentation
9. Business Insights
10. Strategy Recommendations

---

# Key Metrics

- Daily Trader PnL
- Win Rate
- Average Trade Size
- Number of Trades
- Long vs Short Ratio
- Trade Frequency
- Trader Segmentation

---

# Key Findings

- Fear sentiment recorded the highest trading activity.
- Extreme Greed produced the highest average profitability.
- Trading activity varied significantly across market sentiment conditions.
- High Activity traders generally generated better performance.
- Market sentiment influences both trader behavior and profitability.

---

# Strategy Recommendations

- Reduce trading risk during Extreme Fear conditions.
- Increase trading opportunities during favorable bullish conditions while maintaining proper risk management.
- Monitor trader performance using activity and profitability metrics.
- Use market sentiment as an additional decision-making indicator.

---

# Dataset Limitations

- The provided dataset did not include leverage information; therefore, leverage-based analysis could not be performed.
- Results are based only on the provided historical trading dataset.

---

# Repository Structure

```
Trader-Performance-vs-Market-Sentiment/
│
├── Trader_Performance_Analysis.ipynb
├── README.md
├── requirements.txt
├── historical_data.csv
├── fear_greed_index.csv
└── images/
```

---

# How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Upload both datasets.
5. Run all cells sequentially.

---

# Future Improvements

- Develop an interactive Power BI dashboard.
- Build a Streamlit application.
- Apply Machine Learning models for trader profitability prediction.
- Perform real-time sentiment analysis using live market data.

---

# Author

**Sanju Singh**

Data Analytics Enthusiast
