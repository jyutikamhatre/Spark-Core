# Spark-Core

Proof of concept - Spark Core

Project Description : Retail market analysis

Dataset Resource : Cloudera Quickstart VM 5.10 CDH – retail_db database

Special operations :

      a. Count by order status
      b. Compute daily revenue
      c. Compute daily revenue per day per department
      d. Find the most expensive product
      e. Top 5 expensive products in each category

Goal : To do various operations on retail market yearly data and do the analysis.

The project done on Cloudera Quickstart VM 5.10 CDH.

Note : I imported the MYSQL db - all tables to HDFS with 4 mappers as default in the sqoop so each table file devided into 4 parts.  I have uploaded only one as a sample for each table here.

Output files are also divided into 4 parts due to default partitions set on the HDFS setup.  I have uploaded only one sample file for each output.
