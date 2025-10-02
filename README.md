# eBay Scraper

A robust eBay scraper built with Selenium. Handles dynamic content, pagination, and stale elements, extracting item titles, prices, and links. Results are saved to a CSV file. Includes headless mode, random delays, and duplicate filtering for reliable automated scraping.

## Features

- Scrapes eBay search results by keyword

- Handles pagination and dynamic content loading

- Manages stale elements to prevent errors

- Filters items above a specified price cap

- Stores results as a CSV file

- Headless browser mode supported

- Random delays to mimic human browsing

- Duplicate results automatically removed

## Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/ebay-scraper.git
cd ebay-scraper
```
2. Install dependencies:
```
pip install selenium colorama
```
## Usage

1. Run the script:
```
python main.py
```
2. Input the required information when prompted:

- Search keyword

- Number of pages to scrape

- Price cap

- Headless mode (y/n)

The results will be saved in results.csv in the project folder.

