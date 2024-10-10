# Espn_web_scrapping_ipl
This repository contains csv files and code to scrap the batting and bowling averages of ipl teams

This repository contains a Python-based web scraping tool that extracts Indian Premier League (IPL) player statistics, specifically batting and bowling averages, from ESPN Cricinfo. It utilizes `Playwright` for navigating through dynamically loaded content and `BeautifulSoup` for parsing the HTML content.

Scrapes player statistics (batting and bowling averages) for all IPL teams.
- Uses `Playwright` for dynamic content loading.
- HTML content parsing is handled using `BeautifulSoup`.
- Extracts relevant data (team, player names, stats) and saves it into lists/dictionaries for further processing.

Dependencies

Playwright: Automates Chromium-based browsers for scraping dynamic content.
BeautifulSoup: Used to parse the HTML and extract relevant data.
pandas: To handle tabular data (optional but recommended for saving and analyzing data).
