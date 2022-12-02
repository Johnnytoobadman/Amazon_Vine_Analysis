# AMAZON VINE ANALYSIS

## OVERVIEW

### This project involves analyzing Amazon written reviews by members of the paid Amazon Vine program.  This program is sponsored by "SellBy" and it's members who receieve Amazon products and write reviews for a small stipend.

### This project involves just one of many datasets, specifically "Outdoor Accessories".  The process is to use PySpark to perform an Extract, Transform, Load (ETL) to extract the dataset, transform the data, connect to an Amazon Worldwide Services (AWS) server instance and load the transformed data into pgAdmin.  Subsequently PySpark is used to determine if there is any bias towards favorable reviews from the Vine members.

### The deliverables are as follows:

### 1. Perform an ETL process on Amazon product reviews for outdoor accessories.

### 2. Determine the bias of vine reviews.

### Provide a written report on the above analysis'.


## RESOURCES

### Starter Code: Amazon_Reviews_ETL_Starter_codes.ipynb, 

challenge_schema.sql

### Spark version 3.3.1

### hadoop version 3

### postgres version 42.5.0

### pgAdmin version 6.12

### Colab (Google) version 3.5.5

### Amazon RDS and S3



## RESULTS

### pgAdmin Table Creation

### DataFrame show()

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df1.png)

### Customer_id Count

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df2.png)

### Product_id and title

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df3.png)

### Review_id and information

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df4.png)

### Review ID with Rating

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df5.png)

### pgAdmin customer-id output (table)

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df6.png)

### pgAdmin product_id output (table)

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df7.png)

### pgAdmin review_id output (table)

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df8.png)

### pgAdmin review_rating output (table)

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df9.png)

### pgAdmin Code used to create tables

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df10.png)

### DataFrame

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df11.png)

### Top Reviews

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df13.png)

### Top Rated Reviews

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df14.png)

### Highest Rated Reviews

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df15.png)

### Percentage of 5 Star reviews for unpaid vine users.

![__](https://github.com/Johnnytoobadman/Amazon_Vine_Analysis/blob/main/Images/df16.png)


## SUMMARY

