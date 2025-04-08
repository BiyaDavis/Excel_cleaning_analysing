# Excel_cleaning_analysing
Importing some data from a department which relates to inventory information about their fleet of vehicles. The data is in comma-separated value (CSV) format and the data also needs cleaning up before doing any kind of analysis.
Link used -
- <a herf="https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr"> under a Public Domain license.

# Tasks Performed for Cleaning the Data
Save the CSV file as an XLSX file
Column widths: Sort out the widths of all columns so that the data is clearly visible in all cells.
Empty rows: Used the Filter feature to look for blanks and removed all empty rows from the data.
Duplicate records: Used the Conditional Formatting or Remove Duplicates feature to look for and removed any duplicated records from the data.
Spelling: The original source file data has not been checked for errors in the spelling. Checked for spelling mistakes in the data and fixed them.
Whitespace: Used the Find and Replace feature to remove all double-spaces from the data.
Department names: When the data was converted from its data source, the department names didn’t import correctly and they are now split over two columns in the data. Use Flash Fill to reduce the department names to just one column, and then removed any unnecessary columns.

# Tasks Performed for Analysing the Data
Format the data as a table: Used the Format as Table option to format the data as a table.
Use AutoSum to calculate values: Used AutoSum to find the following values for column ‘C’ and record each of the values:
SUM, AVERAGE, MIN, MAX, COUNT
Create a Pivot Table: Use the PivotTable feature to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.
Sort the pivot table data: Use the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.
Made two more pivot tables: Created two more identical pivot tables so that it end up with 3 worksheets that contain identical pivot tables.
Analyze data in the pivot table: Use the PivotTable Fields pane to manipulate and analyze data in the two copied pivot table as follows:
  In pivot table 2 added the Equipment Class field below the Department field so that the different vehicle types appear under each department with their 
  respective counts.
  Collapse all fields except the top one - Transportation
  In pivot table 3 added the Equipment Class field above the Department field so that the different vehicle types appear first, with the different departments 
  listed underneath each vehicle type with their respective counts.
  Collapse all fields except the top one - CUV

