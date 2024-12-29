# Amazon Sales Dashboard

## Project Objective  
Analyzed Amazon sales data to uncover key insights and trends across different segments, markets, and regions using Power BI.  

## KPI Metrics  
- **Returns**: 1,466  
- **Sales Projection**: $2.64M  
- **Product Units Sold**: 3,788  
- **Total Sales**: $178K  

## Visualizations  
1. **Sales by Segment** (Pie Chart):  
   - Consumer: 51.48% (highest)  
   - Corporate: 30.25%  
   - Home Office: 18.27%  

2. **Sales by Market** (Donut Chart):  
   - Asia Pacific: 31.98% (highest)  
   - Europe: 26%  
   - USCA: 18.7%  
   - LATAM: 2.16%  
   - Africa: Lowest  

3. **Sales by Region** (Map Visual).  
4. **Profit by Customer Name** (Stacked Column Chart):  
   - Tamara: Highest profit  
   - Tom: Lowest profit  

5. **Top 5 Products by Profit** (Clustered Bar Chart):  
   - **Best:** Canon ImageClass ($25K)  
   - **Least in Top 5:** Sauder Classic Bo ($11K)  

6. **Bottom 5 Products by Profit** (Clustered Bar Chart):  
   - **Worst:** Cubify CubeX (-$8.9K)  
   - Bevis Round Tab (-$3.6K)  

7. **Slicers**: Years (2012–2015)  

## Process  
1. **Data Connection**: Connected to the database and analyzed tables/relationships.  
2. **Data Cleaning**:  
   - Used Power Query Editor to clean data (e.g., converted headers, removed null values).  
   - Created custom columns:  
     - **Delivery Date** = Order Date - Ship Date  
     - **Year** = Extracted using `Date.Year(Order Date)`  
     - Converted `Returns` (Yes/No) to numeric using a conditional column.  
3. **Visualizations**: Created and formatted visuals (e.g., added Amazon logo).  
4. **Publishing**: Published the report to Power BI Service and pinned the live dashboard.  

## Insights  
- **Segment Analysis**: Consumer segment has the highest sales (51.48%).  
- **Market Trends**: Asia Pacific contributes the most sales (31.98%).  
- **Customer Insights**: Tamara generates the highest profit, while Tom generates the least.  
- **Product Trends**:  
   - Best Product: Canon ImageClass ($25K profit).  
   - Worst Product: Cubify CubeX (-$8.9K profit).  

## Dashboard Link  
[View Dashboard](https://github.com/Vinitha-dotcom/Data-Analysis-Dashboard)

