# 🚀 Mars Data Scraping Assignment

This repository contains the completed assignment for Module 11 of the University of Toronto Data Analytics Bootcamp. The assignment focuses on practicing web scraping using Python, BeautifulSoup, and Splinter. The tasks involve extracting data from Mars-related web pages and analyzing the results.

## 📁 Assignment Components

### Part 1: Mars News Scraping
- Used Splinter and BeautifulSoup to automate browsing of the NASA Mars News website.
- Extracted the most recent article titles and preview text.
- Stored the results in a list of dictionaries.
- Included optional functionality to export the scraped data to a JSON file.

### Part 2: Mars Weather Data
- Scraped daily Mars weather data from a static HTML table.
- Converted the data into a Pandas DataFrame with correctly typed columns.
- Performed analysis to:
  - Count Martian months and the number of Sols (Martian days) observed.
  - Determine the coldest and warmest months based on average minimum temperature.
  - Identify months with the lowest and highest atmospheric pressure.
  - Estimate the number of terrestrial (Earth) days in a Martian year using temperature cycles.
- Exported the final DataFrame to a CSV file.
- Created supporting bar and line charts using Matplotlib.

## 📦 Tools and Libraries Used
- Python
- BeautifulSoup
- Splinter
- Pandas
- Matplotlib
- Jupyter Notebook

## 📝 How to Run the Notebooks
1. Clone or download this repository.
2. Install required libraries if not already installed:
   ```bash
   pip install splinter beautifulsoup4 pandas matplotlib
3. Launch Jupyter Notebook and open:
   ```bash
   part_1_mars_news.ipynb for the news scraping task.
   
   part_2_mars_weather.ipynb for the weather data scraping and analysis.