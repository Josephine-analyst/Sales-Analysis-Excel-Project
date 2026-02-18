# SALES ANALYSIS PROJECT

Interactive Excel dashboard analyzing sales performance across regions, products, managers, time periods, and customer locations. Built entirely in Microsoft Excel using pivot tables, calculated columns, slicers, charts, and a consolidated dashboard to uncover trends and support data-driven business decisions.

## PROJECT OBJECTIVES
   - Monitor key sales metrics (average sales, total revenue, transaction volume)
   - Identify top-performing regions, suburbs, product categories, and sales managers
   - Reveal seasonal patterns (monthly & day-of-week trends)
   - Create an intuitive dashboard for quick insights and filtering
   - Provide actionable recommendations for marketing, inventory, and performance optimization

<img width="1366" height="768" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/80a5d905-478d-4cdc-8392-31c395c1911a" />


### TOOLS & TECHNOLOGIES
    - Microsoft Excel (100% of the project – no Power BI, SQL, or external tools)
    - Features used: Tables, Calculated Columns, PivotTables, PivotCharts, Slicers (connected), Dashboard layout
    
### STEP-BY-STEP PROCESS
1. **Data Loading & Preparation**
     - Import raw data into Excel
     - Convert range to Excel Table (Ctrl + T) → name it `SalesTable`

2. **Calculated Columns**
     - Added in table columns (using formulas):
     - `Year` = YEAR([Order Date])
     - `Month` = TEXT([Order Date], "mmmm")
     - `Day` = TEXT([Order Date], "dddd")
     - `Average Sales` = AVERAGE([Sales Amount])

3. **Key KPIs & Summary**
     - Created a summary area with formulas (COUNT, SUM, AVERAGE) for:
     - Total Transactions
     - Total Revenue
     - Average Sales per Transaction

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


### **Slicers & Interactivity**
     - Financial Year slicer connected to **all** pivot tables and charts
     - Allows dynamic filtering across the entire dashboard


## 🔍 Key Insights & Recommendations
    - **Regional Performance**  
        NSW leads average sales ($867 in 2015 → $971 in 2016); VIC and NT follow closely. ACT lags significantly.

    - **Top Locations**  
        Campbelltown is the highest-performing suburb (over $1.7M in sales) — strong market presence here.

    - **Product Categories**  
        Shoes dominate average sales — prioritize inventory and promotions for this category.

    - **Seasonality**  
        March and August are peak months (~11% each of annual sales); October and November are lowest (~5%) — plan inventory/marketing accordingly.

    - **Day-of-Week Trends**  
        Best-selling days identified — optimize staffing/promotions on high-volume days.

 **Business Recommendations**  
   - Focus marketing budget and inventory on NSW, VIC, and Campbelltown  
   - Investigate and support underperforming regions (e.g., ACT)  
   - Stock more Shoes and plan seasonal promotions for March/August  
   - Align sales team training and incentives with top performers

## How to Use / Explore This Project
1. Download or clone the repository
2. Open `SALES ANALYSIS EXCEL PROJECT.xlsx` in Microsoft Excel
3. Enable content/macros if prompted (for slicers)
4. Use the **Financial Year** slicer on the Dashboard sheet to filter all visuals
5. Explore pivot tables and charts on individual sheets for deeper analysis

### Conclusion
   This Excel-based sales analysis project reveals clear patterns in performance across regions, products, sales managers, and time periods. Key findings include:
   - **NSW** consistently leads in average sales (rising from $867 in 2015 to $971 in 2016), followed by VIC and NT, while ACT significantly underperforms.
   - **Campbelltown** stands out as the top-performing suburb (over $1.7M in total sales).
   - **Shoes** dominate average sales among product categories — a clear priority for inventory and promotion.
   - **March** and **August** are peak months (~11% of annual sales each), while October and November are the weakest (~5%).
   - Certain days of the week show stronger sales — ideal for targeted staffing and promotions.



 
