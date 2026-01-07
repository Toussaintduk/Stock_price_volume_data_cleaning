# Stock Price and Volume Data Analysis

## Project Overview
This project is focused on **analyzing stock price and trading volume data**. Historical stock data is fetched using an API, cleaned, and prepared for further analysis or visualization.  

The project was completed as part of an **AfriTEC Program assignment**.

## Data Source
- **API:** Financial Modeling Prep  
- **Endpoint:** Historical Price (End of Day – Full)  
- **Documentation:** [FMP API Docs](https://site.financialmodelingprep.com/developer/docs/stable/historical-price-eod-full)
- **Data Provided:** Open, High, Low, Close prices, Volume, Change, Change %, VWAP, and Date  

## Sample Data Record
```json
{
  "symbol": "AAPL",
  "date": "2025-02-04",
  "open": 227.2,
  "high": 233.13,
  "low": 226.65,
  "close": 232.8,
  "volume": 44489128,
  "change": 5.6,
  "changePercent": 2.46479,
  "vwap": 230.86
}
