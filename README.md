# Online Store Sales Analysis

## Project Overview

This project presents a comprehensive analysis of sales data from an online store operating in the USA between 2014 and 2018. The goal is to uncover sales and profit patterns, identify key customer segments, and provide actionable business insights to improve store performance.

## Dataset

- The raw data file used is `Sample - Superstore.csv`.
- The dataset contains order transactions with details such as product names, sales, profit, regions, customers, and dates.
- Data is preprocessed to fix encoding issues, parse dates, handle missing values, and engineer new features.

## Data Preprocessing

An additional notebook (`data_preprocessing.ipynb`) is included to demonstrate the full data preparation pipeline:

- Reading raw data with correct encoding (`windows-1252`).
- Cleaning and handling missing data.
- Converting date columns to datetime format.
- Creating new features such as `year-month` and `profit margin`.
- Saving the cleaned data as `Preprocessed_data.csv` for further analysis.

This ensures reproducibility and a clear understanding of how raw data is transformed for analysis.

## Analysis

The main analysis notebook (`sales_analysis.ipynb`) covers:

- Total profit calculation over the period.
- Identification of top 5 products by sales.
- Identification of top 5 customers by profit.
- Average order value calculation.
- Monthly order trends and seasonal analysis.
- Profit distribution by region, category, and city.
- Visualization through bar charts, pie charts, boxplots, line plots, and heatmaps.
- Insights and business recommendations based on the data.

## Key Findings and Conclusions

- The technology category is the most profitable, while furniture lags significantly.
- Top customers contribute disproportionately to profit and should be prioritized for retention strategies.
- Sales peak in November and December, likely due to holiday shopping.
- The Western region generates the most profit; however, certain cities show significant negative profits and require strategic attention.
- Recommendations include focusing on the technology segment, improving or reconsidering furniture offerings, and enhancing marketing efforts in less profitable regions.

## How to Use This Repository

1. Explore `data_preprocessing.ipynb` to understand how raw data is cleaned and prepared.
2. Review `sales_analysis.ipynb` for detailed exploratory data analysis and visualization.
3. All necessary data files (`Sample - Superstore.csv`, `Preprocessed_data.csv`) are included.
4. Visualizations and insights are embedded within notebooks for ease of understanding.

## Technologies and Tools

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV data files

---

If you have any questions or feedback, feel free to reach out!

