# CodeAlpha Web Scraping Project

This project scrapes book data from books.toscrape.com using Python, BeautifulSoup, and pandas.

## What it does
- Extracts book titles, prices, and star ratings across 50 pages (1000 books total)
- Cleans the data (fixes currency symbols, converts ratings to numeric values)
- Saves the final dataset as a CSV file for further analysis

## Tools used
- Python
- Requests
- BeautifulSoup
- Pandas

## Files
- `web_scraping_books.ipynb` — the scraping script and code
- `books_dataset.csv` — raw scraped data
- `books_dataset_clean.csv` — cleaned dataset
