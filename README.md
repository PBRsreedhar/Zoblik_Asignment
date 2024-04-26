#ZOBLIK- Sales & Volume Dashboard 

## Problem Statement

This dashboard helps the sales & Volume at country level and weekly how much volume of products sold.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed having three countries sales data and needs to add country column at specfic data and then appeneded three files created sales table.
- Step 5 : By using dax created data dimension table and given relationship between date dimesion [date] to sales table [date] So that we can filtered sales table by using date dimension table. 
- Step 6 : Visual filters (Slicers) were added for Three fields named "Country", "ProductName", "WeekNumber".
- Step 7 : Top matrix visuals were added to the canvas, one representing Total sales by country level breakdown and also added drill through function by using we can be to see country level sales at detail view and second one representing Volume products sold by weekly.
- Step 8 : A Line chart was also added to the report design area representing the Total sales by weekly & Total running sales by weekly.
