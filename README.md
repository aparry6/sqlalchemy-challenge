# Analysis of Climate Data in Hawaii


This project analyzes climate data collected in Hawaii by a series of weather stations. The dataset contains measurements of temperature and precipitation from 1950 to 2017.
The analysis is performed using Python, SQLAlchemy, and Jupyter Notebook. The dataset is loaded into a SQLite database using SQLAlchemy, and then queried to extract various summary statistics and visualizations.
The analysis includes the following steps:
Connect to the SQLite database using SQLAlchemy.
Query the database to retrieve the last 12 months of precipitation data and plot the results using Pandas and Matplotlib.
Calculate summary statistics for the precipitation data using Pandas.
Query the database to calculate the total number of stations in the dataset.
Find the most active stations in the dataset by counting the number of rows associated with each station.
Using the most active station from the previous query, calculate the lowest, highest, and average temperature recorded at that station.
Plot a histogram of temperature observations for the station with the highest number of observations.
