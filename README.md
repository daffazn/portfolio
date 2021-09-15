# Data Analysis Projects

This repository contains individual projects that demonstrate my ability to use various tools and programming languages for data analysis. Most of these projects contain the process of data extraction, wrangling, cleaning, manipulation, exploration, and visualization. This repository will continue to be updated over time, either by addition of a new project or by the update of the existing project.

I use Jupyter Notebook to show my work, except for the project that use Tableau.

## Historical Airplane Accident Analysis
I web-scraped historical airplane accident data from planecrashinfo.com, which contains details of +5,000 accidents from 1908 until 2021. I use Python with the help of NumPy, Pandas, and Matplotlib libraries to do all the work.

## Twitter Keyword Analysis
I extracted +300,000 tweets containing keyword of Cristiano or Ronaldo (or both) at the day of his first match with Manchester United after his return. I use Tweepy Python library to access the Twitter API. The latest Tweepy stable release can only access the Twitter API v1.1, but I wanted to access the v2 because it gives more detalis about the tweet. So I decided to use the latest beta version of Tweepy.

I found an error when I was requesting specific data queries for the tweets. After exploring the library's code, I found the source of error and modify the code. So in the end, I used this modified library to extract the tweets. I also have included the modified file in this repository.

## European Soccer Analysis
I used a Kaggle’s dataset that consists of 25,000+ match details of European soccer leagues and other things related to it, from 2008 season until 2016. The data originally is in the form of an SQLite file (.sqlite). I migrated it to PostgreSQL database using Python’s SQLAlchemy and prepared the data using Pandas. Then I made the queries in PostgreSQL dialect. I also utilize Python so I can show the query results in Jupyter Notebook.

## COVID-19 Data Analysis
I used a dataset from Our World in Data that consists of 100,000+ data of daily pandemic information in every country, then I made a Tableau dashboard out of it.

## Police Activity Analysis
I used Stanford Open Policing dataset that consists of 500,000+ traffic stops details conducted by the police in State of Rhode Island in the US. I use Python with the help of NumPy, Pandas, and Matplotlib libraries to do all the work.
