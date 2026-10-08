# Trader Performance vs Market Sentiment Analysis

> **Portfolio focus:** Python • Behavioral Analytics • Financial Data • Exploratory Analysis

## Business Problem

Trader behavior can change with market sentiment. Understanding whether trading activity, risk-taking and profitability vary across sentiment regimes can help analysts identify behavioral patterns.

## Objective

Study the relationship between trader behavior/performance and the Fear & Greed Index by aligning market sentiment with historical trading data.

## Data

Two sources are documented in the original project:

1. Fear & Greed Index dataset
2. Historical trading dataset from Hyperliquid

## Data Preparation

The project documents the following workflow:

- Convert timestamps to datetime
- Align both datasets at daily level
- Handle missing values and duplicates
- Merge datasets using the date field

## Key Metrics

- Daily PnL per trader
- Win rate
- Trade frequency
- Average trade size
- Long/Short ratio
- Trader segmentation, including Frequent, Infrequent and Winners

## Analysis

The notebook compares trader performance and behavior across Fear and Greed periods, including:

- Performance by sentiment regime
- Behavioral changes in trading patterns
- Trader segmentation by activity and profitability

## Key Insights

The current project README documents three findings:

1. Traders take higher risks during Greed periods.
2. Overtrading reduces profitability.
3. Market sentiment influences trade direction significantly.

## Strategy Recommendations

1. Review leverage/risk exposure during Fear periods.
2. Avoid unnecessary overtrading during Greed phases.
3. Monitor sentiment regime shifts alongside trader activity and directional behavior.

## Results

The analysis connects daily market sentiment with trader-level behavior and performance indicators, producing a behavioral analytics view rather than a standalone sentiment chart.

## Project Structure

```text
trader-sentiment-analysis/
├── Notebook.ipynb
├── fear_greed_index.csv
├── SHORT WRITE-UP.txt
├── ReadMe.md
└── README.md
```

## How to Run

1. Open `Notebook.ipynb`.
2. Install the required Python libraries used by the notebook, including Pandas, Matplotlib and Seaborn.
3. Ensure `fear_greed_index.csv` is available in the notebook's expected path.
4. Run the notebook cells sequentially.

## Portfolio Takeaway

This project demonstrates data alignment, feature creation, segmentation and business interpretation — useful skills for Data Analyst and Business Analyst roles where behavior and performance need to be analyzed together.
