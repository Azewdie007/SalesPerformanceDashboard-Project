# SalesPerformanceDashboard-Project

#### Dashboard Link: https://app.powerbi.com/groups/me/reports/fe18f651-2f49-4aff-9247-6998ab6e0a55?ctid=c5063431-d7f2-48db-ac62-eaeaa2e0bffc&pbi_source=linkShare

## Problem Statement

This project demonstrates the data lifecycle such as cleaning, storing, and processing data to create an effective ETL (Extract, Transform, Load) process and an interactive Power BI dashboard. The goal is to analyze the Superstore Sales Dataset to provide actionable insights into sales performance across regions, states, products, and time, helping businesses optimize sales strategies and identify top performing areas.

### Steps Followed

- **Step 1**: Performed a statistical analysis and data cleaning using python in jupiter notebook then Loaded the Superstore Sales Dataset (CSV file) into Power BI Desktop.

- **Step 2**: Opened Power Query Editor and, under the View tab, enabled "Column Distribution," "Column Quality," and "Column Profile" to assess data quality.
- **Step 3**: Selected "Column profiling based on entire dataset" to analyze all rows.
- **Step 4**: Identified and handled missing values. In this case there was 11 missing zipcodes which were irrellevant to this analysis. 
- **Step 5**: Cleaned and transformed data by standardizing dates and checking for duplicates using Power Query.
- **Step 6**: Loaded the transformed data into Microsoft SQL Server Management Studio (SSMS) for structured querying.
- **Step 7**: In Power BI Report View, applied a consistent theme under the View tab.
- **Step 8**: Added slicers for interactivity, filtering by Region, Category, Sub-Category, Year, Month, and Quarter.
- **Step 9**: Created KPI cards to display Total Sales ($2.3M), Total Orders (4,922), Customers (793), and Transactions (9,800) using DAX measures. This numbers display the appropriate data based on the filter tab as well.
- **Step 10**: Designed a Shape Map to visualize Sales by State, with tooltips showing Total Sales and Sales Percentage.
- **Step 11**: Added a Donut Chart to represent Sales Total by Region.
- **Step 12**: Included a Bar Chart for Top 5 Products by Sales and a Line Chart for Sales Total by Month.
- **Step 13**: Added a text box with the title “Sales Performance KPI Dashboard” and a footer noting “Data Source: Superstore Sales Dataset, Processed in Python/SSMS, Visualized in Power BI.”
- **Step 14**: Published the dashboard to Power BI Service using the provided link.


## Insights
A single-page interactive report was created in Power BI Desktop and published to Power BI Service. Key findings include:

### [1] Key Performance Indicators
- Total Sales: $2.3M
- Total Orders: 4,922
- Customers: 793
- Transactions: 9,800

### [2] Regional Sales Distribution
- West Region: 31.4% of total sales
- South Region: 29.6% of total sales
- East Region: 21.7% of total sales
- Central Region: 17.3% of total sales
- Insight: The West region is the top contributor, with California likely leading among states.

### [3] Top Products
- Canon imageCLASS dominates sales (~60K), followed by Fellowes PB500 (~40K).
- Insight: Focus on promoting top products to boost overall revenue.

### [4] Monthly Trends
- Sales peak in October (~0.4M), indicating seasonality.
- Insight: Plan marketing or inventory adjustments around peak months.

### [5] Data Quality
- Handled 11 missing zip codes (filled with 'Unknown'), ensuring data integrity.
- No significant duplicates or errors detected.

These insights can be filtered dynamically using the provided slicers, offering real-time analysis.

## Tools Used
- **Programming Languages**: Python, SQL
- **ETL Tools**: Jupyter Notebook, SSMS, Power Query
- **Visualization Tool**: Power BI

## Skills Demonstrated
- Data Cleaning and Transformation (ETL)
- SQL Database Management
- DAX and Power BI Visualization
- Interactive Dashboard Design


