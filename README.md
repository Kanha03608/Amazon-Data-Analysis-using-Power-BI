# Amazon-Data-Analysis-using-Power-BI
The data given was very unorganized. We followed the following steps to clean and organize the data for visualization : 
Removed unnecessary columns: Removed columns such as user ID, username, review ID, review title, review content, and image link as they were not needed for this project.
Divided category columns: Split the category columns into two separate columns, namely Category and Sub-Category, using the extract function for better organization and clarity.
Checked for null values: Examined each column for any missing values. Identified 2 null values in the rating count columns and obtained the missing data from Amazon using the provided product links.
Created a new column for updated ratings: Generated a new column to update ratings and replaced any instances of "13" with zero for consistency.
Rectified errors/null values in ratings: Addressed any errors or null values in the ratings column by cross-referencing with Amazon data through the product links.
Added new measures: Introduced new metrics such as average discounts, total sales with discounts, total sales without discounts, and the number of products for both categories and subcategories.
Designed the dashboard: Developed a visualization dashboard showcasing all the metrics and included buttons for selecting categories and subcategories for easier navigation.
Implemented interactive functionality: Enabled the use of Shift + Click to switch between category and subcategory visuals for a more dynamic user experience. The blue and yellow colour blocks are “Buttons” to switch between two pages.
