# YouTube Video Scraper

This project uses **Selenium** and **BeautifulSoup** to scrape video details from a YouTube channel. The script automates a browser session to retrieve video information such as titles, views, and upload dates.

## Project Overview
- **Uses Selenium to load dynamic YouTube content**
- **Parses HTML using BeautifulSoup**
- **Extracts video details like title, views, and upload date**
- **Stores the data for further analysis**

## Technologies Used
- **Python**
- **Selenium** (for automating browser interaction)
- **BeautifulSoup** (for parsing HTML content)
- **Chromedriver** (for Selenium WebDriver)

## Installation
Ensure you have Python installed, then install the required dependencies:

```sh
pip install selenium beautifulsoup4 chromedriver_binary
```

## Usage
Run the Python script or Jupyter Notebook to scrape YouTube video details.

Example snippet:
```python
from selenium import webdriver
from selenium.webdriver.chrome.service import Service
from bs4 import BeautifulSoup
import chromedriver_binary

service = Service(executable_path='chromedriver.exe')
browser = webdriver.Chrome(service=service)
browser.get('https://www.youtube.com/@GeeksforGeeksPractice/videos')
```

## Output
The extracted video details can be stored in a structured format for further analysis.

## Conclusion
This project demonstrates how to scrape dynamic web content using Selenium and BeautifulSoup. It serves as a foundation for more advanced web scraping tasks, such as tracking video metrics over time.


