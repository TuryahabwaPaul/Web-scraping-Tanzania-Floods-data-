# Flood Data Scraping Project

This project involves scraping flood-related articles from FloodList, specifically focusing on events in Tanzania. The data is collected from multiple pages of the website and stored in a structured format using Python.

## Project Overview

This repository contains a Python script that performs the following tasks:

1. **Web Scraping:** 
   - Send GET requests to web pages on FloodList to gather flood-related articles for Tanzania.
   - Mimic browser requests using custom headers to avoid potential blocking by the server.
   - Parse the HTML content using `BeautifulSoup` to extract the title and date of each article.
   - Iterate through multiple pages to gather all available data.

2. **Data Processing:**
   - Extract titles and dates of flood-related articles from the scraped content.
   - Store the extracted data in Python lists for further processing.

3. **Data Export:**
   - Convert the extracted data into a pandas DataFrame.
   - Export the DataFrame to both CSV and Excel files (`floodlist_data.csv` and `floodlist_data.xlsx`).

## Requirements

To run this script, you need the following Python libraries installed:

- `requests`: For making HTTP requests.
- `beautifulsoup4`: For parsing HTML content.
- `pandas`: For handling data and exporting it to CSV and Excel files.
  
You can install the required libraries by running:

```bash
pip install requests beautifulsoup4 pandas
