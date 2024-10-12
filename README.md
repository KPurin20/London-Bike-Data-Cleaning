# London-Bike-Data-Cleaning
Cleaning and mutation of columns for future reporting in tableau

Read in csv file 
Took initial look at data to better understand intiial dataframe using .info()

Gathered counts of unique values in season and weather columns as the numeric values of these needed to be changed to strings for easier interpretation

Renamed all columns and used dictionaries to change numeric values to descriptive strings
ie: 0 = spring, 1 = summer, 2 = fall etc.

Mapped dictionaries to dataframe and checked cleaned dataframe for proper structure and implementation of mapping

Exported to .xlsx file for import to Tableau
