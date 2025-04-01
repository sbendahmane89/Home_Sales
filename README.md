## **Module Challenge #22: Home_Sales**

## Description: 

This module challenge involves using SparkSQL to analyze and optimize home sales data, focusing on caching, partitioning, and efficient query execution to ensure better performance and accurate results. This challenge involves the following steps:

**1. Setup:**

- Rename the Home_Sales_starter_code.ipynb file to Home_Sales.ipynb.

- Import the necessary PySpark SQL functions.

- Load the home_sales_revised.csv file from the AWS S3 bucket into a PySpark DataFrame, and create a temporary table called home_sales.

**2. SparkSQL Queries:**

- Compute the average price of four-bedroom homes sold each year.

- Calculate the average price of homes with three bedrooms and three bathrooms by the year they were built.

- Determine the average price of homes with three bedrooms, three bathrooms, two floors, and at least 2,000 square feet by year built.

- Calculate the average home price per view rating for homes valued at $350,000 or more, and record the runtime for this query.

**3. Caching and Performance Optimization:**

- Cache the home_sales temporary table and verify that the caching is successful.

- Execute the query using the cached data and compare the runtime with the uncached query.

**4. Partitioning and Parquet:**

- Partition the data by the date_built field and save it as a Parquet file.

- Create a temporary table from the Parquet data.

- Re-run the query for average price by view rating, comparing the runtime between the cached and uncached versions.

**5. Uncaching:**

- Uncache the home_sales table and confirm that the cache has been cleared.

**6. Final Steps:**

- Download the Home_Sales.ipynb file and upload it to your GitHub repository.




