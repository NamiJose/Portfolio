Sales Story: Revealing Insights is a sample sales dashboard created using data obtained from kaggle. 
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
