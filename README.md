# Master List from Google Sheets
 Create an auto-updating master list by pulling data from multiple tabs on a Google sheets workbook written in Javascript. 

 The variable sheetNamesToImport represents the names of the tabs for the source data. The array that is defined for this code contain columns A through D and rows 4 through 19. This should be edited to make the desired array. Note that all the data for each tab needs to be formatted into the same array for this code to work. 

 This script is best used for data in tabs that is formatted the same across the tabs of the workbook. 

 The code will create a new tab for the master list if it doesn't already exist. 

 This is not meant to overwrite data that is already in the destination sheet, so it should be empty if you want to populate a new list. Otherwise, it will start at the next available cell. 

 This code is meant to be used as an App Script and should be manually initiated. There are no triggers coded into the 

