# Bitcoin Market Sentiment Analysis

## Objective

The objective of this project is to analyze the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid historical trading data.

## Datasets Used

- Historical Trader Data
- Bitcoin Fear & Greed Index

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Data Preprocessing

- Loaded both datasets
- Converted Timestamp IST to Date format.
- Converted the sentiment dataset date column to Date format.
- Merged both datasets using the Date column.

## Analysis Performed

- Trade count by market sentiment
- Average Closed PnL
- Total Closed PnL
- Winning trades
- Losing trades
- Average trading fee
- Top profitable traders

## Key Findings

- Fear sentiment had the highest number of trades.
- Extreme Greed generated the highest average profit per trade.
- Fear produced the highest total realized profit.
- Greed had the lowest average profit.
- Winning trades were highest during Fear.
- Losing trades were highest during Greed.
- Trading fees were highest during Fear.

## Conclusion

The analysis shows that market sentiment has a significant impact on trader performance. Fear periods generated the highest overall profit due to higher trading activity, while Extreme Greed provided the highest average profit per trade. These findings suggest that market sentiment can be a valuable indicator for developing better trading strategies.