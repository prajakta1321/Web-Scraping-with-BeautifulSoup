# Web-Scraping-with-BeautifulSoup
A collection of web scraping projects utilizing Python's BeautifulSoup library to extract and analyze data from various websites.

# Web Scraping with BeautifulSoup

## Description
This repository contains a series of web scraping projects that utilize Python's BeautifulSoup library to extract data from web pages. It serves as a practical guide to understanding web scraping techniques and best practices.

## Projects Included
1. **Basic Web Scraper:** Scrapes quotes from [Quotes to Scrape](http://quotes.toscrape.com/).
- Initially, we used the Quotes to Scrape website for practicing web scraping. It’s designed specifically for this purpose and provides a simple and accessible way to extract quotes along with their authors without violating scraping policies.
  
2. **Wikipedia Scraper:** Extracts article titles and introductions from Wikipedia's homepage.
- This project demonstrates how to scrape data from Wikipedia using Python's BeautifulSoup library. The scraper extracts article titles and introductory paragraphs from the Wikipedia homepage, showcasing basic web scraping techniques.

Key Features
Fetches the HTML content of a specified Wikipedia page.
Parses the content to extract titles and introductory sections.
Prints the results in a clear format for easy reading.

## Libraries Used
- `requests`: For sending HTTP requests.
- `beautifulsoup4`: For parsing HTML.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/web-scraping-with-beautifulsoup.git

## Navigate to the project directory:
cd web-scraping-with-beautifulsoup

## Install the required libraries:
pip install requests beautifulsoup4

## Run the scrapers:
python webscraper.py  # Replace with the specific script you want to run.
