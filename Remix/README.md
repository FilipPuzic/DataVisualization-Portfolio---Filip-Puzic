# Recreate and Remix

## Final Visualization  
![alt text](<Recreation of SPY.png>)

![alt text](<SPY 200EMA.png>)

## Data Sources  
- Historical S&P 500 data downloaded from [Yahoo Finance](https://finance.yahoo.com/)  
- Original candlestick chart taken from [TradingView](https://www.tradingview.com/)

## Tools Used  
- Python (`pandas`, `plotly`)  
- Jupyter Notebook  
- **ChatGPT** & **Copilot** (for coding assistance)

## Project Description  
This project is part of the **Recreate and Remix** initiative in my data science portfolio. The goal was to take an existing financial visualization and both recreate and enhance it with additional analytical features.

### What?
I selected a candlestick chart of the S&P 500 index originally published on TradingView. I recreated the chart using Python and Plotly, then built a customized remix version.

### Why?
Candlestick charts are fundamental tools in technical analysis. They help traders identify price trends and potential reversals. By remixing the original chart, I aimed to improve visual clarity and add analytical tools for deeper insights.

### How?

#### Recreation
I used static, downloaded historical data from Yahoo Finance to recreate the original candlestick chart. Due to using static data, I could not include:

- *Real-time Bid/Ask prices*
- *Real-time volume*
- *Countdown to market close*

These features require a live data API feed.

#### Remix Enhancements
- **Background Change** – Switched to a black theme for improved contrast and readability.
- **200-Day Moving Average** – Added a long-term trendline to identify broader trends.
- **Bollinger Bands** – Used as a volatility indicator for potential overbought/oversold signals.
- **OHLC Tooltip** – Enabled hover tooltips to display Open, High, Low, and Close prices for each candle.
- **Interactive Features** – Zoom, pan, and click-to-inspect features included via Plotly.

## Features Summary (Markdown Highlights)
- *Background contrast improved for visibility*  
- **Added technical indicators for deeper analysis**  
- **Enabled hover tooltips and interactivity**

