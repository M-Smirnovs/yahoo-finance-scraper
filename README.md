# NVIDIA Stock Price Scraper

A Python script that scrapes real-time NVIDIA (NVDA) stock data from Yahoo Finance. The tool extracts current stock price and daily price changes using BeautifulSoup4.

## Features
- Fetches current NVIDIA stock price
- Tracks daily price changes
- Handles HTTP request errors
- Uses BeautifulSoup4 for HTML parsing

## Requirements
- Python 3.x
- BeautifulSoup4
- Requests

## Usage
```python
result = scrape_nvidia_stock()
print(result)  # Returns dictionary with price and daily change
```

This tool is designed for educational purposes and demonstrates basic web scraping techniques with Python.
