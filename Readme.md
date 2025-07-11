CodeAlpha Task 1 — Titanic Dataset Web Scraping

This project is part of the CodeAlpha Data Analytics Internship.  
It demonstrates web scraping using Python to collect real Titanic passenger data, save it as a dataset, and create a simple HTML report.

Scraping Goals
- Use Python (`Requests`, `BeautifulSoup`) to scrape Titanic passenger data from Wikipedia
- Parse the HTML structure to build a structured dataset
- Save the scraped data to a CSV file for further analysis (EDA & visualization)
- Generate a clean HTML report to showcase the data clearly

Source Details
- Source Website: [Passengers of the RMS Titanic — Wikipedia](https://en.wikipedia.org/wiki/Passengers_of_the_RMS_Titanic)
- Description: Contains names, ages, passenger class, fate, and notes for Titanic passengers.
- Tools Used: Python, Requests, BeautifulSoup, Pandas

Key Outputs & Insights
Raw Data Extraction 
- Successfully scraped the full passenger table directly from Wikipedia  
- Saved the clean dataset as `titanic_passengers_scraped.csv`
HTML Report
- Converted the scraped data to a styled HTML table
- Saved as `titanic_report.html` 
