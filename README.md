# Blinkit Sales Analysis – Excel Project

## Project Overview  
A detailed Excel dashboard project analyzing Blinkit's sales data to gain insights into sales performance, customer satisfaction, and product distribution. This project focuses on cleaning raw data, creating KPIs, and building visualizations using Excel pivot tables and charts.

## Business Questions  
- What is the overall and average sales performance?  
- Which item types and outlet types contribute the most to sales?  
- What is the average customer rating per item?  
- How does fat content affect sales across different outlets?  
- What is the performance distribution across outlet sizes and locations?


## Process

## 1. Data Loading & Preparation
- Loaded dataset (CSV format) into Excel.
- Formatted the raw data into a table for better structure.
- Reviewed data columns and row count.

## 2. Data Cleaning
- Standardized *Fat Content* values:
  - Replaced `"LF"` and `"low fat"` with `"Low Fat"`.
  - Replaced `"reg"` and `"Regular"` with `"Regular"`.
- Checked for missing/null values:
  - Handled nulls in non-mandatory fields (e.g., `Item Weight`, `Average Rating`).
  - Ensured no blanks in critical fields like `Date` and `Sales`.
- Renamed columns for better clarity (e.g., `Item_Outlet_Sales` → `Sales`, `Outlet_Identifier` → `Outlet ID`).
- Converted rating and sales columns to appropriate number format.

## 3. KPI Calculation Using Pivot Tables
Created a pivot table with the following KPIs:
- **Total Sales** → Sum of `Sales`.
- **Average Sales** → Average of `Sales`.
- **Number of Items Sold** → Count of `Item Identifier`.
- **Average Rating** → Average of `Rating`.

## 4. Dashboard Design
- Created a new sheet named `Dashboard`.
- Turned off gridlines and added a rectangle shape as background.
- Designed 4 KPI cards using formulas and linked text boxes.
- Applied theme colors and clean formatting.

## Data Analysis & Visualizations

## 1. KPIs Cards  
- Total Sales  
- Average Sales  
- Number of Items Sold  
- Average Customer Rating  

## 2. Donut Chart – Fat Content Distribution  
- Shows sales percentage split between `Low Fat` and `Regular` items.

## 3. Bar Chart – Sales by Item Type  
- Highlights top-performing product categories like `Fruits/Vegetables` and `Snacks`.

## 4. Bar Chart – Sales by Outlet Location  
- Evaluates which city types (e.g., Tier 1, Tier 2, Tier 3) perform best.

## 5. Area Chart – Sales by Outlet Size  
- Identifies sales trends across different outlet sizes.

## 6. Column Charts – Metrics by Outlet Type  
- Visualizes total sales, average sales, and number of orders per outlet type.

## 7. Donut Chart – Sales by Outlet Establishment Year  
- Analyzes outlet performance based on establishment age.

## 8. Bar Chart – Ratings Distribution  
- Displays number of orders received per rating (1 to 5).

## 9. Slicers  
- Added slicers for `Item Type`, `Outlet Type`, and `Location` to make the dashboard interactive.


### Key Insights

## Sales & Orders:
- **Tier 3 locations** had the highest sales (~₹0.47M) and number of orders (3350).
- **Supermarket Type 1** outlets led in both total sales (₹787.5K) and number of orders (5577).

## Product Categories:
- **Top categories**: `Fruits/Vegetables` and `Snack Foods`.
- **Lowest performing**: `Seafood` (₹0.01M, 64 orders).

## Customer Ratings:
- **Average Rating**: ~4/5.
- **Most orders** received a rating of 4 or 5.

## Miscellaneous:
- **Average sale per order**: ~₹141.
- **Fat content**: 64% of products sold were `Regular`.


## Dashboard ![blinkit sales analysis](https://github.com/user-attachments/assets/d0170c11-cabc-46c4-9f2b-7a547e36860a)


