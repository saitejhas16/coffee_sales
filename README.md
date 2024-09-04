# Coffee Sales Data Analysis

## Project Overview

This project performs data analysis on a dataset of coffee sales over six months. The analysis includes data cleaning, filtering, and visualization to gain insights into weekly sales statistics, sales by coffee type, and payment methods.

## Notebook Structure

The notebook includes the following sections:

- **Introduction**
  - Providing an overview of the analysis and its objectives.

- **Importing Libraries**
  - Importing necessary Python libraries such as `pandas` and `matplotlib`.

- **Loading the Dataset**
  - Loading the coffee sales dataset into a pandas DataFrame for analysis.

- **Data Cleaning**
  - Dropping unnecessary columns (e.g., card information) to maintain privacy.

- **Data Filtering**
  - Filtering the dataset to focus on sales data for a specific month (e.g., March).

- **Data Visualization**
  - Visualizing weekly sales statistics.
  - Analyzing sales by coffee type.
  - Examining payment methods used by customers.

## Key Functions and Code

- **Data Loading:** The dataset is loaded using `pd.read_csv()` from a specified path.
- **Data Cleaning:** Unnecessary columns are dropped to maintain data privacy.
- **Data Visualization:** 
  - Visualizing weekly sales statistics using bar charts.
  - Representing coffee type sales with pie charts.
  - Analyzing payment methods (cash/card) using matplotlib visualizations.

## Requirements

To run this notebook, you need the following Python libraries:

- `pandas`
- `matplotlib`

You can install these libraries using pip:

```bash
pip install pandas matplotlib
