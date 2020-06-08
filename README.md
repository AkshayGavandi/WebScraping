# WebScraping
Web Scraping worldometer website for COVID-19 analysis using Python, Selenium and Databricks

The worldometer website (https://www.worldometers.info/) provides the latest COVID-19 data.
The objective of this project is to stay on top of the information for Coronavirus by collecting latest COVID-19 dataset using web scraping method and converting it into presentable format for visualization and analysis.

## Plan
I am going to use Databricks platform to utilize databricks file system for installing drivers and Python packages, Python for collecting data and Spark SQL for cleaning and presenting data.

## Set up
Install selenium and import webdriver
Download and test Chrome driver for linux (databricks file system)

## Web scraping
Got to the website and inspect elements that contain the required data. For worldometer website, check the table element 'main_table_countries_today' and data under it.

Use find_element_by_xpath() save the table and further extract the data row by row.
