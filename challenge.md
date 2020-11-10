# Azure Synapse Analytics Challenge

Challenge time: 90 minutes

## New York Taxis Data Challenge

Overall, the goal of this challenge is to use SQL On Demand to explore data and uses Spark Pool to prepare the dataset for a machine learning task to predict the taxi trip cost.

## Lab context

The Dataset used in this challenge is based on 2 CSV files coming from https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page. These 2 files are stored in challenge-data container in the Data Lake

## Exercise 1 - Explore the data lake with Azure Synapse SQL On-demand 

In this exercise, you will explore data using the SQL On Demand engine.

Find out:
* Do the CSV files have the same schema?
* How data is distributed between Yellow and Green company
* The average, min and max cost of the trip per company
* Use Chart in SQL On demand to find the outliers for total_amount, trip_distance

## Exercise 2 - Build Data Prepaaration

After exploring the data lets clean it.
* Read the 2 CSV files
* From lpep_pickup_datetime column create for new columns "month_num", "day_of_month","day_of_week", "hour_of_day"
* Keep only the following columns:
passenger_count,trip_distance,tip_amount,fare_amount,extra,tip_amount,tolls_amount,improvement_surcharge,total_amount,payment_type,tripe_type

Once data is properly understood and interpreted, moving it to the various destinations where processing steps occur is the next big task. Any modern data platform must provide a seamless experience for all the typical data wrangling actions like extractions, parsing, joining, standardizing, augmenting, cleansing, consolidating, and filtering.

Azure Synapse Analytics provides two significant categories of features - data flows and data orchestrations (implemented as pipelines). They cover the whole range of needs, from design and development to triggering, execution, and monitoring.

## Exercise 3 - Power BI integration

In this exercise, you will build a Power BI report in Azure Synapse Analytics.

The visual approach in data exploration, analysis, and interpretation is one of the essential tools for both technical users (data engineers, data scientists) and business users. Having a highly flexible and performant data presentation layer is a must for any modern data platform.

Azure Synapse Analytics integrates natively with Power BI, a proven and highly successful data presentation and exploration platform. The Power BI experience is available inside Synapse Studio.

## Exercise 4 - High Performance Analysis with Azure Synapse SQL Pools

In this exercise, you will try to understand customer details using a query and chart visualizations. You will also explore the performance of various queries.

SQL data warehouses have been for a long time the centers of gravity in data platforms. Modern data warehouses are capable of providing high performance, distributed, and governed workloads, regardless of the data volumes at hand.

The Azure Synapse SQL Pools in Azure Synapse Analytics is the new incarnation of the former Azure SQL Data Warehouse. It provides all the modern SQL data warehousing features while benefiting from the advanced integration with all the other Synapse services.

## Exercise 5 - Data Science with Azure Synapse Spark

In this exercise, you will play the role of a data scientist. You will create a model to predict customer purchase volumes based on the WWI sales dataset, using Azure Synapse Spark.

Modern era data environments must handle in a performant and seamless way any data an organization might have. In almost all cases, this means a combination of relational SQL-style capabilities and big data ones. In the world of massively distributed big data processing platforms, Spark is almost an implicit choice.

Azure Synapse Analytics provides Apache Spark to support data science workloads. They enable data scientists to perform all their specific tasks while benefiting from the integration with the other Synapse services.
