# Decodelabs Internship Projects

I worked on practical data analytics projects involving data cleaning and preparation, exploratory data analysis (EDA), and SQL data analysis. Cleaned and transformed datasets to improve data quality, analyzed patterns, distribution and trends using descriptive statistics, correlation analysis and visualizations, and used SQL queries to extract, filter, aggregate, and analyze data to generate meaningful insights for decision-making.

## Features
- Cleaned and transformed raw datasets to improve data quality
- Performed exploratory data analysis using descriptive statistics (mean, median, count)
- Conducted correlation analysis to identify relationships between variables
- Created visualizations to reveal patterns, distributions, and trends
- Wrote SQL queries to extract, filter, and aggregate data for analysis
- Generated insights to support data-driven decision-making

## Installation
```bash
git clone https://github.com/grace-akpan/repo.git
cd repo
```


# Core Summaries

## Project 1:Data Cleaning

The dataset was reviewed for data-quality issues before analysis. The following data-cleaning steps were performed:

- **Date formats:** Corrected inconsistent date formats.
- **Duplicates:** Checked for duplicate records; no duplicates were identified.
- **Data types:** Converted `Quantity`, `Unit Price`, and `Total Price` to appropriate numeric data types.
- **Missing values:** Checked for missing values and handled them appropriately. Identified 309 blank values in the `CouponCode` column and replaced them with `"No code"` to distinguish missing entries from actual coupon codes.

# Tools & Skills
- Microsoft Excel
- Data cleaning 
  
## Project 2: Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand the patterns, trends, distributions, and relationships within the dataset before drawing conclusions. Descriptive Statistics (mean=1053.97, median = 823.62 and 1200 records )
values were calculated for key numerical variables to understand their distribution and central tendency.
A box-and-whisker plot was used to examine the distribution of the data and identify potential outliers. Any observations flagged as potential outliers ranging from 3334.00  to 3456.40 were reviewed to determine whether they represented genuine values or possible data-quality issues.
Correlation analysis was performed to examine the relationship between `Quantity` and `Total Price`. **Pearson correlation coefficient:** r = 0.615, showing a moderate positive linear relationship and the relationship between `Unit Price`, and `Total Price` producing **Pearson correlation coefficient:** r = 0.717, showing a strong positive relationship. 
PivotTables were used to summarize and compare sales performance across relevant categories, providing a clearer view of patterns and differences within the dataset.

# Tools & Skills
- Microsoft Excel
- Exploratory Data Analysis  


# Project 3: SQL Assessment

In this project, I performed **12 SQL queries** to analyze e-commerce order data and evaluate sales performance, order statuses, customer spending, product performance, cancellations, promotions, and referral sources.
I applied SQL techniques including **CTEs, CASE statements, WHERE clauses, aggregate functions, GROUP BY, HAVING, filtering, and window functions** to answer business questions and generate actionable insights.

## Key Findings
- Cancelled and Returned orders represented **41.1% of revenue** under the Lost/Retained classification used in the SQL analysis.
- **Credit Card** recorded the highest cancellation rate at **23.1%**, while **Debit Card** had the lowest at **19.0%**.
- Monthly completed-sale revenue showed considerable fluctuations rather than a consistent upward trend.
- **Referral** recorded the highest referral-source success rate at **41.4%**, and **Facebook** had the highest average order value at **1,098.29**. **Instagram** had the lowest success rate at **36.3%**.

## Tools & Skills

- DB Browser SQLite / SQL
- Data Filtering
- Data Aggregation
  
---

# Project 4: Data Visualization

This project builds on the SQL analysis from Project 3 by transforming the findings into clear, business-focused insights, avoiding misleading data visualizations and chartjunk. I created **DAX measures** for dashboard, Selected **appropriate charts** based on each business question and built a **zero-baseline dashboard** highlighting actionable insights

## Tools & Skills
- Power BI
- DAX
- Data Visualization
- Data Storytelling
