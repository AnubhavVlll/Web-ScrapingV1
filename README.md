# Web Scraping Wikipedia and Exporting to CSV 

## Overview
### US Largest Companies Web Scraper
This Python script scrapes data from Wikipedia's "List of largest companies in the United States by revenue" page and saves it as a CSV file. It demonstrates web scraping techniques using BeautifulSoup and data manipulation with pandas.

## Features
- Scrapes data from a Wikipedia page
- Extracts information about the largest US companies by revenue
- Saves the data in a structured CSV format

## Requirements
- Python 3.x
- BeautifulSoup4
- Requests
- Pandas


###  This script
- the content of the Wikipedia page.
- Parse the HTML to find the table containing the list of companies.
- Extract the table headers and data.
- Create a pandas DataFrame from the extracted data.
- Export the DataFrame to a CSV file located at "/../..../.../copm.csv."
- ###### Note Ensure the file path in df.to_csv is valid for your system.
