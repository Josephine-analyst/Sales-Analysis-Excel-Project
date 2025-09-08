# SALES ANALYSIS PROJECT

## PROJECT DESCRIPTION
   This project aims at enabling stakeholders to monitor key sales metrics, identify trends and make data-driven to optimize revenue and 
   operational efficiency.

### SOFTWARE USED
    * MICROSOFT EXCEL

### STEPS FOLLOWED
    * Step 1: Load the data using Microsoft Excel, dataset is an xlsx file.
    * Step 2: Convert the dataset to a table format
               Select the data range, go to insert>Table and give the new table a name "Sales Table".
    * Step 3: Add Calculated Columns
               - Average Sales=AVERAGE(K:K)
               Extracting the year, month and day from the month column
               - Year=YEAR([@Month])
               - Month=TEXT([@Month],"mmmm")
               - Day=TEXT([@Month],"dddd")
    * Step 4: Key Performance Indicator
               - Total Average Sales=SUM(DATASET!L:L)

### CREATE PIVOT TABLES FOR ANALYSIS
    1. INSERT PIVOT TABLES
       * Go to insert>Pivot Table, select "Salestable" as the source and place each pivot table on a new sheet.
       * Create separate pivot tables for:
         - Average of sales in each year by state
         - Top five Suburb
         - Top ten average sales by category from 2016-2018
         - Top ten best selling manager
         - Percentage of sales by each month
         - Five best selling days of the year.

### CONFIGURE PIVOT TABLES
    * Average of sales in each year by state
      - Row: State
      - Column: Financial Year
      - Values: Sales
      

    * Top five suburb
      - Row: Suburb
      - Filter: Financial Year
      - Values: Sales
      

    * Top ten average sales by category from 2016-2018
      - Row: Category'
      - Column: Financial Year
      - Values: Average Sales
      

    * Top Ten best selling manager
      - Row: Manager
      - Column: Financial Year
      - Values: Sales
     

    * Percentage of sales by each month
      - Row: Month2
      - Values: Sales
      

    * Five best selling days of the year
      - Row: Day
      - Column: Year
      - Values: Financial Year
      
### BUILD VISUALIZATIONS
    1.  Average of sales in each year by state <Column Chart>
        This analysis covers yearly sales performance, state comparisons and regional patterns. In 2015 NSW led with an average of $867, 
        followed by VIC at $737.
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/0563a6ab-bea5-4f7f-bddf-d89cd414671f" />

    2.  Top five Suburb <Bar Chart>
        Helps to analyze how different suburbs contribute to overall sales. This helps to identify high-performing regions and areas that
        may need more attention.
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/e0be40fd-0a97-405b-b43e-2d6deb76e00a" />

    3. Top Ten average sales by Category <Column Chart>
       It analyzes which product categories contribute most to revenue. From 2016-2018 Shoes contributed the most to revenue ($1,189),
       topping the list of top ten average sales by category.
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/cb7174c4-cfa5-4c04-884e-d5f06df19cf0" />

    4.  Top Ten best selling manager <Stacked Column Chart>
        It evaluates sales performance at the individual level. It helps to identify the top ten best selling manager.
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/ed3e844f-b77b-4bc1-8036-f564d292267e" />

    5.  Percentage of sales by each month <Stacked Line Chart>
        It helps to understand seasonal trends and forecast demand, compare across months see consistency.
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/31543af6-f213-4ddd-a207-469d2035f86b" />

    6.  Best five selling days of the year < Column Chart >
        It helps to find the days that generated the highest sales. Useful for identifying successful campaigns or seasonal surges.
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/40233bd1-7b47-4192-80e4-201d1625040c" />


### ADD INTERACTIVITY WITH SLICER
    1. Insert Slicer
       - select any pivot table, go to insert>slicer and choose 'Financial Year'.
       
    2. Connect slicer to all pivot tables:
       - Pivot table Analyze>Report connections, select all relevant pivot tables.
       - Adjust layout for a clean look.

### DESIGN THE DASHBOARD
    1. Create a Dashboard sheet:
       - Insert a new sheet named "Dashboard".
       - Move Charts and KPIs to this sheet by copying and pasting.
       - Arrange charts for clarity; KPIs at the top , charts below.

    2. Enhance Visuals
       - Add a title "Sales Analysis Dashboard"
       - Hide gridelines (view>gridelines) for a cleaner look.

### KEY INSIGHTS
    1. NSW consistently has the highest average sales ($867 in 2015 and $971 in 2016) compared to VIC ($737 in 2015 and $824 in 2016) 
       and NT ($665 in 2015 and $791 in 2016).
    2. ACT has the lowest average sales in 2016/17.
    3. Campbelltown cosistently has the highest sales ($1,716,158) compared to other suburbs.
    4. Shoes has the highest sales in 2016/17, topping the list of top ten average sales by category.
    5. The months of March and August accounts for the highest percentage of annual sales(11%), while October and November
       recorded the lowest percentage of annual sales(5%).

### CONCLUSION
    This project effectively highlighted key trends, patterns and outliers in the sales data. By leveraging Excel's robust tools, I
    identified  top performing products, regional sales variations and seasonal trends, enabling data-driven decision-making. These findings
    underscore opportunities for optimizing inventory,refining marketing strategies and targeting underperforming segments.
    



 
