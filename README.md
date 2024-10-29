## Reddit Web Scraper
This project is a web scraping tool developed to extract information from Reddit's best communities. Using BeautifulSoup and Requests, it scrapes multiple pages to gather data on subreddits, categories, subscriber counts, and links, and organizes the results in a structured dataset saved as an Excel file.

## Project Overview
The web scraper retrieves and compiles the following information from Reddit's community pages:

### Subreddits: The names of trending subreddits
### Categories: Associated categories or topics for each subreddit
### Subscribers: Number of subscribers in each subreddit
### Links: Direct links to each subreddit page

The final dataset is stored in an Excel file, Scraped_Data.xlsx, for easy viewing and analysis.

### Python: The core language for the project

### Libraries and Modules Used :-

### BeautifulSoup: For HTML parsing and data extraction
### Requests: For HTTP requests to access web pages
### Pandas: For data handling, transformation, and exporting to Excel

## How It Works

### Scraping: The script iterates over multiple pages of Reddit's best communities and collects the required information.
### Data Extraction: Data is organized into lists by scraping subreddit names, categories, subscriber counts, and links.
### Data Export: The data is combined into a single DataFrame and saved as an Excel file for further use.


The script will output an Scraped_Data.xlsx file in the project directory.

Functions in the Script
### enter_url(url): Sends a request to the URL and returns the parsed HTML.
### Subreddits(soup): Scrapes and returns subreddit names.
### Category(soup): Scrapes and returns subreddit categories.
### hrefs(soup): Scrapes and returns subreddit links.
### Subscribers(soup): Scrapes and returns subscriber counts.

### Output
The final output is an Excel file, Scraped_Data.xlsx, containing the following columns:
Subreddits
Category
Subscribers
Links
