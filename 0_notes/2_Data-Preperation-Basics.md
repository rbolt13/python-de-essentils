# Data Preparation Basics

# Filtering and Selecting 

## Introducing the pandas Library

* Why pandas - fast data cleaning, preparation, and analysis; easy to use for data visualization and machine learning. 
* What is pandas - built on top of NumPy, makes it easy to work with arrays and matrices (called series and data frames). 

## Indexing in pandas

An index is a list of integers or labels you use to uniquely identify rows or columns.

This course uses:

* A set of square-brackets [...]
* The .loc[] indexer 

## DataFrame object recap

DataFrame object - acts like a spreadsheet in Excel, made of a set of Series objects, and are indexable.

Series object - a row or column that is indexed 

## Comparison Operators in Python 

![image](https://user-images.githubusercontent.com/76530973/191070350-7a861b0e-5333-4b7d-9800-2c9e7cc83380.png)

## Code Demonstration

* Plain indexing
* Data slicing 
* Arithmetic comparisions

# Missing Values in Python

* By default, missing values are represented with NaN: "Not a Number"
* Warning: If your dataset has 0s, 99s, or 999s, be sure to either drop or approximate them as you would with missing values. 

## Example 

Imagine you work at a local car dealership, and are tasked with summarizing results from a customer satisfaction survey. 

![image](https://user-images.githubusercontent.com/76530973/191333886-91fca58e-f315-49a4-945f-5c1b71dacced.png)

Notice Sally and Jim are missing values for the "Quality of Work", but did respond to the other 75% of information. We dont want to drop the information they gave or drop the information given for this column by Rod, Sam, and Jane. What should we do?

We could fill in the missing values with an approximation of the average of the other values in the column. 

In the coding demonstration we will show why it is important to approximate missing values as oppose to dropping them all together. 

## Missing values in Python

* Discovering what's missing 
* Filling in for missing values
* COunting missing values
* Filtering out missing values



