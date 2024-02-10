# Arsenal ETL Database Design Project using Python & SQL
### An ETL design project using Python to extract and SQL to store team and players information for Arsenal Football Club.

## Situation
As an aspiring Data Analyst, I decided to work on an ETL project on my favourite sport team, Arsenal Football Club. The aim of this project was to gather/extract 5 seasons/years worth of data from various websites through webscraping, then clean and write SQL queries to load players and team data into my database. Now with the accesible data, draw comparison between various players, highlight notable team strengths and weaknesses, areas of improvments, and build visualizations to track the team and players performance.

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
After extracting and transforming all the required data, I wrote SQL queries to load data into the MySQL database.
This process invloved the use of JOINs and CTEs to pull data from different tables. Below is a sample query where I use CTEs to create a table from multiple tables in SQL: 
<br/>

![Alt Text](https://github.com/Lekan-E/Arsenal-ETL-Design/blob/main/Miscell/CTEs.png)


## Result
The ETL process was completed within the timeframe I had set for myself, and the new database was able to collect new data from various web sources into a single place.
The new database also provided me with the ability to run queries to answer intriguing question regarding the team and the players, build visualizations to track and monitor performance. <br/>
Quantifiable results:
* Extracted data from 5 different web sources.
* Built a database that handles incoming data with 26 individual tables.
* Build a dashboard to track and monitor performance.

## Reflection/ Improvement
Through this project, I learned the importance of designing a scalable and flexible database schema to accomodate incoming data. I also learned the importance of automating the ETL process to ensure data integrity and reduce the risk of errors of incoming data and lastly various webscraping techniques, using Python functions.

## Future improvements
If I were to do this project again, I would spend more time on data profiling and analysis to ensure that the data was properly transformed and loaded. I would also explore the use of newer ETL tools to simplify the process and improve performance. Some other improvements I could do are:

* Write a function to scrape data at give date-times throughout the season, ideally after each matchday.
* Automate the loading process of scraped data into database
* Create automated visuals after games in Tableau
* Create a webpage to search up desired information from database.


