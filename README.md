# Home_Sales
## Overview:
In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

# Initial data:
![Initial](https://github.com/victoriant/Home_Sales/assets/119895467/407443e9-e6a6-41df-81ef-9a8ae800bc0f)

# Cached data:
![Cached](https://github.com/victoriant/Home_Sales/assets/119895467/a8e1abde-4ccc-4206-ac30-643cd3508a3d)

# Partitioned data:
![Partitioned](https://github.com/victoriant/Home_Sales/assets/119895467/78d368c2-31e5-4c39-abd2-13d1a56d4e4b)

## Summary:
The inital time that it took to run the query was 0.21 seconds. After changing it to cached data, the new run time was 0.16 seconds, which was .05 seconds faster. Lastly, we partitioned the data which took 0.19 seconds. This appeared to be the second best method to run data with cached being first and the initial run being the slowest. 
