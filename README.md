# Web Scraping Project

## Overview

This project is a web scraping application built with Python that allows users to scrape product data from Amazon and Flipkart based on a specified category and the number of pages to scrape. The collected data is stored in CSV files and can be sorted or visualized through histograms. The application provides an interactive command-line interface for users to filter and analyze the data.

## Technologies Used

- Python
- Pandas
- Beautiful Soup (bs4)
- Requests
- Matplotlib
- CSV

## Features

- Scrapes product data from Amazon and Flipkart based on user-defined category and number of pages.
- Stores scraped data in two separate CSV files: one for Amazon and one for Flipkart.
- Provides options to sort data based on:
  - Review count
  - Price
  - Rating
- Generates histograms of prices for the selected platform (Amazon, Flipkart, or both).

## Installation

To run this project, ensure you have Python installed on your machine. Then, install the required packages using pip:

```bash
pip install pandas beautifulsoup4 requests matplotlib
