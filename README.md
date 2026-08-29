# US Regional Sales Data Exploratory Data Analysis

This repository contains an exploratory data analysis (EDA) of US regional sales data. The analysis is performed using a Jupyter Notebook (`EDA.ipynb`) and covers various aspects of the sales data to uncover trends and patterns.

## Overview

The dataset analyzed contains historical sales data for 45 stores and 81 departments, spanning from `2010-02-05` to `2012-10-26`. The total revenue recorded in this dataset is `$6.74B` across `421,570` rows.

## Analysis Performed

The notebook performs the following analyses:

1.  **Data Loading and Initial Overview:**
    *   Loads the dataset from `sales data-set.csv`.
    *   Formats date columns and extracts year and month information.
    *   Provides basic statistics like the number of rows, unique stores, unique departments, date range, and total revenue.
2.  **Monthly Revenue Trend (All Stores):**
    *   Calculates and visualizes the total weekly sales aggregated by month, showing the overall revenue trend over time.
3.  **Top 10 Stores by Total Revenue:**
    *   Identifies and visualizes the top 10 stores that generated the highest total revenue.
4.  **Top 10 Departments by Total Revenue:**
    *   Identifies and visualizes the top 10 departments that generated the highest total revenue.
5.  **Average Weekly Sales: Holiday vs Non-Holiday:**
    *   Compares the average weekly sales during holiday weeks versus non-holiday weeks to assess the impact of holidays on sales.
6.  **Distribution of Weekly Sales:**
    *   Visualizes the distribution of weekly sales values using a histogram and Kernel Density Estimate (KDE) to understand the spread and skewness of the sales data.
7.  **Average Weekly Sales by Month:**
    *   Calculates and visualizes the average weekly sales for each month across all years to identify seasonal patterns.

## Requirements

To run the notebook, you will need the following Python libraries:

*   `pandas`
*   `matplotlib`
*   `seaborn`

## Usage

1.  Ensure you have the required libraries installed.
2.  Place the `sales data-set.csv` file in the appropriate directory (or update the file path in the notebook).
3.  Open and run the Jupyter Notebook to reproduce the analysis and visualizations.

