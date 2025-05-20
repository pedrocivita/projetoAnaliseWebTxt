# Stock Analysis and News Scraper

A Python project that analyzes S&P 500 stocks by combining real-time stock data with news analysis. The project scrapes stock information and related news from Yahoo Finance, providing insights through text analysis and visualization.

## Features

- Real-time stock price fetching for S&P 500 companies
- Latest news scraping with titles and summaries
- Text analysis of news content
- Data visualization capabilities
- Automated data collection and processing

## Project Structure

- `stockAnalyser.ipynb`: Main analysis notebook for stock data and news scraping
- `LICENSE`: Project license file
- `.gitignore`: Git ignore configuration

## Requirements

The project uses the following Python packages:

- requests
- BeautifulSoup4
- pandas
- matplotlib
- re (Regular Expressions)

## Usage

1. Open `stockAnalyser.ipynb` in Jupyter Notebook
2. Run the cells to analyze any S&P 500 stock by providing its ticker symbol
3. The analysis will provide:
   - Current stock price
   - Company name
   - Latest news with titles and summaries
   - Text analysis of the news content

## Example

```python
# Analyze Apple stock (AAPL)
result = analyze_stock("AAPL", n_news=5)
```

## Contributitors

Felipe Trintim
Pedro Civita
