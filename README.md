# Adult Income Analysis

## Project Overview

This project analyzes the Adult Income dataset using Python. The main goal is to clean the dataset and explore the relationship between income levels and different demographic, education, occupation, and work-related features.

## Objectives

- Clean and preprocess the dataset
- Handle missing and inconsistent values
- Check and correct data types
- Perform exploratory data analysis (EDA)
- Analyze income patterns across different features
- Create new features for analysis
- Prepare a cleaned dataset for further analysis and machine learning

## Dataset

The dataset contains information about individuals, including:

- Age
- Workclass
- Final Weight (`fnlwgt`)
- Education
- Education Number
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain
- Capital Loss
- Hours per Week
- Native Country
- Income

## Data Cleaning

The following data-cleaning steps were performed:

- Removed unnecessary leading and trailing spaces
- Identified and handled missing values
- Replaced unknown values with missing values
- Handled missing values in categorical columns
- Cleaned and standardized the income values
- Checked for duplicate records
- Checked data types
- Created age groups
- Created work-hour groups
- Created a `net_capital` feature using capital gain and capital loss

## Exploratory Data Analysis

The project explores income patterns based on:

- Education
- Age
- Occupation
- Workclass
- Sex
- Hours worked per week
- Age groups

Different visualizations were created using Matplotlib and Seaborn to understand the data.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Files

| File | Description |
|---|---|
| `data cleaning(poject1).ipynb` | Jupyter Notebook containing data cleaning and exploratory data analysis |
| `adult_income_cleaned.csv` | Cleaned Adult Income dataset |
| `.gitignore` | Specifies files that should not be tracked by Git |

## Conclusion

This project demonstrates practical data cleaning and exploratory data analysis techniques using Python. The cleaned dataset provides a suitable foundation for further analysis and machine learning tasks.

## Author

**Sahil Das**
