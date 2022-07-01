
# Stock Chart Analyzer with Dash

## Introduction
This project intends to recreate stock charting platforms using Python, specifically with the use of [Plotly Dash](https://dash.plotly.com/). The dashboard involves a simple time series candlestick chart embedded with trading indicators such as Bollinger Bands, RSI, MACD, and Moving Average.  


## Requirements

1. Create a virtual environment running on Python 3.6
```
conda create --name your_env_name python=3.6
```
2. Activate virtual environment
```
conda activate your_env_name
```
3. Install dependencies
```
pip install -r requirements.txt
```
4. Run on your local computer
```
python stock_charter.py
```
5. If the application does not load automatically, copy the local link on your web browser
```
http://127.0.0.1:8000/
```

## Demo

User gets to choose stock ticker from the dropdown, press `PLOT` then the app will load the stock chart on the right and a table that includes summary statistics about the ticker. 

![](https://github.com/neooooo28/stock-analyzer/blob/main/assets/demo_chart.png)

## Credits
1. Live and historical stock data is from [Yahoo! Finance](https://pypi.org/project/yfinance/). 
2. Frontend inspiration on Plotly and CSS come from a tutorial by [STATWORX Blog by Alexander Blaufuss](https://www.statworx.com/en/blog/how-to-build-a-dashboard-in-python-plotly-dash-step-by-step-tutorial/)
