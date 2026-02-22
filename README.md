# Study-of-Pandas
## Name- Srushti J. Nalawade
## PRN- 25070123157
## Batch- A1
## Aim:
To study the Pandas library and perform basic operations on Series and DataFrame.

## Objectives

>To understand the features of Pandas

>To create Series and DataFrame

>To perform data selection and filtering

>To handle missing values

>To read and write data using Pandas

## Software Requirement

>Python 3.x

>Pandas Library

>Jupyter Notebook / Google Colab / Python IDE

## Theory
Pandas is an open-source Python library used for data manipulation and data analysis. It provides two main data structures:
1. Series
A one-dimensional labeled array capable of holding data of any type.
2. DataFrame
A two-dimensional labeled data structure consisting of rows and columns.

Pandas is widely used in:

Data cleaning

Data transformation

Statistical analysis

Exploratory Data Analysis

It is built on NumPy and provides fast and efficient data handling.

## Important Functions


Function :	                                Description

head()	:                                  Displays first 5 rows

tail()	:                                  Displays last 5 rows

info()	 :                                 Shows dataset structure

describe():	                              Statistical summary

loc	       :                               Label-based selection

iloc	      :                              Position-based selection

isnull()	   :                             Detect missing values

dropna()	    :                            Remove missing values

fillna()	     :                           Fill missing values



## Program

import pandas as pd

#Creating Series

s = pd.Series([10, 20, 30, 40])

print("Series:\n", s)

#Creating DataFrame

data = {
    
    "Name": ["A", "B", "C"],
    "Marks": [85, 90, 78]

}

df = pd.DataFrame(data)

print("\nDataFrame:\n", df)

#Display first rows

print("\nFirst 5 rows:\n", df.head())

#Statistical summary

print("\nDescription:\n", df.describe())

#Selecting column

print("\nMarks Column:\n", df["Marks"])

## Output

Series is created successfully

DataFrame is displayed

First five rows are shown

Statistical summary of numerical data is displayed

## Conclusion
Thus, the basic operations of the Pandas library such as creation of Series and DataFrame, data viewing, and data selection were successfully performed.
