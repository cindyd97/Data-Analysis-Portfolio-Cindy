# Data-Analysis-Portfolio
## About ##

Hello, I'm Cindy! I have a background in Audit-Accounting and currently, I am on track to completing my Certificate in Data Analytics at University of California, Irvine. I have developed a strong foundation in Financial Audits in the financial services industry and a passion for using data to uncover meaningful insights. I am excited to bring my technical and analytical skills to the field of data science as an entry-level data analyst.

In the past 6 months, I have dedicated time to expanding my expertise in data analytics where I am strengthening my skills in Python, SQL, data modeling, and data visualization (Tableau/Power BI). I am particularly interested in leveraging these skills to enhance data-driven insights in asset management, risk modeling, and financial performance analysis.

LinkedIn Profile: 

This is a repository to showcase skills and share projects in Data Analytics / Data Science related topics.

## Portfolio of Projects ##
This section lists all of my completed data analytics projects. 

### Each Git Repo includes the data source as well as project contents (see READMe)
- [Python](#Python)
- Javascript and HTML
- Tableau
- [SQL](#SQL)
- Python (Machine Learning)
- Excel - VBA

## Python

### Analyzing the City's School District
Git Repo: [Analyzing School Data Using Pandas-Python](https://github.com/cindyd97/Analyzing_School_Data-Pandas-Python)

Description: This assignment creates a Python script, using the Pandas library, that performs calculations to summarize key metrics about each school including the following: school name, school type, total students, total school budget, per student budget, average math score, average reading score, percentage of students who passed math, percentage of students who passed reading, and percentage of students who pass math and reading. Dataframes are created to show the top 5 rows of the highest performing schools by % of Overall Passing and the lowest performing schools by % of Overall Passing. Dataframes are created to also list the average math score and average reading score for students of each grade level at each school. Other analyses include creating a table that breaks down school performance based on average spending ranges per student.

Language:
Pandas - Python

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

### Analyzing Social Media and Emotions (Group Project)
Git Repo: [Social Media and Emotions](https://github.com/cindyd97/Analyzing-Social-Media-And-Emotions)

Description:
This group project includes exploring the data on the usage of social media and emotional well-being. Social media has grown to become part of our modern day-to-day lives having an influence over various aspects of our emotional well-being. We will be analyzing demographic factors (age, gender), social media platform statistical factors (platform app, usage time, activity type), and emotional state factors (Happiness, Sadness, Anger, Anxiety, Boredom, Neutral). The group seeks to understand the relationship, if any, that may exist between these variables. This analysis will explore the dataset over platform activity and users’ emotional state, discuss our thought process of exploration, and include any conclusions found.

Language:
Python (with pathlib, pandas, matplotlib, and scipy.stats)

### Weather Analysis and Vacation Recommendations
Git Repo: [Weather Analysis Vacation Recommendations Python & API](https://github.com/cindyd97/Weather_Analysis_Python-API/tree/main)

Weather Description: This assignment involves creating a python script to visualize the weather of 500 cities of varying distances from the equator. The code utilizes the citipy library and data using an API call. A list of cities is created using latitude and longitude coordinates and an API call is made on the weather data for each city. The data information for each city includes: max temperature, humidity, cloudiness, wind speed, country, and date. The city data is saved to a CSV file. The code includes visualizing the data in scatter plots for both the northern and southern hemispheres to view: latitude vs. temperature, latitude vs. humidity, latitude vs. cloudiness, and latitude vs. windspeed. Then a linear regression is computed for each scatter plot to understand the r-squared value and slope/formula of the linear regression model.

Vacation Recommendation Description: This part of the assignment utilizes the city data that was saved to a CSV file in the first part of this assignment. A visual map is created that plots each city in the city dataset and sizes the plots based on humidity. The city data is filtered with parameters specifying ideal weather conditions for humidity, cloudiness, and windspeed. An API call is used to retrieve the nearest resort based on the ideal weather conditions of the filtered data set using the city name and coordinates. Another visual map is created that plots the resorts based on ideal weather conditions showcasing recommended vacation spots to visit.

Language:
Python and API calls

### Analyzing Restaurant Data Using MongoDB/Pymongo
Git Repo: [Analyzing Restaurant Data with MongoDB](https://github.com/cindyd97/Analyzing_Restaurant_Data_MongoDB)

Description: 
- The first part of this assignment involves importing the JSON file into the MongoDB database and using pymongo to connect to the database through python. Other steps involve reading the data, updating the data with new information, and deleting specific rows. Certain fields were also converted to integers.
- The second part of this assignment entails finding out how many restaurants received a hygiene score of 20. The code also finds all restaurants in London with a rating of 4 or more. The analysis also finds the top 5 establishments with a rating value of 5 sorted by lowest to highest hygiene score that is nearest to the newly added restaurant. Lastly, the code retrieves a list of establishments with a hygiene score of 0.

Language:
MQL (NoSQL) and Python with Pymongo

### Comparing the Performance of Pharmaceutical Drugs
Git Repo: [Comparing Pharma Drug Performance Using Matplotlib-Python](https://github.com/cindyd97/Comparing_Pharma_Drug_Performance)

Description: The script prepares the data by importing the datasets and merging them into a single Dataframe to display the unique mice IDs. The next step includes cleaning the dataframe by removing duplicate mice IDs. A summary statistic is generated that includes a row for each drug regimen as well as a column that displays: mean, median, variance, standard deviation, and SEM of the tumor volume. Bar charts are created where one is created using pandas and the other is created using pyplot. Pie charts are created where one is created using pandas and the other is created using pyplot. The analysis also includes finding any outliers using a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. A single mouse was selected that was treated with Capomulin to track the tumor volume over time using a line chart. For the same mouse, a scatter plot was generated to observe the mouse's weight vs. average observed tumor volume. A linear regression model is created based on the scatter plot to calculate the correlation coefficient.

Language:
Matplotlib and Python

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

## Javascript and HTML

### Exploring Belly Button Biodiversity with Javascript and HTML
Git Repo: [Exploring Belly Button Biodiversity with Javascript and HTML](https://github.com/cindyd97/Exploring_Bellybutton_Biodiversity_with_Javascript_and_HTML)

Description:
- This JavaScript code is used to build a data visualization dashboard that displays metadata and charts related to biological samples. It utilizes the D3.js library for data manipulation and Plotly.js for creating interactive charts. This code creates an interactive dashboard that allows users to select different biological samples from a dropdown menu and see corresponding metadata and visualizations (Bubble and Bar charts) based on the selected sample.
- This HTML code represents a complete structure for a web page that serves as a dashboard for exploring a dataset related to Belly Button Biodiversity. It includes interactive elements that allow users to select different samples and view corresponding demographic information and visualizations.

Language:
Javascript and HTML

### Visualizing Earthquakes and Tectonic Plates using Leaflet and Javascript
Git Repo: [Earthquakes and Tectonic Plates with Leaflet and Javascript](https://github.com/cindyd97/Earthquakes_Tectonic_Plates_Leaflet_Javascript)

Description:
- The javascript code uses the leaflet library to create an interactive map that displays earthquake data and tectonic plate boundaries. The earthquake data is plotted with circles and is styled based on magnitude and depth. The layer groups allow the user to toggle between viewing earthquake data or tectonic plates. The layer control adds a control to the map that allows users to switch between the base maps. An API request is made to retrieve the data. Popup markers as well as a legend are added to display the depth of the earthquakes
- The CSS code styles and enhances the visual representation of the map and its associated elements.
- The HTML structure sets up a webpage that is ready to display leaflet map, styled appropriately and with the necessary scripts to provide interactivity and functionality.

Language:
Javascript, HTML, and CSS

### Tableau

### Understanding Banking Data
Tableau Public Link:
- Tableau Public Dashboard - Loan Data

- Tableau Public Dashboard - Credit Data

Description:

### Citibike Story with Tableau
Tableau Public Link: [Tableau Public Link - Citibike Story](https://public.tableau.com/app/profile/cindy.duong2876/viz/Mod18Challenge_17406199793550/CitibikeStory?publish=yes)

Description:
With citibike data, graphs were created to portray a story on the usage of citibikes in NYC. The story focused on bike data from the spring of 2022 taking a look at peak hours, top 10 starting locations, types of members, and mapping of bike stations.

## SQL
[Back to top](#Each Git Repo includes the data source as well as project contents (see READMe))
### Employment Data Analysis With SQL
Git Repo: [Analyzing Employment Data Using SQL](https://github.com/cindyd97/Employment-Data-Analysis-with-SQL/tree/main)

Description: 
- Step 1 Data Modeling: An Entity Relationship Diagram is created using QuickDBD to display the relationship of the data tables based on primary and foreign keys found in each table. The diagram links 6 tables based on department ID, employee ID, or title ID.
- Step 2 Data Engineering: Table schemas are created for each of the 6 CSV files where datatypes, primary keys, foreign keys, and other constraints are specified. Then, each CSV file is imported into the corresponding SQL table
- Step 3 Data Analysis: This part of the assignment involves joining tables to view employee data based on demographic and salary information. Other steps include filtering employee data based on hire date, listing employees based on department or other internal information to the company, finding employees based on the beginning initial of their name, and finding employees based on a specified department. The code also involves performing frequency counts in descending order for all employees.

Language:
SQL (PostgreSQL in pgAdmin)

### Extracting, Transforming, and Loading Crowdfunding Data (Group Project)
Git Repo: [Crowdfunding with ETL](https://github.com/cindyd97/Crowdfunding_with_ETL)

Description:
This project includes building an ETL pipeline using both python dictionary methods and regular expressions to extract and transform the data. Dataframes with unique IDs are created from the CSV files to upload to Postgres where the table schemas can be merged with the unique IDs.

Language:
- Python (with numpy and pandas)
- SQL

## Python (Machine Learning)
[Back to top](#Each Git Repo includes the data source as well as project contents (see READMe))
### Credit Score and Loan Prediction (Group Project)
Git Repo: [Credit Score and Loan Prediction](https://github.com/cindyd97/Credit-Score-Loan-Default-Prediction)

Description:
This group project involves creating a machine learning model that classifies a bank's customers based on their credit score and credit information. The group also created a machine learning model that predicts whether a client's loan application is default or not based on specific features related to their demographics, education, payment history, annual income data, etc. Banks and financial services institutions utilize credit score classification to assess a borrower's creditworthiness, enabling them to make calculated decisions about managing risk and profitability. There are 5 credit score brackets that a person can fall into, however, for simplicity purposes, our project will focus on 3 categories of credit which are Good, Standard, or Bad. Financial loan services are utilized by many companies, especially, in the financial services and banking industry. The goal of financial loan services is to mitigate the risk of default payments and ensure that clients are paying back their loans in compliance with their loan contract. Clients will either be deemed default (high risk) or not (low risk).

Language:
Python Machine learning - Neural Networks (google.colab)

### Funding with Deep Learning
Git Repo: [Funding with Deep Learning](https://github.com/cindyd97/Funding_with-Deep-Learning)

Description:
The purpose of this analysis is to create a tool that will assist a nonprofit organization in selecting applicants for funding with the best chance of success. The tool is a binary classifier that can predict an applicant’s success or not, if funded by the nonprofit organization. The label column is the column indicating if the applicant was successful or not, 'IS_SUCCESSFUL'. The remaining columns are features utilized in the model that would assist in the learning. They provide insight into the data for the model to learn how to predict new data. However, columns that serve the purpose of identification, should be removed as they don’t serve a relevant purpose in the model’s learning.

The model utilizes ‘relu’ as the activation with the first hidden layer having 8 neurons and the second layer having 5 neurons. The output layer is expected to classify 2 classes with activation using ‘sigmoid’. The model is set to binary classification using ‘adam’ as optimizer and ‘accuracy ’ as metrics. The model was able to attain an accuracy score of 1 and a loss score of 0.5544 with 100 epochs. The model started with 2 layers each having 1 neuron. Neurons were incrementally increased after each run trial to find out how many neurons were needed to attain an accuracy score of 75% or more. It was concluded that 8 neurons in the first layer and 5 neurons in the second layer were acceptable in building the model.

Language:
Python (with Tensor Flow)

### Credit Risk Classification with Supervised Machine Learning
Git Repo: https://github.com/cindyd97/Credit_Risk_Classification_Supervised-Machine-Learning/tree/main

Description:
* The purpose of this analysis is to train and evaluate certain supervised machine learning models based on the risk of loans. 
* The dataset consists of historical lending activity from a peer-to-peer lending services company. The assignment entails that the analyst build a model that can correctly predict whether a loan is healthy or high-risk based on training data. 
* The dependent variable is the `loan_status` column and the labels are either healthy loan (0) or high-risk loan (1).
* After describing the purpose and where the data is from, the process includes splitting the data for training and testing sets. Then the code utilizes the logistic regression model followed by an evaluation using the confusion matrix and classification report. 
*  Other steps include trying out different models (Support Vector Machine learning, Decision Tree Learning, as well as K Nearest Neighbors).

Language:
Python with scikit-learn

### Cryptocurrency Clustering with Unsupervised Machine Learning
Git Repo: [Crypto-Clustering Unsupervised Machine Learning](https://github.com/cindyd97/Crypto-Clustering_Unsupervised-Machine-Learning/tree/main)

Description: 
Clustering and unsupervised learning is used to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. The data is prepared and normalized using the standardscaler() module from scikit-learn. The elbow method is applied to find the best k value with a for loop and inertia. The data is modeled and fitted using Kmeans. The data is simplified using PCA to reduce the amount of features in the data set. The data is plotted in a scatter-gram format to showcase the clusters of the data.

Language:
Python with scikit-learn

## Excel VBA
[Back to top](#Each Git Repo includes the data source as well as project contents (see READMe))
### Analyzing Stock Data Using VBA Coding in Excel
Git Repo: [Stock-Analysis-VBA-coding](https://github.com/cindawwgg/Stock-Analysis-VBA-coding/tree/main)

Description:
This assignment analyzes quarterly stock data to find stocks with the greatest increase/decrease and the greatest volume traded for the quarter.

Language:
Excel - VBA

