# MarketSentiments_-_TraderPerformance
📊 Bitcoin Market Sentiment vs Trader Performance Analysis
This project explores the relationship between Bitcoin market sentiment (Fear vs Greed) and trader performance on the Hyperliquid exchange.

🔍 Objective
The primary goal is to uncover actionable insights by analyzing how different market sentiments influence trading behavior and outcomes. By combining sentiment data with real historical trading activity, we aim to inform smarter trading strategies based on behavioral trends.

🗂️ Datasets Used
Bitcoin Market Sentiment Dataset

Source: Alternative.me Fear & Greed Index

Columns: date, value (0–100), classification (Fear/Greed)

Historical Trader Data (Hyperliquid)

Columns include: Account, Coin, Execution Price, Size USD, Side, Closed PnL, Timestamp IST, etc.

⚙️ Key Analyses
📈 Market Sentiment Trends:
Visualizing historical Fear & Greed levels and identifying macro patterns in trader psychology.

💹 Trader Behavior Analysis:
Measuring PnL distribution, trade volume, and side (long/short) performance.

📊 Performance by Sentiment:
Aggregating and comparing trader PnL during Fear vs Greed market phases.

🔁 Moving Averages & Patterns:
Tracking sentiment momentum using rolling averages to correlate with trader profitability.

💡 Insights
Does trader PnL improve during Greed or Fear?

Are long or short strategies more profitable in certain sentiment phases?

Can sentiment predict shifts in trading volume or risk appetite?

📁 Files
historical_data.csv – Raw trader transactions

fear_greed_index.csv – Market sentiment data

trader_analysis.ipynb – Jupyter Notebook for trader analysis

sentiment_analysis.ipynb – Jupyter Notebook for sentiment trends

merged_insights.ipynb – Combined analysis (PnL vs sentiment)

🚀 Future Improvements
Incorporate real-time sentiment API

Use machine learning for PnL prediction

Deploy interactive dashboard (e.g., with Plotly or Streamlit)
