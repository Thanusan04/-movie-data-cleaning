Movie Dataset Cleaning Project
This project focuses on cleaning a raw movie dataset using Python and Pandas in a Jupyter Notebook environment.



Description
The original dataset (movies.csv) contained inconsistencies and formatting issues, such as:

Text fields with newline characters and unnecessary whitespace

Year values wrapped in parentheses (e.g., (2021))

VOTES stored as strings with commas (e.g., "885,805")

Missing values in important columns like RATING and RunTime

A mostly empty Gross column

Cleaning Steps
The following steps were applied to clean the dataset:

Removed newline characters and stripped extra whitespace from text fields (MOVIES, GENRE, ONE-LINE, STARS)

Extracted the year from the YEAR column using regular expressions

Converted the VOTES column to numeric format by removing commas

Dropped the Gross column due to excessive missing values

Removed rows with missing values in key columns such as RATING or RunTime

Technologies Used
Python 3

Pandas

Jupyter Notebook

How to Use
Clone or download this repository

Open the Pandas2F.ipynb notebook in Jupyter

Run the cells to see the cleaning process

Use movies_cleaned.csv for analysis or visualization
