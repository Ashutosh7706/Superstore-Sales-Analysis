# Superstore Sales Analysis and Customer Segmentation

## Project Overview

This project presents an end-to-end data analytics case study using the Superstore dataset. It combines SQL-based data analysis, interactive Power BI dashboard development, exploratory data analysis (EDA), and machine learning-based customer segmentation using Python.

The objective is to uncover sales trends, identify profitable products and customer segments, evaluate discount strategies, and generate actionable business insights to support data-driven decision-making.

## Objectives

- Identify the most profitable products, categories, regions, and customers.
- Analyze sales and profit trends across different business segments.
- Understand the impact of discounts on overall profitability.
- Develop an interactive Power BI dashboard for business reporting.
- Segment customers based on purchasing behavior using RFM analysis and K-Means clustering.

## Dataset Overview

**Dataset:** [Superstore Dataset – Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The dataset was organized into four structured CSV files:

| File | Description |
|---|---|
| `customers.csv` | Customer-related information |
| `orders.csv` | Order details and dates |
| `order_details.csv` | Sales, quantity, discount, and profit |
| `products.csv` | Product categories and sub-categories |

## Tools and Technologies

- **SQL:** MySQL, phpMyAdmin
- **Business Intelligence:** Power BI
- **Programming:** Python, Jupyter Notebook
- **Libraries:** Pandas, Seaborn, Matplotlib, Scikit-learn
- **Analytics Techniques:** Exploratory Data Analysis, RFM Analysis, K-Means Clustering, Data Visualization

## Project Workflow

### Phase 1: SQL-Based Business Analysis

- Created relational database tables from structured CSV files.
- Developed SQL queries to calculate sales, profit, and profit margins.
- Identified top-performing products and customers.
- Analyzed category-level and regional profitability.
- Evaluated the relationship between discounts and profitability.

### Phase 2: Interactive Power BI Dashboard

- Connected MySQL database to Power BI.
- Developed KPI cards to monitor key business metrics.
- Created sales trend charts and profit margin visualizations.
- Added interactive slicers for region, customer segment, and order month.
- Implemented navigation and back buttons using Power BI bookmarks.

### Phase 3: Exploratory Data Analysis (Python)

- Loaded and explored the dataset using Pandas.
- Performed data analysis to understand distributions and patterns.
- Created histograms, boxplots, and correlation heatmaps.
- Validated SQL findings through Python-based analysis.
- Examined outliers and discount-related trends.

### Phase 4: RFM-Based Customer Segmentation

- Calculated Recency, Frequency, and Monetary (RFM) metrics.
- Prepared and normalized customer-level data.
- Applied K-Means clustering to identify customer groups.
- Analyzed and labeled segments such as Loyal, Lost, and Potential Customers.
- Exported customer segmentation results for reporting and visualization.

## Business Value and Key Applications

- **Customer Retention:** Identifying valuable customers and customers at risk of disengagement.
- **Profitability Analysis:** Understanding which products and categories contribute most to profits.
- **Discount Optimization:** Evaluating discount strategies to reduce potential profit losses.
- **Marketing Strategy:** Supporting targeted marketing through customer segmentation.
- **Business Intelligence:** Converting raw business data into interactive dashboards and actionable insights.

## Project Structure

```text
Superstore-Sales-Analysis/
│
├── Dataset/
│   ├── customers.csv
│   ├── orders.csv
│   ├── order_details.csv
│   └── products.csv
│
├── SQL/
│   └── SQL_Analysis.sql
│
├── Python/
│   └── Customer_Segmentation.ipynb
│
├── PowerBI/
│   └── Superstore_Dashboard.pbix
│
└── README.md
```

*Note: Adjust the folder and file names above to match your actual repository structure.*

## Author

**Ashutosh Soni**  
B.Tech – Biomedical Engineering | Minor in Computer Science  
National Institute of Technology, Rourkela

- **GitHub:** [Ashutosh Soni](https://github.com/Ashutosh7706)