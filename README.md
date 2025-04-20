# Store-data-analysis-using-MS-excel
Microsoft Excel project


Hi there! This repository holds my data analysis project focusing on Vrinda Store's sales data which is an e-commerce seller, conducted entirely within Microsoft Excel. Following a guided tutorial, I cleaned, processed, and analyzed the sales data to identify key trends and performance indicators, culminating in an interactive dashboard. This project highlights my skills in leveraging Excel for comprehensive data analysis and reporting.


## Project Goal
The main aim of this project was to analyze Vrinda Store's 2022 sales data to understand customer behavior, identify top-performing categories and sales channels, and visualize key metrics through an interactive dashboard. The insights derived can help the store make data-driven decisions.


## Dataset
The analysis utilized sales data for Vrinda Store, contained within the 'Vrinda Store' sheet of the Excel file. The dataset includes detailed information about orders
(it is uploaded as a csv file in this repository)

## Project Workflow & Excel Techniques
I performed the end-to-end analysis using various Microsoft Excel features:

### 1. Data Loading & Preparation:
- Loaded the raw sales data into Excel.

- Data Cleaning: Checked for inconsistencies, blank cells, and errors. Ensured data types were appropriate for analysis (e.g., formatting 'Amount' as currency, 'Date' as Date type).

- Data Transformation: Added helper columns if necessary (e.g., extracting 'Month' from the 'Date' column, creating 'Age group' from 'Age').


### 2. Data Analysis with PivotTables:
Created multiple PivotTables (evident from the 'Pivot table' sheet) to summarize the data and uncover insights. Key analyses included:
- Total Orders and Sales Amount per Month.

- Sales contribution by Gender and Age Group.

- Order count and Sales Amount by Sales Channel (Myntra, Ajio, Amazon, etc.).

- Top-selling Product Categories (kurta, Set, etc.) by Quantity and Amount.

- Sales performance by State and City.

- Order status breakdown (Delivered, Cancelled, Returned, Refunded).

Alse used aggregation functions like `COUNT` (for Order ID, Cust ID) and `SUM` (for Amount, Qty) within the PivotTables.


### 3. Data Visualization with PivotCharts:
Generated PivotCharts from the PivotTables to visually represent the findings.

- Selected appropriate chart types:

  - Column/Bar Charts: For comparing sales across different channels, categories, states, or age groups.

  - Line Charts: To show trends in orders or sales amount over months.

  - Pie Charts: To illustrate the proportion of sales by gender or order status.
 

### 4. Also formatted charts by adding titles, data labels, and removing unnecessary clutter for clarity.
Interactive Dashboard Creation:
- Designed the 'Vrinda store report' sheet to serve as the central dashboard.

- Arranged the created PivotCharts and key metrics (potentially using cards or text boxes linked to PivotTable data) onto the dashboard sheet.

- Inserted Slicers for key dimensions like 'Month', 'Channel', 'Category', 'Size', and 'Age group' to allow users to dynamically filter the entire dashboard.

- Ensured Slicers were connected to all relevant PivotTables/Charts on the dashboard (Slicer > Report Connections).



## Key Analyses & Insights Visualized
The final dashboard provides insights into:
- Overall Sales Performance: Total revenue and number of orders for the year (or period analyzed).

- Monthly Trends: Identification of peak sales months.

- Customer Demographics: Sales contribution breakdown by gender and age group (e.g., Women vs. Men, Adult vs. Teenager vs. Senior).

- Channel Performance: Which sales channels (Myntra, Ajio, etc.) drive the most orders and revenue.

- Product Insights: Which product categories are Top-selling

- Geographical Distribution: Top contributing states and cities to sales.

- Order Fulfillment: Overview of order statuses (Delivered, Cancelled, etc.).



## Technologies Used
Microsoft Excel: Utilized exclusively for data cleaning, analysis, visualization, and dashboard creation.

Excel Features: Tables, PivotTables, PivotCharts, Slicers, and potentially basic Excel functions.
