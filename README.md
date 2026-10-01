# Decodelabs Internship Projects

Worked on practical data analytics projects involving data cleaning and preparation, exploratory data analysis (EDA), and SQL data analysis. Cleaned and transformed datasets to improve data quality, analyzed patterns, distribution and trends using descriptive statistics, correlation analysis and visualizations, and used SQL queries to extract, filter, aggregate, and analyze data to generate meaningful insights for decision-making.

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

## Project 2: Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand the patterns, trends, distributions, and relationships within the dataset before drawing conclusions. Descriptive Statistics (mean=1053.97, median = 823.62 and 1200 records )
values were calculated for key numerical variables to understand their distribution and central tendency.
A box-and-whisker plot was used to examine the distribution of the data and identify potential outliers. Any observations flagged as potential outliers of 11.39 and 3456.40 were reviewed to determine whether they represented genuine values or possible data-quality issues.
Correlation analysis was performed to examine the relationship between `Quantity` and `Total Price`.
- **Pearson correlation coefficient:** r = 0.615
- **Interpretation:** A moderate positive linear relationship, suggesting that higher quantities tend to be associated with higher total prices.
PivotTables were used to summarize and compare sales performance across relevant categories, providing a clearer view of patterns and differences within the dataset.


