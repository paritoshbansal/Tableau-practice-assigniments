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

# Assigniment :-4
1. Connect to the HPIRegions spreadsheet (note: not the HPIAdmin spreadsheet) in the SourceDataf workbook. 
2. Create a viz (bar chart) which shows the Year(Date) (going across) by SUM(Sales Volume) (going up). Drag "Region Name" to the Color mark. Rename this as "Viz 1".
3. Create a second viz which has:
    "Region Name" on the Rows, and
    Sum(Sales Volume) in the Text marks.
    Rename this as "Viz 2".
4. Create a third viz which has:
    Year(Date) on the Rows shelf
    Sum(Sales Volume) in the Text marks.
    Rename this as "Viz 3".
5. Create a dashboard which has:
    "Viz 2" in the top-left hand corner.
    "Viz 3" in the top-right hand corner.
    "Viz 1" in the bottom half.
    Before you do it, have a think about what is the best order to add the Vizzes into the dashboard.
6. Click on the "Use as Filter" on Viz 2, and click on "East Midlands" in Viz 2. See what happens.
7. Now change this filter so that it only works on a menu.
8. Add a similar filter on Viz 3.
9. Set up this dashboard on a Tablet and a Phone.
10. Create a story, using this dashboard three times. In each story point, select a different region in "Viz 2".

# Assigniment :-5
1. Connect to the States spreadsheet in the SourceDataf workbook. This contains a list of the population of the 50 US states.
2. Create a new viz. Add the Latitude, Longitude and Population. Look at the results.
3. Show the results by State.
4. How many states are missing? Correct the problem.
5. Zoom into New York so that it roughly fits the screen.

# Assigniment :-6
1. Create a new viz, with State on the Rows shelf and Sum(Population) as a Text mark.
2. Create a new group, grouping together all states which start with the letter M.
3. Order the viz by Sum of Population descending.
4. Create a new set of "State (group)", containing the top 5 state groups based on Population.
5. Go back to the map viz (or create a fresh map), and change the color scheme to the newly created set.
6. Move this set to the rows shelf.

# Assigniment :-7
1. Connect to the HPIRegions spreadsheet (note: not the HPIAdmin spreadsheet) in the SourceDataf workbook. 
2. What is the range of the field SalesVolume? Create a histogram to find out.
3. Change the "SalesVolume (bin)" so that there is a bar every 500.
4. Create a heat map, with 
    "Year(Date)" on the Rows shelf
    "Quarter(Date)" on the Columns shelf
    "SUM(SalesVolume)" as the color and label marks.
5. Change it to a tree map, and remove the "Quarter(Date)" field.
6. Create a new viz, with
    "Year(Date)" on the Columns shelf, and
    "SUM(SalesVolume)" and "Avg(AveragePrice)" on the Rows shelf.
Put them on the same graph, using the same synchronized scale.
7. Create a new scatter graph viz, with
    Avg(AveragePrice) on the Columns shelf,
    Sum(SalesVolume) on the Rows shelf, and
    Month(Date) in the Detail.
8. Now add Year(Date) to the Pages shelf. Create a motion graph, showing the History for all marks, and using Both Trails and Marks.
9. Create a dashboard, using the vizzes that you have just created.
