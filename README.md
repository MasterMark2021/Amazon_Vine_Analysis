# Amazon_Vine_Analysis

This assignment was done and submitted on Google Colaboratory user:markokoli85@gmail.com

The link to the challenge assignment workbook can be accessed through the below link:

https://github.com/MasterMark2021/Amazon_Vine_Analysis

**Objectives**
In this assignment, we were tasked with running the ETL process on the cloud, using Spark. We utilized PySpark to run statistical analysis on a database of US-based Amazon.com reviews.

We first created our tables in the RDS database. We then extracted the data from the S3 bucket and loaded it into a dataframe. Once the data was in a DataFrame, we transformed it to fit the desired schema (from schema.sql). To complete the ETL process, we loaded the DataFrames that correspond to tables into an RDS instance.

Once the ETL process was completed, we performed statistical analyses in PySpark to determine if the Vine reviews were unbiased.

My work (including analysis) is in the notebook. Through our analysis, we were able to determine that the Vine reviews were trustworthy.
