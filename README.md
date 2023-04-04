# Bike-Sales-Dashboard-in-Excel
## This is a Bike Sales Dashboard Full Project using Microsoft Excel 
This dashboard is explaining to us about persons who do or do not purchase bikes from the raw data we populated (I used the "Bike Sales Datasets" from Alex Freberg), this will include the slicer for the gender, age brackets, marital status and occupation to filter results.

**For the Data Cleaning:**
1) Opened a new working sheet to work with and avoid tampering with the original dataset.
2) Had my filter on to see my data to have an idea what it looks like.
3) Removed all duplicates.
4) Gender: I used the find replace function to replace the letters M and F to Male and Female for easier read. Ctrl+H for shortcut.
5) Age brackets : The raw data had different ages so I had to put them into some age brackets. Using the IF function, =IF(L2<31,"Adolescent","Invalid"), I was able to create ages 0-30 under Adolescent. For ages 31-54 as 'Middle age' and 55-above as 'Old' The IF function was nested to the first formula, that is =IF(L2>55,"Old", IF(L2>=31,"Middle Age",IF(L2<31, "Adolescent", "Invalid")
6) Inserted Pivot tables to summarise my data. I also did sum functions like Count and Average. This helped me compare and see the patterns in a very easy manner.
7) Added some charts to suit my data- both bar charts and Line charts were used
8) Dashboard: Hid the grid lines to get a clearer view, formatted my fonts, colours and aligned the charts to my desired style
9) Slicer: This acts as a filter. I connected them all to my pivot tables to enable them work effectively. I added colours to my slicer to help us know what data was being accessed easily.
