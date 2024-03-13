# Tableau-practice-assigniments

# Assigniment :- 1
1. Open Tableau, and connect to the Excel workbook "SourceDataf.xlsx", and the Excel spreadsheet "CDs".
2. Create a viz which shows a bar chart the smallest file size per "File Extension". (There are 3 File Extensions - I want the smallest file size for each of these file extensions.) 
3. Create another viz which shows a line chart with Years and Quarters in the Columns shelf, and the Minimum of the "#" field in the Rows shelf.

# Assigniment :-2
1. Connect to the HPIAdmins spreadsheet in the SourceData workbook. 
2. Hide all of the fields except Date, Region Name, Index and 12m%Change. 
3. Ensure that Date is a Date field, Region Name is a String field, and Index and 12m%Change are number fields.
4. Rename 12m%Change as "12 month percentage change", and change its default aggregation to Average.
5. Create a viz (a line chart) which shows, for each RegionName, the average 12 month percentage change per year.
6. Color the lines according to the RegionName.
7. Duplicate the viz, and change it to a circle display.
8. Add the average of the Index as the size.

# Assigniment :-3
1. Connect to the HPIRegions spreadsheet (note: not the HPIAdmin spreadsheet) in the SourceDataf workbook. 
2. Create a folder for the fields starting "Detached", and move them into that folder.
3. Create a viz (stacked bar chart) showing the Date going along the bottom (Year, then Quarter), the Sum of the SalesVolume as the bars, and the RegionName being the color.
4. Highlight the West Midlands Region.
5. Add a filter using the RegionName, add a filter card, and exclude "London" and "England".
6. Create a new shape viz, with SalesVolume running along the bottom, Average of AveragePrice running up the graph, RegionName being the color, and Average of 12m%Change being the size. Exclude London and England.
7. Add the Date to the Page card, using the Year and Quarter.
8. Add labels showing the Minimum and Maximum of the Average of 12m%Change.
9. Add an annotation in the bottom-right corner saying "House Price inflation by region."
