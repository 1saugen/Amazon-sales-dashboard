# Amazon-sales-dashboard

This contains all the steps I took to create the dashboard.
Data cleaning 
1.	Handling missing values
•	Go to conditional formatting. 
•	Choose new rule. 
•	Select Format only cells that contains. 
•	Chande the cell value to blank. 
•	Use any background color to highlight cells
2.	Handle duplicates
•	Go to conditional formatting
•	Select highlights the cells rules -> duplicate values
•	Check and delete
3.	Standardize Text
•	Select your data and go to Data tab -> From Table/Range
•	In power Query window, Right-Click the header of the column you want to clean.
•	Select Transform-> Format->Trim
•	Close ->keep
4.	fix data types (Dates)
•	Go to data -> text to columns->Next->Next-> change the date format you want->finish
5.	Identify Outliers
•	I used box plot to identify the outlier
•	Also go to conditional formatting -> Top/Bottom rules -> Top 10 % ->adjust the %
•	Also go to conditional formatting -> Top/Bottom rules -> Bottom 10 % ->adjust the % 

