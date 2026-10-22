# Retail Sales Exploratory Data Analysis & Visualization

## Project Overview

This project explores a retail sales dataset using Python to understand sales performance, customer demographics, product category revenue, and sales trends over time. Exploratory Data Analysis (EDA) and data visualization are used to summarize the dataset and identify useful business insights.

## Objectives

- Explore the structure and characteristics of retail sales data.
- Check for missing values and examine descriptive statistics.
- Analyze sales by product category and customer gender.
- Identify monthly and quarterly sales trends.
- Summarize findings that may support business decision-making.

## Dataset

The dataset, `retail_sales_dataset.csv`, contains **1,000 records and 9 columns**.

| Column | Description |
|---|---|
| Transaction ID | Unique transaction identifier |
| Date | Transaction date |
| Customer ID | Customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Product Category | Category of the purchased product |
| Quantity | Number of units purchased |
| Price per Unit | Price per unit |
| Total Amount | Total transaction amount |

## Tools and Libraries

- **Python** — analysis and calculations
- **Pandas** — data loading, manipulation, grouping, and aggregation
- **Matplotlib** — data visualization
- **Seaborn** — visualization library imported in the notebook

## Methodology

1. **Data loading and inspection:** Loaded the CSV file using Pandas and examined the first few records, dataset dimensions, column data types, and structure.
2. **Data quality checks:** Checked for missing values across all columns.
3. **Descriptive statistics:** Used summary statistics to examine numerical variables, including age, quantity, unit price, and total amount.
4. **Date processing:** Converted the `Date` column to datetime format and extracted monthly and quarterly periods.
5. **Sales analysis:** Grouped and aggregated sales data to compare product categories, customer gender, and sales performance over time.
6. **Visualization:** Created charts to make sales patterns and comparisons easier to understand.

## Visualizations

The notebook includes visual analysis of:

- Monthly sales trends using a line chart.
- Total sales by customer gender using a bar chart.
- Sales performance across product categories.
- Sales aggregated by month and quarter.

## Key Findings

- **Top revenue category:** Electronics generated the highest category revenue, totaling **156,905**.
- **Lowest revenue category:** Beauty generated the lowest category revenue, totaling **143,515**.
- **Sales by gender:** Female customers contributed the higher total sales, amounting to **232,840**.
- **Average customer age:** Approximately **41.39 years**.
- **Highest monthly sales:** May 2023, with **53,150** in sales.
- **Highest quarterly sales:** Q4 2023, with **126,190** in sales.
- **Data completeness:** No missing values were detected in the initial dataset inspection.

*Note: Sales amounts are reported in the dataset's units; no currency symbol is assumed.*

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data inspection and quality checks
- Descriptive statistics
- Date and time processing
- Grouping and aggregation with Pandas
- Time-based sales analysis
- Data visualization and interpretation
- Communicating findings from data

## Conclusion

This project demonstrates how Python can be used to explore retail transaction data, summarize customer and product information, and visualize sales patterns across different categories and time periods. The analysis highlights the strongest revenue-generating category, differences in sales by gender, and periods with higher sales activity.

## Repository Contents

- `data_analysis_week2.py` — Python code containing the analysis, code, outputs, and visualizations
- `README.md` — project documentation

