# Pyspark-creditcard-fraud-detection
Exploratory fraud detection analysis on credit card transactions using PySpark and Databricks Spark Connect.
Credit Card Fraud Detection with PySpark (Databricks)

This project explores credit card fraud detection using PySpark on Databricks with Spark Connect. The goal was to perform basic data analysis on an anonymized transaction dataset and identify fraudulent patterns.

**Dataset**

The dataset contains anonymized features of credit card transactions, with a binary classification column Class indicating fraud (1) or not fraud (0). The data was loaded into Databricks and accessed as a managed table.

**Tools and Technologies**

PySpark via Databricks Spark Connect (Community Edition)

Databricks notebook interface

Python and Pandas (for initial loading)

Spark SQL and PySpark DataFrame operations

**Work Completed**

Loaded Excel file into Databricks as a table

Explored schema, column types, and value distribution

Filtered and displayed fraud vs non-fraud transactions

Conducted basic summary statistics and class balance check

**Limitations**

Due to Spark Connect’s restricted environment, full machine learning functionality was not used. The project focused on data inspection and preparation stages.
