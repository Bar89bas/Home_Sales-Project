# Home_Sales-Project

## Overview:
Aggregrating the Home Sales Data to determine the key metrics. Creating temporary views, partition the data, cache, uncache a temporary table and verifying the table has been uncached with SparkSQL. 

## Task Performed:
- [ ] Creating Spark DataFrame from the dataset.
- [ ] Creating the temporary table of the original DataFrame. 
- [ ] Query to return  returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year. 
- [ ] Query to return returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms. 
- [ ] Query to return the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year built rounded to two decimal places.
- [ ] Query to return the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two decimal places. 
- [ ] A cache of the temporary "home_sales" table is created and validated.
- [ ] The query from step 6 is run on the cached temporary table, and the run time is computed.
- [ ] A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read.
- [ ] A temporary table of the parquet data is created.
- [ ] The query from step 6 is run on the parquet temporary table, and the run time is computed.
- [ ] The "home_sales" temporary table is uncached and verified. 
