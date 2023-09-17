# Home-Sales-Challenge
## Module 22: Big Data

In this challenge, we used our knowledge of SparkSQL to determine key metrics about home sales data. We also used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table had been uncached.

# Instructions
1. Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.
2. Import the necessary PySpark SQL functions for this assignment.
3. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.
4. Create a temporary table called home_sales.
5. Answer the following questions using SparkSQL:
  - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    
    <img width="831" alt="image" src="https://github.com/RP8844/Home_Sales-Challenge/assets/118138351/af832ca9-306e-44e0-922b-ceff435c5ef7">
    
  - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    
    <img width="853" alt="image" src="https://github.com/RP8844/Home_Sales-Challenge/assets/118138351/2b43ec43-8fa6-4469-8afb-fc5c153e3dc0">

  - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    
    <img width="926" alt="image" src="https://github.com/RP8844/Home_Sales-Challenge/assets/118138351/b20838b8-6952-4600-9852-80f622756934">

  - What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
    <img width="797" alt="image" src="https://github.com/RP8844/Home_Sales-Challenge/assets/118138351/4b7534fa-e3f9-42bb-af8b-ab5b25b0e32b">

    
6. Cache your temporary table home_sales.
7. Check if your temporary table is cached.
8. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
9. Partition by the "date_built" field on the formatted parquet home sales data.
10. Create a temporary table for the parquet data.
11. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
12. Uncache the home_sales temporary table.
13. Verify that the home_sales temporary table is uncached using PySpark.
14. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

# Resources
1. Modules 22: In Class Activities
2. Class Instructor: Arooj A Qureshi
3. TA Instructor: Abdelrahman "Abdo" Elewah
