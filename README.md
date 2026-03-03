# sales_analytics
# Project: Sales & Logistics Data Analytics

This repository contains a comprehensive data analysis project focused on exploring retail performance, logistics efficiency, and geographic market trends. The analysis is performed using **Python** within a Jupyter Notebook environment.

The primary goal of this project is to transform raw sales and logistics data into actionable business insights. The workflow includes:

**Data Cleaning:** Handling missing values in columns like `Units Sold` and `Country Code` using statistical imputation and placeholder values.

**Feature Engineering:** Calculating new metrics such as `order_revenue`, `order_cost`, `order_profit`, and `ship_days`.

**Exploratory Data Analysis (EDA):** Visualizing distributions of sales and profit per order.
 
**Strategic Insights:** Analyzing performance across product categories, geographic regions (primarily Europe), and sales channels (Online vs. Offline).

## File Structure

**Sales_Analytics.ipynb** The main Python notebook containing the data cleaning, analysis, and visualizations.

**countries.csv** Dataset containing geographic information for 249 countries, including regions and sub-regions.

**events.csv** Transactional data with 1,330 rows covering order dates, shipping dates, quantities, and pricing

**products.csv** Catalog mapping product IDs to specific item types like Cosmetics, Office Supplies, and Fruits.


## Technical Stack

**Language:** Python 

**Libraries:** **Pandas:** Data manipulation and merging. **Matplotlib & Seaborn:** Advanced data visualization and multi-panel plotting. **DateTime:** Temporal analysis for shipping durations and seasonality.
