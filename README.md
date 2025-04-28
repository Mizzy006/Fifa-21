## FIFA 21 Data Cleaning Project

## Project Overview
This project involves cleaning and preparing the FIFA 21 player dataset for data analysis and machine learning purposes.
The raw data contains real-world imperfections such as inconsistent formats, mixed text and numbers, embedded contract details, missing values, and unnecessary columns.
The goal is to transform this messy data into a structured, reliable, and analysis-ready format using Python.

## Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Regular Expressions (re library)

## Cleaning Steps
Removed unwanted characters (e.g., \n, ★, ', cm, lbs) from text fields.

Converted Height and Weight columns from strings to numeric values.

Extracted Team and Contract information from a combined text field.

Cleaned and standardized the Hits column.

Renamed ambiguous columns for clarity.

Dropped irrelevant or unnecessary columns.

Handled missing data safely and validated the cleaned output.
