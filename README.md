# Superstore Sales Dashboard (Excel)

An interactive Excel dashboard analysing the Superstore sales dataset: sales, profit and margin by region, category, year and month.

![Dashboard](dashboard.png)

## Objective
Find out where the business makes and loses money, and which regions, categories and months drive sales.

## Dataset
- Superstore Sales dataset (public, from Kaggle)
- Rows: [ADD YOUR ROW COUNT]
- Key columns: Order Date, Region, Category, Sales, Quantity, Discount, Profit

## What I did
1. **Cleaned the data:** removed duplicates, checked blanks, confirmed date formats.
2. **Added helper columns:** Year, Month, Month No, Profit Margin %.
3. **Built 4 Pivot Tables:** sales and profit by Region, by Category, yearly sales, monthly sales.
4. **Made PivotCharts** for each pivot and combined them on one Dashboard sheet.
5. **Added KPI cards** (Total Sales, Total Profit, Profit Margin) using `GETPIVOTDATA`, so they update with the filters.
6. **Added slicers** for Region and Year, connected to all four pivots.

## Key insights
- **Furniture earns only about a 2.5% profit margin**, compared with about 17% for Office Supplies and Technology, even though its sales are almost as high.
- **West has the highest sales and the best margin (about 15%).** Central has the lowest margin (about 8%).
- **Sales grew about 52% from 2011 to 2014**, with a small dip in 2012.
- **October to December bring about 38% of yearly sales**, so there is a strong year-end peak.

## Tools used
Microsoft Excel: Tables, Pivot Tables, PivotCharts, Slicers, GETPIVOTDATA, IFERROR

## Files
- `Superstore_Dashboard.xlsx`: the full workbook with the dashboard
- `dashboard.png`: screenshot of the dashboard
- `README.md`: this file

## How to use
Download the workbook, open the **Dashboard** sheet, and click the Region and Year slicers to filter all charts and KPI cards.

## Author
Praveen Kumar Dola | [LinkedIn](https://linkedin.com/in/praveen-kumar-dola) | [GitHub](https://github.com/praveen-kumar21-pk)
