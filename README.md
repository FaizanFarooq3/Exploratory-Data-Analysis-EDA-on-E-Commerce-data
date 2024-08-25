# Exploratory Data Analysis (EDA) on E-Commerce Data

## Objective
The primary objective of this project is to perform an Exploratory Data Analysis (EDA) on the E-Commerce dataset obtained from a UK-based online retail store. The analysis aims to uncover interesting patterns in customer behavior and transaction trends over time.

## Problem Statement
The analysis seeks to address the following key questions:
- Which customers place the most orders, and which countries generate the highest revenue?
- How do order volumes and revenue vary across different months, days, and times?
- Are there any specific trends or anomalies in the dataset that could inform business strategies?

## Dataset
- **Source:** [Kaggle E-Commerce Dataset](https://www.kaggle.com/carrie1/ecommerce-data)
- **Company:** UK-based and registered non-store online retail
- **Products:** Mainly all-occasion gifts
- **Customers:** Mostly wholesalers (local or international)
- **Transactions Period:** 1st Dec 2010 - 9th Dec 2011 (One year)
- **Size:** 541,909 transactions

## Methodology
The analysis involves the following steps:
1. Data Cleaning: Handling missing values, correcting data types, and filtering irrelevant data.
2. Data Exploration: Analyzing the distribution of transactions over time and across different customer segments.
3. Visualization: Creating insightful visualizations to highlight key patterns and trends.
4. Insights Extraction: Summarizing the findings into actionable insights.

## Tools Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## Results and Insights

### 1. Customer Order and Spending Patterns
- The **customer with the highest number of orders** is based in the United Kingdom (UK).
- The **customer with the highest total spending** comes from the Netherlands.
- The **top 5 countries by order volume** are:
    1. Germany
    2. France
    3. Ireland (EIRE)
    4. Spain
    5. Netherlands



### 2. Money Spent by Country
The **top 5 countries by money spent** are:
1. Netherlands
2. Ireland (EIRE)
3. Germany
4. France
5. Australia

### 3. Monthly Sales Trends
- **November 2011** recorded the highest sales volume.
- Due to incomplete data for December 2011, it’s not possible to determine the month with the lowest sales.


### 4. Daily Sales Patterns
- The company **does not receive any orders on Saturdays** during the observed period.
- **Thursday** is the most active day for transactions, with order volumes peaking on this day.


### 5. Hourly Sales Patterns
- The company receives the **highest number of orders at 12:00 PM**.
- Most customers likely make purchases during their lunch hour, between **12:00 PM and 2:00 PM**.

### 6. Free Item Distribution
- The company occasionally **gives out free items** with purchases each month, but the criteria for these giveaways are unclear.

## Conclusion
This EDA provides valuable insights into customer behavior, order patterns, and sales trends. These insights can help the company optimize its marketing strategies, stock management, and customer targeting.

## Notes
For more details, you can refer to the [Notebook]([https://www.kaggle.com/admond1994/e-commerce-data-eda](https://github.com/FaizanFarooq3/Exploratory-Data-Analysis-EDA-on-E-Commerce-data/blob/main/Exploratory_Data_Analysis_(EDA)_on_E_Commerce_data.ipynb)).

## Acknowledgements
This data was made available by Dr. Daqing Chen, Director of the Public Analytics Group at the London South Bank University, via the UCI Machine Learning Repository.
