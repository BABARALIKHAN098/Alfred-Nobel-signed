# Movie Budget vs. Box Office Revenue Analysis

## Overview
This project investigates the relationship between film budgets and their financial performance. The primary goal is to determine if higher production budgets lead to higher box office revenue.

## Data Source
The dataset used in this analysis was scraped from [the-numbers.com](https://www.the-numbers.com/movie/budgets) on May 1st, 2018.

## Requirements
To run the notebook, you will need the following Python libraries:
- pandas
- matplotlib
- seaborn
- ydata-profiling
- scikit-learn

## Data Cleaning & Preparation
- **Type Conversion:** Converted currency-based strings (e.g., "$110,000") to numeric floats.
- **Datetime Formatting:** Standardized the `Release_Date` column to Pandas Datetime objects.
- **Exploration:** Identified and analyzed films with zero revenue and filtered for significant outliers.

## Key Findings
- **Average Film Budget:** ~$31.1 Million
- **Average Worldwide Gross:** ~$88.8 Million
- **Linear Relationship:** Using a Linear Regression model, the analysis suggests a strong correlation between budget and revenue. For example, a budget of $350 million is estimated to generate roughly $1.077 billion in revenue.

## How to Use
1. Clone the repository.
2. Ensure the dataset `cost_revenue_dirty.csv` is in the project directory.
3. Open `Seaborn_and_Linear_Regression_(start).ipynb` in Jupyter or Google Colab and run the cells.
