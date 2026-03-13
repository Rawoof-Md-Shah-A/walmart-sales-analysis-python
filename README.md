# Walmart Sales Data Analysis (Python)

## Project Overview
This project analyzes Walmart store sales data to identify patterns, trends, and factors influencing revenue.

The analysis focuses on:
- Sales trends over time
- Store performance comparison
- Seasonal sales patterns
- Impact of holidays on revenue
- Relationship between economic indicators and sales

## Dataset
The dataset contains weekly sales data from multiple Walmart stores including:

- Store
- Date
- Weekly Sales
- Holiday Flag
- Temperature
- Fuel Price
- CPI
- Unemployment

## Project Structure
walmart-sales-analysis-python
│
├── data
│   ├── raw
│   └── processed
│
├── notebooks
│   ├── 01_data_cleaning.ipynb
│   ├── 02_sales_analysis.ipynb
│   └── 03_visualization_insights.ipynb
│
├── outputs
│   └── figures
│
├── requirements.txt
└── README.md

## Analysis Steps

1. Data Cleaning
- Loaded dataset
- Checked missing values
- Converted date formats
- Created new time features

2. Sales Analysis
- Total revenue calculation
- Store performance ranking
- Yearly and monthly sales trends
- Holiday sales comparison

3. Visualization
- Weekly sales trend
- Top performing stores
- Holiday vs non-holiday comparison
- Correlation heatmap

## Key Insights

- Weekly Walmart sales average around 45–50 million dollars.
- Major spikes occur during holiday periods such as Thanksgiving and Christmas.
- Store performance varies significantly, with top stores generating up to 4x the revenue of the lowest performing stores.
- Economic indicators such as CPI and fuel prices show weak correlation with weekly sales.
- Holiday weeks generate noticeably higher sales compared to regular weeks.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook