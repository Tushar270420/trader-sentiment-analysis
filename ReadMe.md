# Trader Performance vs Market Sentiment Analysis

## Objective

Thow 

---

## Data Sources

1. Fear & Greed Index dataset
2. Historical trading dataset from Hyperliquid

---

## Data Preparation

* Converted timestamps to datetime format
* Aligned both datasets on daily level
* Handled missing values and duplicates
* Merged datasets using date column

---

## Key Metrics Created

* Daily PnL per trader
* Win rate
* Trade frequency
* Average trade size
* Long/Short ratio
* Trader segmentation (Frequent, Infrequent, Winners)

---

## Analysis

* Compared performance across Fear and Greed periods
* Analyzed behavioral changes in trading patterns
* Segmented traders based on activity and profitability

---

## Key Insights

1. Traders take higher risks during Greed periods
2. Overtrading reduces profitability
3. Market sentiment influences trade direction significantly

---

## Strategy Recommendations

1. Reduce leverage during Fear periods
2. Avoid overtrading during Greed phases

---

## Tools Used

* Python (Pandas, Matplotlib, Seaborn)
* Google Colab

---
