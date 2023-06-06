# home_sales_challenge

## Overview
This challenge used SparkSQL to analyze home sales data. This data utilized temporory tables, data partitioning, and the ability to cache and uncache tables. 


## Instructions

* Read the `home_sales_revised.csv` data in the starter code into a Spark DataFrame.

* Create a temporary table called `home_sales`.

### Answer the following questions using SparkSQL:

   1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

   2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

   3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
  
   4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
   

## Instructions (cont.)

* Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

* Partition by the "date_built" field on the parquet home sales data and create a temporary table for this data. Run the same query that was used for the above "cached data".

* Uncache the `home_sales` temporary table. Verify that the `home_sales` temporary table is uncached.

## Resources
I used previous examples from Module 22 to guide me through this challenge. These examples included creating temporary views and partitioning data.
