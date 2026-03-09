# HR-Analytics-Databricks-Transformations
This project demonstrates various data transformations performed on HR Analytics data.  datasource (kaggle): [Link](https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists)

### Step 1: Loading & Understanding Data

i) Reading CSV files in Databricks

ii) Checking schema and data types

### Step 2: Data Cleaning & Transformation
i) Renaming columns for better clarity

ii) Converting categorical values into numerical format

iii) Handling NULL values using fillna(), dropna()

### Step 3: Working with DataFrames

i) Using filter(), sort() operations

ii) Performing column operations like withColumn(), alias(), and cast()

### Step 4: Advanced PySpark Functions
i) Using explode(), collect_list(), pivot(), when(), otherwise()

ii) String functions: initcap(), upper(), lower()

iii) Date functions: current_date(), datediff(), date_add(), year(), month()

### Step 5: Joins & Data Merging
i) Inner, Left, Right & Outer Joins

ii) Union & UnionByName for combining datasets

### Step 6: Window Functions & Ranking

i) Using rank(), dense_rank(), and cumulative sum()

ii) Partitioning and ordering data efficiently

### Step 7: User Defined Functions (UDFs)
i) Writing custom functions in PySpark

ii) Applying UDFs to transform and clean data

### Step 8: Writing & Saving Data
i) Writing datasets in CSV, JSON, ORC, and Delta formats

ii) Overwriting, appending, and handling errors while saving

