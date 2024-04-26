#ZOBLIK- Sales & Volume Dashboard 

## Problem Statement

This dashboard helps the sales & Volume at a country level and weekly how much volume of products sold.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, the dataset is a CSV file.
- Step 2 : Open the power query editor & in the view tab under the Data Preview section, and check the "column distribution", "column quality" & "column profile" options.
- Step 3 : It was observed having three countries' sales data and needs to add a country column at specific data and then appended three files to create a sales table.
- Step 4 : Using Dax create a date dimension table and give the relationship between the date dimension [date] to the sales table [date], we can filter the sales table by using the date dimension table. 
- Step 5 : Visual filters (Slicers) were added for Three fields named "Country", "ProductName", and "WeekNumber".
- Step 6 : Top matrix visuals were added to the canvas, one representing Total sales by country level breakdown and also added drill through function by using we can to see country level sales at detail view and second one representing Volume products sold by weekly.
- Step 7 : A line chart was also added to the report design area representing the Total sales weekly & Total running sales by weekly.
