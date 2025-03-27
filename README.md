# Data-Analysis-Portfolio
## About ##

Hello, I'm Cindy! I have a background in Audit-Accounting and currently, I am on track to completing my Certificate in Data Analytics at University of California, Irvine. I have developed a strong foundation in Financial Audits in the financial services industry and a passion for using data to uncover meaningful insights. I am excited to bring my technical and analytical skills to the field of data science as an entry-level data analyst.

In the past 6 months, I have dedicated time to expanding my expertise in data analytics where I am strengthening my skills in Python, SQL, data modeling, and data visualization (Tableau/Power BI). I am particularly interested in leveraging these skills to enhance data-driven insights in asset management, risk modeling, and financial performance analysis.

Please see "" for my resume

LinkedIn Profile: 

This is a repository to showcase skills and share projects in Data Analytics / Data Science related topics.

## Table of Contents ##

- [About](#About)


## Portfolio of Challenge Assignments ##
This section lists all of my completed data analytics projects. 

### Analyzing Stock Data Using VBA Coding in Excel
Git Repo: [Stock-Analysis-VBA-coding](https://github.com/cindawwgg/Stock-Analysis-VBA-coding/tree/main)

Description:
This assignment analyzes quarterly stock data to find stocks with the greatest increase/decrease and the greatest volume traded for the quarter.

Language:
Excel - VBA

### General Analysis of a Bank's Monthly Profit or Loss
Git Repo: [Bank Python](https://github.com/cindyd97/Bank-Poll-Python/tree/main)

Description: The assignment entails creating a Python script to analyze the financial records of a company. It includes a financial dataset with Date and Profit/Losses information. The Python script analyzes the records to calculate the total number of months included, the net total amount of "Profit/Losses" over the entire period, the average change in "Profit/Losses" over the entire period, the greatest increase and decrease in profits over the entire period.

Language:
Python

### General Analysis of a Town's Poll Data
Git Repo: [Poll Python](https://github.com/cindyd97/Bank-Poll-Python/tree/main)

Description: This part of the assignment includes a Python script that analyzes poll data of a state. It includes a dataset with the County as well as the candidates' names. The script calculates the total number of votes as well as the amount of votes per candidate and their percentage of votes relative to the total number of votes. The script also includes a for loop that finds the winner.

Language:
Python

### Analyzing the City's School District
Git Repo: [Analyzing School Data Using Pandas-Python](https://github.com/cindyd97/Analyzing_School_Data-Pandas-Python)

Description: This assignment creates a Python script, using the Pandas library, that performs calculations to summarize key metrics about each school including the following: school name, school type, total students, total school budget, per student budget, average math score, average reading score, percentage of students who passed math, percentage of students who passed reading, and percentage of students who pass math and reading. Dataframes are created to show the top 5 rows of the highest performing schools by % of Overall Passing and the lowest performing schools by % of Overall Passing. Dataframes are created to also list the average math score and average reading score for students of each grade level at each school. Other analyses include creating a table that breaks down school performance based on average spending ranges per student.

Language:
Pandas - Python

### Comparing the Performance of Pharmaceutical Drugs
Git Repo: [Comparing Pharma Drug Performance Using Matplotlib-Python](https://github.com/cindyd97/Comparing_Pharma_Drug_Performance)

Description: The script prepares the data by importing the datasets and merging them into a single Dataframe to display the unique mice IDs. The next step includes cleaning the dataframe by removing duplicate mice IDs. A summary statistic is generated that includes a row for each drug regimen as well as a column that displays: mean, median, variance, standard deviation, and SEM of the tumor volume. Bar charts are created where one is created using pandas and the other is created using pyplot. Pie charts are created where one is created using pandas and the other is created using pyplot. The analysis also includes finding any outliers using a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. A single mouse was selected that was treated with Capomulin to track the tumor volume over time using a line chart. For the same mouse, a scatter plot was generated to observe the mouse's weight vs. average observed tumor volume. A linear regression model is created based on the scatter plot to calculate the correlation coefficient.

Language:
Matplotlib and Python

### Weather Analysis and Vacation Recommendations
Git Repo: [Weather Analysis Vacation Recommendations Python & API](https://github.com/cindyd97/Weather_Analysis_Python-API/tree/main)

Weather Description: This assignment involves creating a python script to visualize the weather of 500 cities of varying distances from the equator. The code utilizes the citipy library and data using an API call. A list of cities is created using latitude and longitude coordinates and an API call is made on the weather data for each city. The data information for each city includes: max temperature, humidity, cloudiness, wind speed, country, and date. The city data is saved to a CSV file. The code includes visualizing the data in scatter plots for both the northern and southern hemispheres to view: latitude vs. temperature, latitude vs. humidity, latitude vs. cloudiness, and latitude vs. windspeed. Then a linear regression is computed for each scatter plot to understand the r-squared value and slope/formula of the linear regression model.

Vacation Recommendation Description: This part of the assignment utilizes the city data that was saved to a CSV file in the first part of this assignment. A visual map is created that plots each city in the city dataset and sizes the plots based on humidity. The city data is filtered with parameters specifying ideal weather conditions for humidity, cloudiness, and windspeed. An API call is used to retrieve the nearest resort based on the ideal weather conditions of the filtered data set using the city name and coordinates. Another visual map is created that plots the resorts based on ideal weather conditions showcasing recommended vacation spots to visit.

Language:
Python and API calls

### Employment Data Analysis With SQL
Git Repo: [Analyzing Employment Data Using SQL](https://github.com/cindyd97/Employment-Data-Analysis-with-SQL/tree/main)

Description: 
- Step 1 Data Modeling: An Entity Relationship Diagram is created using QuickDBD to display the relationship of the data tables based on primary and foreign keys found in each table. The diagram links 6 tables based on department ID, employee ID, or title ID.
- Step 2 Data Engineering: Table schemas are created for each of the 6 CSV files where datatypes, primary keys, foreign keys, and other constraints are specified. Then, each CSV file is imported into the corresponding SQL table
- Step 3 Data Analysis: This part of the assignment involves joining tables to view employee data based on demographic and salary information. Other steps include filtering employee data based on hire date, listing employees based on department or other internal information to the company, finding employees based on the beginning initial of their name, and finding employees based on a specified department. The code also involves performing frequency counts in descending order for all employees.

Language:
SQL (PostgreSQL in pgAdmin)

### Climate Analysis with SQLAlchemy and Flask API
Git Repo: [Climate Analysis Using SQLAlchemy and FLask API](https://github.com/cindyd97/Climate-Analysis-Using-SQLAlchemy-Flask-API)

Description: A basic climate analysis and data exploration of the climate database is performed using SQLAlchemy ORM queries, Pandas, and Matplotlib. The code connects to an SQLite database and reflects the tables into classes that are saved to variables. Then, links python to the database by creating a session. The code uses precipitation data to plot precipitation over a period of time. The code also uses temperature data to plot the frequency of temperature as a histogram. A Flask API is designed that includes a homepage and available routes. The first route will display the precipitation graph, the next route will display a JSON list of all stations, and the third route will display the temperature graph. The last route will display minimum temperature, average temperature, and maximum temperature for a specified start or start-end range.

Language:
Python, SQLAlchemy, and Flaskk API

### Webscraping Mars Data With Beautiful Soup
Git Repo: [Webscraping Mars Data with Beautiful Soup](https://github.com/cindyd97/Webscraping-Mars-Data-Beautiful-Soup)

Description: The first part of the assignment utilizes beautiful soup to extract the title and preview text from the elements of the HTML of a website that holds information about Mars. The second part of the assignment extracts Mars data and puts it into a data frame. Certain columns of the data frame are converted to floats and integers for analysis purposes. Bar charts and line graphs are created to display the month with the lowest average temperature, the month with the lowest average atmospheric temperature, and how many terrestrial days exist in a Martian year.

Language:
Python with Beautiful Soup

### Analyzing Restaurant Data Using MongoDB/Pymongo
Git Repo: [Analyzing Restaurant Data with MongoDB](https://github.com/cindyd97/Analyzing_Restaurant_Data_MongoDB)

Description: 
- The first part of this assignment involves importing the JSON file into the MongoDB database and using pymongo to connect to the database through python. Other steps involve reading the data, updating the data with new information, and deleting specific rows. Certain fields were also converted to integers.
- The second part of this assignment entails finding out how many restaurants received a hygiene score of 20. The code also finds all restaurants in London with a rating of 4 or more. The analysis also finds the top 5 establishments with a rating value of 5 sorted by lowest to highest hygiene score that is nearest to the newly added restaurant. Lastly, the code retrieves a list of establishments with a hygiene score of 0.

Language:
MQL (NoSQL) and Python with Pymongo

### Exploring Belly Button Biodiversity with Javascript and HTML
Git Repo: [Exploring Belly Button Biodiversity with Javascript and HTML](https://github.com/cindyd97/Exploring_Bellybutton_Biodiversity_with_Javascript_and_HTML)

Description:
This JavaScript code is used to build a data visualization dashboard that displays metadata and charts related to biological samples. It utilizes the D3.js library for data manipulation and Plotly.js for creating interactive charts. This code creates an interactive dashboard that allows users to select different biological samples from a dropdown menu and see corresponding metadata and visualizations (Bubble and Bar charts) based on the selected sample.
This HTML code represents a complete structure for a web page that serves as a dashboard for exploring a dataset related to Belly Button Biodiversity. It includes interactive elements that allow users to select different samples and view corresponding demographic information and visualizations.

Language:
Javascript and HTML

###




