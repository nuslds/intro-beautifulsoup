# Introduction to Web Scraping with BeautifulSoup in Python

This workshop introduces how to extract information from a static HTML website with BeautifulSoup in Python. Please note that it is designed for participants with no programming experience.



## Workshop Materials

- [This GitHub Repo](https://github.com/nuslds/intro-beautifulsoup)

- [Jupyter Notebooks on Binder](https://mybinder.org/v2/gh/nuslds/intro-beautifulsoup/master/)

  

## Introduction

### 1. What is Web Scraping?

Web scraping is a process of retrieving information from web services in an automated way.

### 2. Why Web Scraping?

Web scraping saves you from the headaches of repeatedly copying or downloading data from different websites. It creates datasets for data-driven projects by simplifying and automating the process of extracting data online and transforming scrapped data into structured formats.

[Source: How Web Scraping is Transforming the World with its Applications](<https://towardsdatascience.com/https-medium-com-hiren787-patel-web-scraping-applications-a6f370d316f4>) 

### 3. What to Consider before Web Scraping

- **Terms and Conditions of the hosting sites**
  - Do make sure you read the terms and conditions of the websites carefully and understand the restrictions.
  - Some sites may have robot.txt files that disallow scraping of particular content.
  - Check if an API exists or if the data is otherwise available for download or sale.
- **The bandwidth of the hosting sites**
  - To avoid excessive burden to the hosting sites, try to limit the bandwidth use, e.g., wait a few seconds between requests and try to scrape during off-peak hours.

[Source: Web Scraping, Columbia University Mailman School of Public Health](https://www.mailman.columbia.edu/research/population-health-methods/web-scraping)



## Overview

- Part I. Jupyter Notebook & Python Warmup
- Part II. Inspecting page source & HTML elements
- Part III. Extracting Data from HTML with BeautifulSoup
- Part IV. Scraping web pages with Requests and BeautifulSoup



## Task Today

To demonstrate, we will extract quotes from  [Quotes to Scrape](http://quotes.toscrape.com/). This is a project created by Scrapinghub ([Github repo](https://github.com/scrapinghub/spidyquotes)). We will create a reusable function that scrapes quotes from the website by page numbers. The outputs will be converted into tabular format and export into CSV.

```python
# scrape quotes from page 1 to page 10
outputs = scrape_quotes(1, 10)
```

![](https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/26.PNG)



