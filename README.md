# Data Cleaning and Exploratory Data Analysis on python
* Data Cleaning on the "house price prediction" data set
* Libraries used; numpy, pandas, missingno & matplotlib

## Step 1: Initial steps
* Deleted unncessary columns
* Made a user defined function "info" to get get number of nulls and unique values in a column instantly  
* Made a user defined function "ranges" to get minimum, maximum, mean, median and mode in a coloumn instantly 
* Made a column to uniquely identify every row (this is used later)

## Step 2 : Removed data entry errors
* Replaced blank spaces and other data entry errors with null values

## Step 3 : Identifying the case of MNAR (Missing Not at Random)  
* Used manobar library to visualize the trend of missing values
* The case of MNAR occurs with less than 5% of the data, therefore deleting those specific rows

## Step 4 : Replacing null values in each column using different techniques
* Used the documentation given with the csv file to understand the relationship between columns
* Used EDA to detect outliers
