# Trader Behavior vs Market Sentiment Analysis

## Objective
Analyze how Bitcoin market sentiment (Fear & Greed Index) impacts trader performance and behavior using historical trading data from Hyperliquid.

## Datasets
- Hyperliquid historical trader data
- Bitcoin Fear & Greed Index

## Key Questions
- Does market sentiment affect trader profitability?
- How does trader behavior differ during greedy vs fearful markets?
- What distinguishes top-performing traders from others?

## Methodology
1. Data cleaning and schema normalization  
2. Memory-safe aggregation of sentiment data to daily frequency  
3. Feature engineering (PnL, win rate, trade value, trader segmentation)  
4. Sentiment regime classification (Fear / Greed)  
5. Performance comparison across trader groups  
6. Visualization and insight extraction  

## Key Findings
- The dataset overlaps with a market window dominated by the “Greed” sentiment regime.
- Top 5% traders achieve nearly **6x higher average profit** despite lower win rates.
- Profitability is driven more by **risk–reward management** than by frequency of winning trades.
- Retail traders win more often but with significantly smaller profits.
- Market sentiment can be used as a **risk filter** and position sizing signal.

## Limitations
The available trader data overlaps with a limited time window during which the Fear & Greed Index remained around 50 (Greed regime). Therefore, multi-regime comparison is constrained by data availability.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Author
Harshith Valaboju
