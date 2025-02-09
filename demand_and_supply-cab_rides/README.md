# Demand and Supply Analysis

This project demonstrates how to perform demand and supply analysis using Python. The dataset contains information on the number of drivers active per hour, riders active per hour, and the rides completed. The analysis explores the relationship between supply (drivers) and demand (riders), calculates the elasticity of demand, and visualizes key metrics like the supply ratio.

## Requirements

- Python 3.x
- Pandas
- Plotly

You can install the required libraries using `pip`
```

## Dataset

The dataset used in this project is a CSV file named `rides.csv`. It contains the following. Got the dataset and case study from STATSO. 

## Steps Involved

### 1. Importing Libraries and Dataset

The necessary libraries (`pandas`, `plotly`) are imported, and the dataset is loaded using Pandas.

### 2. Checking for Missing Values

We check for any null values in the dataset and handle them accordingly.

### 3. Demand and Supply Relationship

A scatter plot is generated to visualize the relationship between the number of drivers active per hour and the number of riders active per hour. A trendline is added to help understand the overall trend.

### 4. Calculating Elasticity of Demand

The elasticity of demand is calculated to determine the responsiveness of the demand for rides relative to changes in the number of drivers active per hour.

The result indicates a moderately responsive relationship between supply and demand.

### 5. Supply Ratio Calculation

A new column is added to the dataset to calculate the supply ratio for each level of driver activity. The formula used is:

### 6. Visualizing the Supply Ratio

A scatter plot is created to visualize the supply ratio against the number of drivers active per hour.


## Summary

This analysis provides insights into the relationship between supply and demand in the context of a ride-hailing service. The elasticity of demand helps businesses understand how sensitive consumer demand is to changes in the number of available drivers. Additionally, the supply ratio indicates the efficiency of the drivers in completing rides.

