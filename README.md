# Data Cleaning and Analysis with Pandas

## Overview

This Python script demonstrates a comprehensive approach to data cleaning and analysis using the Pandas library. The script reads a dataset from a file (in this case, 'chipotle.tsv') and performs various cleaning and preprocessing tasks to ensure the data's integrity and usability.

## Libraries Used

- Pandas
- NumPy
- Matplotlib.pyplot
- Seaborn

## Loading the Dataset

The script begins by loading the dataset from the 'chipotle.tsv' file using Pandas. It then identifies and prints the number of missing values in each column.

## Handling Missing Values

The script provides three common strategies for handling missing values:
1. Dropping rows with missing values
2. Filling missing values with a specific value (e.g., 0)
3. Filling missing values with the mean, median, or mode of the column

The user can choose the appropriate strategy based on their specific case and data characteristics.

## Data Type Adjustment

The script checks and adjusts data types, such as converting the 'quantity' column to numeric and 'item_price' to a float format. It also demonstrates how to handle duplicate entries in the dataset.

## Summary Statistics and Anomaly Detection

The script calculates summary statistics for relevant columns and checks for anomalies or inconsistencies in the data. It provides examples of identifying and handling negative quantities, negative or zero item prices, and unusually high prices.

## Cleaning Special Characters

The script checks for special characters in specified text columns and cleanses them based on analysis needs. An example is given for removing non-alphanumeric characters and spaces.

## Handling Order ID Irregularities

The script addresses irregularities in the 'Order ID' column, such as duplicate or missing IDs, to ensure data consistency.

## Item Name Standardization

The 'Item Name' column is standardized by converting to lowercase, removing extra spaces, and replacing specific variations with standardized terms.

## Data Visualization

The script uses Seaborn to visualize relationships between 'Quantity' and 'Item Price' using scatter plots.

## Data Integrity Checks and Corrections

Additional checks are performed for negative quantities, negative or zero item prices, and inconsistencies in descriptions and prices for the same item. The script demonstrates how to handle identified issues.

## One-Hot Encoding

For categorical columns (e.g., 'Item Name'), the script performs one-hot encoding to transform them into a format suitable for machine learning models.

## Unit Conversions or Adjustments

The script provides examples of converting quantities and item prices to consistent units or currencies.

---

