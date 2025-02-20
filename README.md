# FlipKart_data_analysis_DE
Project Overview
This project focuses on performing basic data analysis on a Flipkart dataset using PySpark. The main goal is to preprocess and analyze the data efficiently using distributed computing. The analysis includes handling missing values, performing transformations, and generating meaningful insights.

Key Features & Steps
Reading Data: Load the Flipkart dataset from a CSV file into a PySpark DataFrame.
Handling Missing Data: Identify and manage null values within the dataset.
Dropping Null Values: Remove rows that contain missing data based on predefined conditions.
Filling Null Values: Replace missing values with meaningful defaults to maintain data consistency.
Data Transformations & Aggregations: Perform necessary transformations and aggregations to extract useful insights.
Data Analysis: Conduct exploratory data analysis (EDA) to derive trends, patterns, and business insights.

Columns description:
id : product unique number
title: description of product
Rating: Rating of product
maincatg: made for men/women
platform: product platform
actprice1: actual price
norating1 :number of customer didn't rate
noreviews1: number of customer didn't review the product
star_5f: total number of customer who given 5 star
star_4f:total number of customer who given 4 star

Technologies: Pyspark,SQL,csv(data handling)
