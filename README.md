#  Trader Behavior & Sentiment Analysis

##  Project Overview
This project analyzes how market sentiment (Fear vs Greed) influences trader behavior and performance using real trading data from Hyperliquid.

The objective is to uncover patterns in trading decisions and identify strategies for improved profitability.


## Datasets Used
1. **Bitcoin Fear & Greed Index**
   - Date, Classification (Fear/Greed)

2. **Historical Trader Data**
   - Account, Price, Size, Side, PnL, Timestamp, etc.


## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook



##  Data Preparation
- Loaded and cleaned both datasets
- Handled missing values and duplicates
- Converted timestamps to date format
- Merged datasets based on date



##  Key Metrics Created
- Daily PnL per trader
- Average trade size
- Trade frequency
- Win rate
- Trader segmentation (High vs Low profit)



##  Analysis Performed
- Profitability vs market sentiment
- Trading activity across sentiment phases
- Buy/Sell behavior patterns
- Segment-wise performance analysis



##  Key Insights
- High-profit traders perform better during **Fear** conditions
- Low-profit traders are more active during **Greed** phases
- Extreme Fear conditions show lower profitability and higher risk
- Market sentiment strongly influences trader decision-making



##  Strategy Recommendations
- Apply **contrarian strategy**: trade during Fear, avoid Greed-driven decisions
- Reduce trading activity in Extreme Fear conditions
- Focus on disciplined, data-driven trading rather than emotional reactions



##  Future Improvements
- Build predictive model for trader profitability
- Cluster traders into behavioral groups
- Develop real-time trading dashboard



##  Author
Swapnil Datir