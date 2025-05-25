# data-cleaning
# Data Cleaning and Validation Script

This Python script performs data cleaning and validation on a dataset (`dataset.csv`) using `pandas` and `numpy`. It checks for missing values, detects outliers using the IQR method, identifies duplicate rows, and validates entries based on logical constraints (e.g., valid age, IQ, gender, sleeping hours).

## Features

- Detects and summarizes missing values
- Identifies outliers in numeric columns using the IQR method
- Checks for duplicate rows
- Validates value ranges (e.g., Age: 0–120, IQ: 50–200, Gender: Male/Female)
- Cleans data by removing duplicates and filling missing values (median/mode)
- Outputs a cleaned DataFrame ready for analysis

## Requirements

- Python 3.x
- pandas
- numpy

Install the required libraries using:

```bash
pip install pandas,numpy,io

