# Loan Data Analysis README

## Overview

This repository contains Python code for analyzing loan data using various libraries such as Pandas, NumPy, Matplotlib, Seaborn, and SciPy.

## Code Description

The code performs the following tasks:

### Data Loading and Exploration

- Imports the necessary libraries.
- Reads loan data from a CSV file (`LoanStatus.csv`).
- Prints the first 5 rows of the dataset.

### Descriptive Statistics

- Calculates statistics like mean, median, and standard deviation for applicant income and loan amount.
- Displays the statistics in a DataFrame.

### Handling Missing Values

- Computes the number of missing values in the dataset.

### Loan Status Probability

- Computes the probability of loan approval status.

### Analysis of Good Credit History

- Calculates the probability of loan approval for individuals with a good credit history.

### Data Visualization

- Creates a histogram of applicant income distribution.
- Creates a histogram of loan amount distribution.

### Statistical Analysis

- Computes the cumulative probability of applicant income.
- Displays boxplots for applicant income and loan amount.

### Statistical Tests

- Performs a one-sample t-test to compare applicant income against a hypothesized mean.
- Performs a two-sample t-test to compare loan amounts between graduates and non-graduates.
