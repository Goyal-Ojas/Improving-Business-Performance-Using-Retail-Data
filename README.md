# Improving-Business-Performance-Using-Retail-Data
Project Overview
This project demonstrates how data analytics can be leveraged to improve business operations for a retail company. Using real-world sales data from 2010 to 2018, we performed data cleaning, analysis, and visualization to extract actionable insights. A Tableau dashboard was created to present findings and forecast future trends.

Steps Followed

1. Data Understanding and Cleaning
- Loaded the dataset containing `item_code`, `date`, `quantity`, and `unit_price`.
- Converted the `date` column to datetime format for time-series analysis.
- Checked for missing values in the dataset (none found).
- Identified anomalies:
  - Negative quantities were treated as returns.
  - Rows with negative unit prices were removed as data errors.
- Created a new column, `total_sales`, calculated as quantity x unit price.

2. Data Analysis
a. Aggregated Sales Data
- Grouped sales data by date to analyze daily revenue trends.
- Aggregated monthly sales data to identify seasonal patterns.

b. Top-Performing Items
- Identified the top 10 items contributing the most revenue by summing their total sales.

c. Seasonal Trends
- Analyzed monthly sales trends over the years to detect seasonality and peak sales periods.

3. Business Insights
a. Revenue Insights
- Promoted top-performing items to maximize revenue.
- Investigated underperforming items for potential pricing or marketing adjustments.

b. Inventory Optimization
- Used seasonal trends to optimize inventory planning during peak sales periods.

c. Return Analysis
- Reduced returns by addressing frequently returned products or operational inefficiencies.

4. Tableau Dashboard Creation
a. Data Preparation
- Exported cleaned and aggregated datasets into CSV files for Tableau:
  - `cleaned_data.csv` (daily sales data).
  - `monthly_sales.csv` (aggregated monthly sales).

b. Dashboard Components
1. Line chart showing daily sales trends.
2. Bar chart highlighting top-performing items.
3. Heatmap visualizing monthly sales trends over multiple years.
4. Interactive filters for year, item code, and other dimensions.

5. Future Forecasting in Tableau
- Used Tableau's built-in forecasting feature on the monthly sales dataset:
  - Created a line chart of monthly sales over time.
  - Applied exponential smoothing models to predict future trends.
  - Customized forecast settings (e.g., confidence intervals).

6. Measuring Improvements
Key metrics used to measure business improvements:
1. Increase in total revenue after implementing recommendations.
2. Reduction in returns (negative quantities).
3. Improved inventory turnover during peak seasons.

Tools Used
1. Python: For data cleaning, transformation, and analysis.
2. Tableau: For creating interactive dashboards and performing forecasting.

How to Use This Project
1. Download the dataset (`benchmark.csv`) and Python scripts from this repository.
2. Follow the Python script to clean and preprocess the data.
3. Import the cleaned CSV files into Tableau for visualization.
4. Explore the Tableau dashboard to gain insights and view forecasts.

This project showcases how data-driven decisions can improve retail operations, optimize inventory, and boost profitability!
