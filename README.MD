# Retail Sales Analysis (2023)
An exploratory data analysis (EDA) report of one year retail sales data using Python. Cleans the data first, and explores sales and profit patterns across time, product categories and regions, and ends with data_driven business recommendations.

## Project Goals
 ### The analysis tries to answer the following questions:
- 1. How do sales and profit change each month?
- 2. Which product category performs best?
- 3. How do the regions compare?
- 4. Does the day of the week affects sales?
- 5. Which numeric variables are related(correlation)?


## Dataset
 - ###  File: retail_sales.csv
 - ### Size: 1864 Rows x 6 Columns
 - ### Source: Kaggle


## Methodology
 - ### Data loading and inspection
checked shape, data types and missing values
 - ### Cleaning
 Missing values filled with Mean(Quantity), most frequent(Category) and placeholder strings such as 'NaN?' were dropped
 Date column converted to datetime - Month, Quarter, Day of Week, and Month Name features were created
 - ### Exploratory analysis
  Descriptive Statistics - groupby-summaries by category, region, month and weekday

- ### Visualization 
Line chart, Bar chart, Pie Chart, and a correlation Heatmap