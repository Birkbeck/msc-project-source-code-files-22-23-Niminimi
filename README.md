# Forecasting Men's ATP Tennis Match Outcomes: A Comparative Study of Machine Learning Algorithms with Emphasis on Mental Toughness Features

# Project Overview:
The aim of this project is to predict the winner of a tennis ATP match based on a set of features, with a special focus on mental toughness features such as breakpoints, tiebreaks, and comebacks.

# Code Details:
**•	Main File**: The final code file in this repository is “Project Code - Cleaned.ipynb”.

**•	Environment**: The code was developed in a Jupyter notebook environment and can also be run in Google Colab.

# Troubleshooting CSV Loading:
If you encounter an error while reading the CSV file using:
df_pandas_local = pd.read_csv('all_years_csv.csv')
Please try one of the following alternatives:
1. df_pandas_local = pd.read_csv('all_years_csv.csv', low_memory=False)
2. df_pandas_local = pd.read_csv('all_years_csv.csv', dtype={8: str, 16: str})

# Data Source:
The dataset for this project is sourced from the GitHub repository maintained by Jeff Sackmann:
https://github.com/JeffSackmann/tennis_atp

Note: The CSV file, “all_years_csv.csv”, was created by merging data from the years 1991-2023, as Sackmann's repository provides separate CSV files for each year.

