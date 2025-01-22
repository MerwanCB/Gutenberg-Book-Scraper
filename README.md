# Gutenberg Book Scraper

## Overview
This project involves scraping the titles and download numbers of books from the "Computers and Technology" bookshelf at the Gutenberg Open Library. The data collected is intended for educational purposes and to demonstrate the process of web scraping using Python.

## Contents
- **Scraper.ipynb**: The main Jupyter notebook containing the scraping script and data analysis.
- **bookshelf.csv**: A CSV file with the scraped data, including book titles and download numbers.
- **full_catalogue.txt**: A text file containing the complete HTML content scraped from the website.
- **combined_html_pages.txt**: A single HTML file that combines all pages scraped.

## Requirements
To run this notebook, you will need:
- Python 3.x
- Libraries: 
  - `requests`
  - `beautifulsoup4`
  - `pandas`
  - `matplotlib`
  - `seaborn`

You can install the required libraries using pip:

```bash
pip install requests beautifulsoup4 pandas matplotlib seaborn
