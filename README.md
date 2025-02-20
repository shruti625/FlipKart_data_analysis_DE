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

## Column Descriptions  
- **id**: Product unique number  
- **title**: Description of the product  
- **Rating**: Rating of the product  
- **maincatg**: Indicates if the product is made for men or women  
- **platform**: Product platform  
- **actprice1**: Actual price of the product  
- **norating1**: Number of customers who didn't rate the product  
- **noreviews1**: Number of customers who didn't review the product  
- **star_5f**: Total number of customers who gave a 5-star rating  
- **star_4f**: Total number of customers who gave a 4-star rating  


Technologies: Pyspark,SQL,csv(data handling)
