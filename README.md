# **Overview**

This Power BI dashboard provides an in-depth analysis of sales data for the "Adventure Works" dataset. The report leverages DAX formulas, interactive visuals, and slicers to explore trends and performance metrics. Designed for decision-makers, this dashboard offers insights into total sales, profit margins, and performance by year, quarter, and month.


# **Features**

## **1. Key Metrics**

   + **Total Sales**: 29.36M
 
   + **Profit Margin**: 41.15%
 
   + **Profit by Region**: 12.08M
 
These metrics are calculated using DAX formulas to provide accurate and dynamic results.


## **2. Visuals**

 + **Total Sales by Year** : A pie chart showing the percentage of sales contribution across different years (2010–2014).
 
 + **Sales Amount vs. Product Cost**: A combination of a bar and line chart visualizing sales revenue and product costs over the years.
 
 + **Total Sales by Month**: A bar chart comparing monthly sales trends, with December leading.
 
 + **Total Sales by Quarter**: A donut chart showcasing quarterly sales, with Q4 contributing the highest.
 
 
## **3. Interactive Slicers**

+ **Year**: Filter sales and profit data by specific years.

+ **Quarter**: Analyze data for selected quarters.

+ **Month Name**: Drill down into sales data by specific months.


## **4. Navigation Buttons**
Buttons for navigating between "Sales Insights" and "Products" sections within the report.

## **5. Dynamic DAX Calculations**
DAX measures used for calculating:

+ **Total Sales**: SUM(Sales[SalesAmount])

+ **Profit Margin**: DIVIDE(SUM(Sales[Profit]), SUM(Sales[SalesAmount]), 0)

+ **Profit by Region**: Aggregated profit data by geographical regions.




# **Benefits**

+ **Interactive and Dynamic**: Enables slicing and dicing of data for tailored analysis.

+ **Comprehensive Insights**: Provides year-over-year and month-over-month trends.

+ **User-Friendly Navigation**: Buttons and slicers enhance usability and interactivity.
