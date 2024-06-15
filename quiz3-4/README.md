# Earthquake Data Analysis README

## Overview

This task contains Python code for analyzing earthquake data using various libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## Code Description

The code performs the following tasks:

### Data Loading and Exploration

- Imports the necessary libraries.
- Reads earthquake data from a CSV file

### Data Cleaning and Preparation

- Drops unnecessary columns
- Handles missing values by filling the 'Depth Error' column with the median value:
- Combines latitude and longitude into a single 'Coordinates' column and drops the original columns
- Categorizes the 'Depth' column into bins

### Data Transformation

-  Transforms the DataFrame to a long format for better analysis
-  Creates a pivot table to analyze the average magnitude by depth category and magnitude type:

### Data Visualization

-  Visualizes the distribution of magnitudes across different depth categories using a box plot
-  Plots a histogram to show the frequency distribution of earthquake depths
-  Creates a bar plot to display the average magnitude for each depth category
-  Calculates and plots the 30-day rolling average of earthquake magnitudes
-  Extracts the year from the 'Date' column and plots the frequency of earthquakes per year
