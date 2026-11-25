# Blinkit Sales Dashboard (Power BI)

I built this dashboard to practice Power BI on a real-looking retail dataset. It uses grocery sales data from Blinkit, India's quick-commerce app, and turns the raw rows into a one-page report that shows where the sales are coming from. The questions behind it were simple: which products sell the most, which kinds of outlets do best, and how do things change by location and over the years?

## What the dashboard shows

Everything is on a single page, so you can read it in one glance.

- **KPI cards** at the top for Total Sales, Average Sales, Average Rating and Total Items
- **Sales by Item Type** (bar chart) to see which product categories bring in the most
- **Sales by Fat Content** (funnel) to compare Low Fat and Regular items
- **Sales by Outlet Size** (donut chart) to compare small, medium and high-size outlets
- **Sales by Outlet Location Type** (pie chart) to compare Tier 1, 2 and 3 locations
- **Fat Content by Location Type** (clustered bar) to see how the fat content split changes between tiers
- **Sales by Outlet Establishment Year** (line chart) to see the trend over the years
- **Outlet Type summary table** with Total Sales, Average Sales, Average Rating and Total Items for each outlet type
- **Metric slicer** to switch the chart values between measures, so one dashboard can answer more than one question

## Measures I created

I wrote four DAX measures for the cards and the table:

- Total Sales
- AVG Sales
- AVG Ratings
- Total Items

## Dataset

The data is one table called `BlinkIT Grocery Data`. The columns I worked with include Item Type, Item Fat Content, Outlet Size, Outlet Location Type, Outlet Type, Outlet Establishment Year, sales, ratings and item counts.

## What I did, step by step

1. Loaded the data into Power BI Desktop and checked the columns and data types.
2. Cleaned the values, for example making the Item Fat Content labels consistent.
3. Created the DAX measures for sales, average sales, ratings and item count.
4. Built the visuals and picked a chart type that fits each question.
5. Added a slicer so the metric can be switched on the same charts.
6. Styled the page with Blinkit's yellow and green look so it feels like the brand.

## Tools used

Microsoft Power BI Desktop, DAX, and data modelling.

## How to open it

1. Download `Blinkit_Dashboard.pbix` from this repo.
2. Open it with Power BI Desktop (it's free from Microsoft).
3. Click through the slicer and hover over the charts to explore.

## Files

- `Blinkit_Dashboard.pbix` is the Power BI report
- `dashboard.png` is a screenshot of the finished page
- `README.md` is this file

## About me

I'm Om Danej, a BCA graduate from Savitribai Phule Pune University, learning data analytics. This is one of my first dashboards, so any feedback is welcome.
<img width="1599" height="920" alt="WhatsApp Image 2026-11-22 at 8 16 50 AM" src="https://github.com/user-attachments/assets/1deb8acd-857f-408a-a462-83560c720e09" />
