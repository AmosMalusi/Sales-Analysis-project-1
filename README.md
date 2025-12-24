# Sales Performance Analysis Dashboard

## Project Overview
This project focuses on analysing retail sales data to understand overall business performance, identify top and underperforming products and regions, and highlight opportunities for improvement. The aim is to turn raw transactional data into clear, decision-ready insights.

The project follows an end-to-end data analytics PACE workflow, from data cleaning and analysis to visualisation and insight generation.

## Business Problem
The business needs a clear view of:
- Which products and regions are performing well
- Which areas are underperforming
- What factors are driving sales and profit

Without this visibility, it becomes difficult to make informed decisions around pricing, inventory, and regional strategy.

## Objectives
- Clean and prepare raw sales data
- Calculate key performance indicators (KPIs)
- Analyse relationships between sales, profit, discounts, and other variables
- Identify best and worst performing products and regions
- Present insights in a clear and interactive dashboard

## Data Source
The dataset used in this project is a retail sales dataset from Kaggle containing information on:
- Orders and sales
- Profit and discounts
- Products and categories
- Regions and dates

(The dataset was sourced from a publicly available dataset and used for learning and portfolio purposes.)

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scipy, statsmodels.api, statsmodels.formulas.api)
- **VS Code** for analysis and documentation
- **Power BI** for dashboard creation
- **GitHub** for version control and project sharing

## Analysis Performed
- Data cleaning and preprocessing
- Handling missing values and outliers
- Exploratory Data Analysis (EDA)
- KPI creation (Sales, Profit, Profit Margin, Order Volume)
- Correlation analysis
- Regression analysis to understand key drivers
- Hypothesis and ANOVA
- Identification of underperforming segments

## Dashboard Output
The final dashboard highlights:
- Total sales and profit performance
- Best and worst performing products
- Regional performance comparison
- Insights that can support business improvement strategies

### Dashboard first page
Sales Overview Dashboard
<img width="824" height="464" alt="Screenshot 2025-12-15 161652" src="https://github.com/user-attachments/assets/0b5dde64-fcc4-4775-a860-0df70583c483" />

This Power BI Sales Performance Dashboard provides a clear executive overview of business performance through key KPIs, including total sales of $2.06M, total profit of $319.74K, 7,724 total orders, and a profit margin of 15.49%. The dashboard highlights underperforming products while allowing users to filter results by region, category, segment, and year for targeted analysis. Visual comparisons show that Office Supplies generate the highest sales, while Technology and Furniture contribute smaller but meaningful profit shares. The monthly trend line reveals steady growth in both sales and profit toward the later months of the year, indicating improving performance over time. Regional analysis shows that Central, South, and North regions lead in sales, while regions such as Canada and the Caribbean lag behind. Overall, the dashboard is designed to support data-driven decision-making by clearly identifying strengths, weaknesses, and opportunities for performance improvement.

Underperforming products dashboard
<img width="834" height="471" alt="Screenshot 2025-12-15 161924" src="https://github.com/user-attachments/assets/f459c7c5-5b35-487d-8207-049720f71c7f" />

This Power BI dashboard focuses specifically on underperforming products, providing a targeted view of areas that require managerial attention. The KPIs show low overall performance, with total sales of $90, total profit of $34.65, 98 orders, and a relatively high profit margin of 34.65%, suggesting low volume but strong margins. Regional analysis indicates that the West and East contribute more to underperforming sales compared to Central and South regions. The segment breakdown reveals that the Consumer segment accounts for the largest share of underperformance, followed by Corporate and Home Office. Product-level visuals clearly highlight the weakest-performing items, making it easier to identify candidates for discontinuation, repricing, or promotion. Overall, the dashboard supports strategic decision-making by pinpointing exactly where and why certain products are failing to perform.


## Key Insights
- A small number of products and regions contribute a large share of total profit
- Discounts have a noticeable impact on profitability
- Underperforming regions show patterns that can be addressed through targeted strategies

## How to Use This Project
1. Review the analysis notebooks/scripts for data preparation and analysis
2. Explore the Power BI dashboard for visual insights
3. Read the documentation to understand the analytical decisions made

## Notes
This project was created for learning and portfolio purposes to demonstrate practical data analytics skills, structured thinking, and business-focused insights.
