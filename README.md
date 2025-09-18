# Super-Store-Sales-Dashboard

1.Project Overview

 This Super Store Sales Dashboard provides a complete view of business performance using Excel sales data as the source.
 
It highlights key KPIs, shipping mode performance, customer segment analysis, and year-over-year growth, helping stakeholders make data-driven decisions.

2.Dashboard Objectives

  Track Total Sales, Total Profit, and Total Orders with interactive KPI cards.
  
  Visualize profitability and sales distribution by shipping mode.
  
  Analyze customer segment performance (sales, profit, and order count).
  
  Measure Year-over-Year (YoY) growth for both sales and profit.
  
  Enable drill-down and filtering by time period (Year, Quarter, Month), Region, and Segment.

3.Tech Stack

  Power BI Desktop - Main data visualization platform used for report creation.
  
  File Format - .pbix for develompment and .png dashboard previews.
  
  Power Query - Data transformation and cleaning layer for reshaping and perperig the data.
  
  Data Modeling - Releationships estalished among tables(order,peopele).

4.Dataset

  File Name: Super store.xlsx
  
  Sheet Used: Orders
  
  Total Records: ~10,000 rows
  
  Key Columns: Order Date, Order ID, Sales, Profit, Quantity, Ship Mode, Region, Segment, Category, Sub-Category

5.Visuals

  Profit by Ship Mode – Bar chart showing profit contribution of each shipping mode
  
  Sales by Ship Mode – Revenue distribution by shipping mode
  
  Orders by Segment – Segment-wise order count (Consumer, Corporate, Home Office)
  
  Sales & Profit by Segment – Combined bar chart comparing revenue vs profit
  
  YoY Sales & Profit – Line chart showing growth trend over years

6.Filters / Slicers

  Year, Quarter, Month, Region, Segment
  
7.KPI Cards

  Total Sales – Total revenue from all orders
  
  Total Profit – Overall profit
  
  Total Orders – Distinct order count

8.Key Insights

  Standard Class shipping is the most profitable and widely used mode.
  
  Consumer segment accounts for the majority of orders and revenue.
  
  YoY analysis shows steady growth in sales and profit, with peak demand in Q4.
  
  Certain sub-categories show negative profit despite high sales → review pricing strategy.

9.Future Enhancements

  Automate Excel data refresh (connect to live data source if available).
  
  Add category-level drill-through pages.
  
  Implement trend forecasting using Power BI visuals.
