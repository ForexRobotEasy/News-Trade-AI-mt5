# News Trade AI MT5

This is the code for the News Trade AI MT5 Expert Advisor developed by Forex Robot Easy Team. 

Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work as described in the official product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/news-trade-ai-mt5-review-advanced-forex-trading-with-ai-news-data/).

## Description

The News Trade AI MT5 Expert Advisor is designed to trade forex based on real-time news data using artificial intelligence. It uses a neural network to analyze the news data and determine trading opportunities. The expert advisor can be used for both live trading and backtesting.

## Usage

To use this expert advisor, the following libraries need to be imported:

- Trade.mqh
- Neuro.mqh
- Risk.mqh

Global variables are defined for the trade, neural network, and risk management objects.

The expert advisor contains the following functions:

### OnInit()

This function is called during the initialization of the expert advisor. It enables the WebRequest option for fetching real-time news data.

### OnDeinit(const int reason)

This function is called during the deinitialization of the expert advisor. It deinitializes the WebRequest.

### OnTick()

This function is called on each tick of the chart. It fetches real-time news data, analyzes it using the neural network, and executes buy or sell trades based on the analysis result.

### OnTester()

This function is called during backtesting. It loads historical data, analyzes it using the neural network, and executes buy or sell trades based on the analysis result.

### Helper Functions

The code also includes two helper functions:

#### GetNewsData()

This function fetches real-time news data. The implementation of this function needs to be added separately to fetch the actual news data.

#### LoadHistoricalData()

This function loads historical data for backtesting. The implementation of this function needs to be added separately to load the actual historical data.

## Disclaimer

Forex Robot Easy is not the official developer of the News Trade AI MT5 Expert Advisor. We only provide a sample code that can work as described in the official product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/news-trade-ai-mt5-review-advanced-forex-trading-with-ai-news-data/).
