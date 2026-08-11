# Pandas Data Analysis and DataFrame Operations

## Overview

This project demonstrates the use of **Pandas** for loading, exploring, cleaning, manipulating, analyzing, and exporting structured data.

The program uses a dataset containing information about Android applications, including application names, categories, ratings, reviews, size, installations, pricing, content ratings, genres, and Android version requirements.

The implementation demonstrates important Pandas concepts that are commonly used in **Data Analysis and Visualization (DAV)**.

## Dataset

The project uses an Android application dataset containing **10,841 records and 13 columns**.

The dataset includes information such as:

* App name
* Category
* Rating
* Reviews
* Size
* Number of installs
* Type
* Price
* Content Rating
* Genres
* Last Updated date
* Current Version
* Android Version

The dataset is stored in a CSV file named `data.csv`.

## Objectives

* Load a CSV dataset into a Pandas DataFrame.
* Explore the structure and contents of the dataset.
* Examine data types and general information.
* Generate summary statistics.
* Handle missing values.
* Create and manipulate DataFrame columns.
* Work with Pandas Series.
* Filter data based on multiple conditions.
* Perform grouping and aggregation.
* Sort DataFrame records.
* Apply Boolean masking.
* Remove duplicate records.
* Select specific columns.
* Export processed data to a CSV file.
* Calculate statistical measures from numerical data.

## Concepts Covered

### 1. Loading Data

The dataset is loaded from a CSV file into a Pandas DataFrame for further analysis.

### 2. Data Exploration

The program examines the beginning and ending records of the dataset to understand its structure and contents.

### 3. DataFrame Information

The structure of the DataFrame is analyzed by checking:

* Number of rows
* Number of columns
* Column names
* Non-null values
* Data types
* Memory usage

### 4. Summary Statistics

Descriptive statistics are calculated for numerical columns to understand the distribution of the data.

The analysis includes measures such as:

* Count
* Mean
* Standard deviation
* Minimum
* Maximum
* Quartiles

### 5. Handling Missing Values

Missing values are identified and handled using Pandas functions to improve the quality and consistency of the dataset.

### 6. Creating New Columns

The program demonstrates how to create a new DataFrame column using an existing column and an arithmetic operation.

### 7. Series Operations

A single DataFrame column is extracted as a Pandas Series, and arithmetic operations are performed on it.

### 8. Filtering Data

Rows are filtered using multiple conditions to select records that satisfy specific requirements.

### 9. Grouping and Aggregation

The `groupby` operation is used to divide the dataset into groups and calculate aggregate values such as the mean.

### 10. Sorting

The DataFrame is sorted based on a numerical column in descending order to organize the records according to their values.

### 11. Boolean Masking

Boolean conditions are used to select records whose numerical values satisfy a particular condition, such as being greater than the median.

### 12. Removing Duplicates and Missing Values

Duplicate records and remaining missing values are removed to produce a cleaner dataset.

### 13. Selecting Columns

A subset of required columns is selected from the original DataFrame to create a new DataFrame.

### 14. Exporting Data

The processed DataFrame is saved as a new CSV file named `filtered_data.csv`.

### 15. Statistical Analysis

Basic statistical measures are calculated for numerical data, including:

* Sum
* Mean
* Standard deviation

## Requirements

* Python 3.x
* Pandas
* Jupyter Notebook or JupyterLab
* CSV dataset

## Installation

Install Pandas using the following command:

```bash
pip install pandas
```

## Project Files

```text
Pandas-Data-Analysis/
│
├── data.csv
├── program.ipynb
├── filtered_data.csv
└── README.md
```

## Applications

The concepts demonstrated in this project can be applied to:

* Data cleaning
* Data preprocessing
* Exploratory Data Analysis (EDA)
* Business analytics
* Statistical analysis
* Dataset management
* Data filtering and transformation
* Report generation
* Machine learning preprocessing
* Data Science projects

## Conclusion

This project provides a practical introduction to **Pandas for data analysis and manipulation**. It demonstrates how real-world datasets can be loaded, explored, cleaned, transformed, filtered, grouped, analyzed, and exported using Pandas.

The Android application dataset provides a practical example of applying these techniques to a real-world dataset and forms a foundation for more advanced data analysis and visualization tasks.

## Author

**Vishnu A**

**Course:** Computer Science and Engineering
**Subject:** Data Analysis and Visualization (DAV)
