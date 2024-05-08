This folder contains the following files:
1. Classification Tool for Chemical Analysis: This is the report created using R after exploratory data analysis and evaluating multiple models for classifying chemicals and predicting the category to which it belongs based on the important features.
2. Predicting Diabetes from Silent Symptoms: This is a report created after data processing, exploratory analysis, model selection and  prediction using python to detect diabetes based on early symptoms without medical intervention.
3. Sales Insights..png: The power bi dashboard screenshot
4.  Sales Dashboard: A sample power bi report (pbix file) created using sales data.

Sales Dashboard is a sample power bi dashboard created using data obtained from kaggle. 
Main Steps Followed:
1. Analysed the raw data and identified key metrics
     1. There are two input files, one for 2023 data and another for 2024 data with same structure.
     2. The granularity of the data is at product category level for each day for each branch. Product details are not available.
     3. The gross income and quantity for each product category for a particular day for each branch is available.
     4. Payment methods, customer type and gender are available. 
3. Loaded the 2024 and 2023 files to Power BI
4. Appended both files.
5. Checked the data quality using data profiling tools in Power BI.
6.Created dimension tables for Branch and Date using Power Query.
7.The details of sales for a particular day for each branch and product category is stored in fact table.
8. Connected fact and dimension tables.
9. Created charts and filters. 
10. Adjusted chart properties.
