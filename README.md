# Diwali Sales Data Analysis

This project analyzes Diwali Sales data to visualize customer demographics, purchasing patterns, and product popularity. The analysis is performed using Python with pandas for data manipulation and seaborn/matplotlib for data visualization.

## Prerequisites

Before you begin, ensure you have the following libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
# Dataset
The dataset used for this analysis should be in CSV format and should be placed in the specified path in the script. The dataset contains sales information, including customer demographics and purchase details.

# Code Description
### Import Libraries:

Import numpy, pandas, matplotlib.pyplot, and seaborn.
### Load Dataset:

Load the dataset using pd.read_csv() with appropriate encoding.
### Display Shape and Info:

Display the shape and concise summary of the DataFrame.
### Drop Unnecessary Columns:

Remove columns that are not needed for analysis.
### Visualize Missing Values:

Create a heatmap to visualize missing values.
### Remove Duplicates:

Count and remove duplicate rows from the dataset.
### Handle Missing Values:

Check for and remove rows with missing values.
### Convert Data Types:

Convert the 'Amount' column to integer type.
### Descriptive Statistics:

Display summary statistics for numerical columns.
### Gender Distribution:

Plot the count and pie chart of gender distribution.
### Total Sales by Gender:

Group data by gender and sum the 'Amount' column, then plot the results.
### Age Group Distribution by Gender:

Plot the count of age groups by gender.
### Total Sales by Age Group:

Group data by age group and sum the 'Amount' column, then plot the results.
### Top States by Number of Orders and Total Sales:

Group data by state and sum the 'Orders' and 'Amount' columns, then plot the top 10 states.
### Marital Status Distribution and Sales by Marital Status and Gender:

Plot the count of marital status and group data by marital status and gender, then plot the results.
### Occupation Distribution and Sales by Occupation:

Plot the count of occupations and group data by occupation, then plot the results.
### Product Category Distribution and Sales by Product Category:

Plot the count of product categories and group data by product category, then plot the top 10 categories.
### Top 10 Most Sold Products:

Group data by product ID and sum the 'Orders' column, then plot the top 10 products.

### Running the Code
To run the script, ensure your dataset is in the correct path and run the script using a Python interpreter. The script will generate various plots and summaries, providing insights into the Diwali sales data.

## Conclusion
This project provides an in-depth analysis of Diwali sales data, uncovering valuable insights related to customer demographics and purchasing behavior.


