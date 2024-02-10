# Arsenal ETL Database Design Project using Python & SQL
### An ETL design project using Python to extract and SQL to store team and players information for Arsenal Football Club.

## Situation
As an aspiring Data Analyst, I decided to work on an ETL project on my favourite sport team, Arsenal Football Club to gain hands-on experience in Webscraping and Database Management.. The aim of this project was to gather/extract data from various websites through webscraping, then clean and write SQL queries to load players and team data into my database. Now with the accesible data, I can track the team and players performance, and build visuals to draw valuable insights and comparison between past and current players. 

## Task
The goal of this ETL project is to use Python and SQL to create a database that stores data collected and updated on a week-to-week basis from various websites via webscraping, clean and aggregate the data and load the data into SQL database, then write queries to gain valuable insights, analysis and build visualization in Tableau.
Tables extracted: 

## Action
The following libraries and tools were used to achieve the ETL Process:

### WEBSCRAPING
The main way of collecting the data was through web scraping from various sports websites. To achieve this, I worked solely with Python and applied the following webscraping techniques and tools below:
1. Selenium - Selenium creates a seperate web driver and then scraped based on different elements. 
2. Requests - Requests makes HTTP requests to the website APIs, then we fetch the HTML contents needed.
3. Pandas - Use Pandas read_html, for most tabluar data on a website.
4. BeautifulSoup - BeautifulSoup was used for parsing HTML documents.

### DATA CLEANING 
This process involved cleaning of  raw scraped data by using various string methods and filtering out for suitable data.
 <br/>
A major tool also used was the Python Pandas library. Pandas - Convert raw data into tabular dataframe, rename columns to meet database naming standards and save tables as a csv file. <br/>
Here's a sample function used to scrape one of our multiple data.
<br/>
![Alt Text](https://github.com/Lekan-E/Arsenal-ETL-Design/blob/main/Miscell/League%20Table%20Function.png)

### DATABASE MANAGEMENT
1. MySQL
Here is a sample query where I use CTEs to create a table from multiple tables in SQL: 
<br/>
![Alt Text](https://github.com/Lekan-E/Arsenal-ETL-Design/blob/main/Miscell/CTEs.png)

### DATA VISUALIZATION
1. Tableau

## Result

## Reflection

Webscrping Methods

Tools for cleaning

website scraped from