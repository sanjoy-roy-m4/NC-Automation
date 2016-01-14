Install Firefox Selenium IDE Add-ons (http://www.seleniumhq.org/projects/ide/)
Open the Selenium IDE
Go to Options -> options... -> Browse two resource (.js) files at 'Selenium Core extensions (user-extensions.js)' fields from 'resource' folder - a. file-saver.js b. user-extensions.js
Go to Options -> options... -> Enter value as-'120000' at 'Default timeout value of recorded command in milliseconds' field
Restart the Selenium IDE
Click Open and browse the 'smoke_test' folder -> 'test_suite.html'
All the test cases will be loaded on Selenium IDE
Download the data file from location - '/files/DXD_Data_file_CSV.csv' and store the file in local PC(e.g. "D:\data\NC_Data_file_CSV.csv")
At the 'Read_Data_File' test case set the Data file location path as - "file:D:\data\NC_Data_file_CSV.csv"
