Dataset Explorer Tool

Overview

The Dataset Explorer Tool is a Python-based application that automatically analyzes and summarizes CSV datasets. It helps users understand the structure, quality, and statistical characteristics of data using Python and Pandas.

Features

Dataset Loading

- Loads CSV files using Pandas
- Handles file loading errors gracefully

Data Inspection

- Displays dataset shape
- Shows column names and data types
- Displays the first 5 rows of the dataset

Missing Value Analysis

- Identifies missing values
- Calculates missing value percentages

Statistical Summary

- Mean
- Median
- Standard Deviation
- Minimum Value
- Maximum Value

Outlier Detection

- Detects outliers using the IQR method

Technologies Used

- Python 3
- Pandas

Project Structure

dataset-explorer/

├── Mall_Customers.csv

├── explorer.py

└── README.md

Dataset

This project uses the Mall Customers dataset containing:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

The dataset is commonly used for customer segmentation and data analysis projects.

Installation

pip install pandas

How to Run

python explorer.py

Learning Outcomes

- Reading CSV files with Pandas
- Exploratory Data Analysis (EDA)
- Missing Value Analysis
- Descriptive Statistics
- Outlier Detection using IQR
- Git and GitHub Version Control

Author

Nivedhitha K

License

This project is created for educational and learning purposes.