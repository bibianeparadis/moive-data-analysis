# movie-data-analysis
Data cleaning and exploratory analysis of movie budgets, ratings, languages, and profitability using Python.

Python | Pandas | NumPy | Data Cleaning | Exploratory Data Analysis

# Overview

This project explores a large movie dataset using Python to demonstrate practical data cleaning, transformation, and exploratory analysis techniques.

The analysis examines movie budgets, ratings, languages, runtime, and financial performance while demonstrating how raw data can be transformed into a cleaner and more useful analytical dataset.

# Objectives
- Clean and prepare movie data for analysis
- Identify duplicate and incomplete records
- Examine movie budgets and ratings
- Analyze the diversity of original languages
- Calculate movie profitability
- Visualize the distribution of movie profits

# Dataset
The dataset contains movie-level information including:

- Title
- Release date
- Original language
- Genres
- Budget
- Revenue
- Runtime
- Ratings
- Analysis
- Data Cleaning

The project begins by selecting relevant variables and identifying data-quality issues. Duplicate records and rows with missing values are removed, and numeric fields are converted into appropriate data types.

# Budget Analysis

Movies with production budgets greater than $1 million are identified and analyzed.

# Rating Analysis

Highly rated movies are identified using a minimum vote-count threshold and an average rating above 8.

# Language Analysis

The number of unique original languages represented in the dataset is calculated.

# Profitability Analysis

Movie profit is calculated using:

Profit = Revenue - Budget

The resulting profit values are then examined using descriptive statistics and visualization.

# Key Findings
- 7,194 movies had production budgets over $1 million.
- 176 movies were highly rated, with an average rating above 8 and more than 20 votes.
- The dataset included 89 unique original languages.
- 344 contained missing values in the selected analysis fields
- Average movie profits was apporximetly 7.04 million dollars.

# Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

# Author
Bibiane Paradis
