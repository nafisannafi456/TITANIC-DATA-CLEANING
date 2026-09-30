# Titanic Dataset Cleaning and Analysis

## Project Overview
This project focuses on the comprehensive data cleaning and preprocessing of the famous Titanic dataset. The goal was to transform raw, messy data into a clean, structured format suitable for machine learning algorithms or in-depth data analysis.

## Dataset Description
The Titanic dataset contains information about passengers aboard the RMS Titanic, including details like survival status, age, sex, passenger class, ticket fare, and embarkation point.

## Steps Taken

### 1. Data Cleaning
- **Handling Missing Values:** Imputed missing age values using the median and filled missing embarkation points with the most frequent value (mode).
- **Dropping Unnecessary Columns:** Removed columns that did not contribute significantly to the analysis (e.g., deck, cabin, passenger ID).

### 2. Feature Engineering & Encoding
- **Categorical Encoding:** Converted categorical variables like 'sex' (male/female) and 'embarked' (S, C, Q) into numerical formats for machine learning models.
- **Data Scaling:** Normalized numerical features like 'age' and 'fare' to ensure consistency.

## Tools Used
- Python
- Pandas
- Seaborn
