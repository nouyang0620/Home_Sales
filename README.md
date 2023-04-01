# Home_Sales

## Introduction

In this challenge, knowledge of SparkSQL is used to determine key metrics about home sales data. Temporary views are created using Spark, the data is partitioned, cached and uncached, then verified that the table has been uncached. 

## Steps
1. Import necessary PySpark SQL functions
2. Read the home_sales_revised.csv data 
3. Create temporary table home_sales
4. Answer questions:
    What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
5. Cache temporary table home_sales
6. Check to see if temporary table is cached
7. Using the cached data, run query filtering out view ratings with an average home price of greater than or equal to $350,000. Determine the runtime and compare to the uncached runtime.
8. Partition by "date_built" on formatted parquet home sales data.
9. Create temporary table for parquet dat.
10. Run query filtering out view ratings with an average home price of greater than or equal to $350,000. Detine the runtime and compare to the uncached runtime.
11. Uncache temporary home_sales table.
12. Verify the temporary table has been uncached using PySpark.
