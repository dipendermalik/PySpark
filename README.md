# PySpark Repository

This repository contains notebooks that cover the basics and advanced functionalities of PySpark, including MLlib and sentiment analysis. Below is an overview of the notebooks:

## Notebooks

1. **PySpark Basics.ipynb**
   - Introduction to PySpark using Google Colab.
   - Setup and configuration of Java and Spark.

### Contents of PySpark Basics.ipynb

#### 1. PySpark First Impression Using Colab
- **Setup Steps:**
  - Download Java and Spark.
  - Set up environment paths.
  - Create a Spark session.

- **Data Import and Exploration:**
  - **1.0 Import data from CSV:**
    - Load a CSV file into a DataFrame.
    - Display the first few rows of the DataFrame.
    - Check the data type of the DataFrame.
    - Get the total number of rows.
    - Understand the data types of each column.
    - Subset the DataFrame by columns, find distinct column values, and count by column(s).

  - **1.1 Import data from JSON:**
    - Load a compressed JSON file into a DataFrame.
    - Display the first few rows of the DataFrame.
    - Check the data type of the DataFrame.
    - Get the total number of rows.
    - Understand the schema and data types of each column.
    - Subset the DataFrame by columns or rows, find distinct column values, and count by column(s).
    - Use Spark SQL functions to summarize the data.

#### 2. PySpark DataFrame Operations
- **Summary of DataFrame Operations:**
  - Get summary statistics of the DataFrame.
  - Show data types for each column.
  - Retrieve columns and extract values from a single column.
  - Rename columns.
  - Filter DataFrames using `where` and `filter`, with support for multiple column conditions.
  - Convert a Spark DataFrame to a Pandas DataFrame.
  - Create SQL temporary views from DataFrames.
  - List all tables available in the current Spark session.
  - Use explicit SQL queries on DataFrames.

## Future Notebooks

- **PySpark MLlib.ipynb:** An introduction to machine learning with PySpark MLlib.
- **PySpark MLlib Sentiment Analysis.ipynb:** A detailed guide on performing sentiment analysis using PySpark MLlib.

## Getting Started

To run the notebooks, you will need:

- Java (JDK 8 or later)
- Apache Spark
- Google Colab or a local environment with the above requirements installed.

## Contributing

Feel free to contribute to this repository by suggesting improvements or adding new functionalities.
