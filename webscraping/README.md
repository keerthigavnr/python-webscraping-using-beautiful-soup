# WebScrapper

This Python script,scrapes job postings from websites based on specific skills and saves relevant information to text files.

## Description

This project utilizes Python along with BeautifulSoup and Requests libraries to extract job listings from the website. It enables the user to specify a skill they are not familiar with and filters out job postings that require that skill. The filtered job information is then saved into separate text files for further review.

## Prerequisites

Before running this script, make sure to install the required Python libraries:

    -BeautifulSoup: 'pip install beautifulsoup4'
    -lxml parser: 'pip install lxml'
    -Requests: 'pip install requests'
    
## Folder Structure

- `webscraper.py`: Contains the main script for scraping job postings.
- `posts/`: Directory where scraped job information is saved in text files.
  
## Project Purpose

This project was created as a learning opportunity for web scraping using Python. It's aimed at understanding the basics of web scraping, using BeautifulSoup for parsing HTML content, and saving scraped data.
