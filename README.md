# Pandas – Data Analysis

This repository contains my Pandas learning, practice, and data analysis work using Python.

## Pandas Topics Covered

### 1. Pandas Fundamentals

* Introduction to Pandas
* Installing Pandas
* Importing Pandas
* Pandas Series
* Pandas DataFrame
* Creating Series
* Creating DataFrames
* DataFrame from Dictionary
* DataFrame from Lists
* DataFrame attributes
* `shape`
* `columns`
* `index`
* `dtypes`
* `values`

### 2. Data Inspection

* `head()`
* `tail()`
* `info()`
* `describe()`
* `shape`
* `columns`
* `index`
* `dtypes`
* `max()`
* `min()`
* `mean()`
* `median()`
* `std()`
* `count()`
* `sum()`

### 3. Reading and Writing Data

* Reading CSV files – `read_csv()`
* Writing CSV files – `to_csv()`
* Reading Excel files – `read_excel()`
* Writing Excel files – `to_excel()`
* Reading data from different sources
* `na_values`
* Working with file paths

### 4. Selecting Data

* Selecting columns
* Selecting multiple columns
* Selecting rows
* Selecting specific cells
* `loc[]`
* `iloc[]`
* Label-based indexing
* Integer-based indexing
* Boolean indexing
* Conditional selection

### 5. Filtering Data

* Single-condition filtering
* Multiple-condition filtering
* `&`
* `|`
* `~`
* `isin()`
* Filtering numerical data
* Filtering string data
* Filtering based on multiple columns

### 6. Missing Data

* Identifying missing values
* `isna()`
* `isnull()`
* `notna()`
* `notnull()`
* Counting missing values
* `dropna()`
* `fillna()`
* `ffill()`
* `bfill()`
* `interpolate()`
* Filling with mean
* Filling with median
* Filling with mode
* Forward fill
* Backward fill

### 7. Data Cleaning

* Handling invalid values
* Replacing values
* `replace()`
* Replacing multiple values
* Removing unwanted rows
* Removing unwanted columns
* Renaming columns
* `rename()`
* Changing data types
* `astype()`
* Handling duplicate records
* `duplicated()`
* `drop_duplicates()`

### 8. Sorting and Indexing

* Sorting rows
* `sort_values()`
* Sorting by multiple columns
* Sorting index
* `sort_index()`
* Setting index
* `set_index()`
* Resetting index
* `reset_index()`
* Index manipulation

### 9. GroupBy and Aggregation

* Introduction to GroupBy
* `groupby()`
* Grouping by one column
* Grouping by multiple columns
* Aggregation
* `sum()`
* `mean()`
* `median()`
* `min()`
* `max()`
* `count()`
* `std()`
* `agg()`
* Multiple aggregations
* Grouped filtering
* Grouped analysis

### 10. Combining DataFrames

* Concatenation
* `pd.concat()`
* Row-wise concatenation
* Column-wise concatenation
* Merge
* `pd.merge()`
* Inner Join
* Left Join
* Right Join
* Outer Join
* Merging on common columns
* Merging using indexes

### 11. Working with SQL Databases

* SQLite with Pandas
* Database connections
* SQLAlchemy
* `to_sql()`
* `read_sql_query()`
* Writing DataFrames to SQL tables
* Reading SQL data into Pandas
* Querying SQL data using Pandas

### 12. DateTime

* Working with dates
* Working with timestamps
* `pd.to_datetime()`
* Converting strings to datetime
* `parse_dates`
* `index_col`
* DateTimeIndex
* Date-based indexing
* Extracting year
* Extracting month
* Extracting day
* Date filtering

### 13. Time Series Analysis

* Time Series fundamentals
* DateTimeIndex
* Partial string indexing
* Selecting data by year
* Selecting data by month
* Chronological sorting
* `sort_index()`
* Resampling
* `resample()`
* Daily resampling
* Monthly resampling
* Yearly resampling
* Time-based aggregation

### 14. String Operations

* Working with string columns
* `.str` accessor
* `str.lower()`
* `str.upper()`
* `str.title()`
* `str.strip()`
* `str.replace()`
* `str.contains()`
* `str.startswith()`
* `str.endswith()`
* `str.split()`
* Extracting text patterns

### 15. Apply and Lambda

* `apply()`
* Applying functions to columns
* Applying functions to rows
* Lambda functions with Pandas
* `map()`
* `applymap()` / element-wise operations

### 16. Data Transformation

* Creating calculated columns
* Modifying columns
* Transforming values
* `map()`
* `apply()`
* Lambda functions
* Conditional transformations
* Vectorized operations

### 17. Categorical Data

* Categorical variables
* `astype('category')`
* Categorical operations
* Category management
* Memory-efficient categorical columns

### 18. Crosstab and Pivot Tables

* `pd.crosstab()`
* Frequency tables
* `margins=True`
* Normalized crosstab
* `normalize='index'`
* `pivot_table()`
* Aggregation using pivot tables

### 19. Reshaping Data

* Wide format
* Long format
* `melt()`
* `pivot()`
* `pivot_table()`
* Stack and unstack
* Reshaping DataFrames

### 20. Combining and Comparing Data

* `concat()`
* `merge()`
* `join()`
* Comparing DataFrames
* Finding differences
* Working with indexes during joins

### 21. Advanced Data Selection

* Advanced Boolean filtering
* `query()`
* `where()`
* `mask()`
* Conditional selection
* Complex filtering conditions

### 22. Advanced Aggregation

* Multiple aggregations
* Named aggregation
* GroupBy transformations
* `transform()`
* Group-level calculations
* Aggregation with multiple columns

### 23. Window Functions

* Rolling calculations
* `rolling()`
* Expanding calculations
* `expanding()`
* Cumulative calculations
* `cumsum()`
* `cumprod()`
* `cummin()`
* `cummax()`

### 24. Data Types

* Understanding Pandas data types
* Numeric types
* String types
* Boolean types
* Datetime types
* Categorical types
* Type conversion
* `astype()`
* Nullable data types

### 25. Duplicate and Unique Data

* Finding duplicates
* `duplicated()`
* Removing duplicates
* `drop_duplicates()`
* Unique values
* `unique()`
* Number of unique values
* `nunique()`

### 26. Working with Columns and Rows

* Adding columns
* Removing columns
* `drop()`
* Inserting columns
* Reordering columns
* Adding rows
* Removing rows
* Updating values

### 27. Input/Output and External Data

* CSV
* Excel
* SQL databases
* JSON
* Reading JSON
* Writing JSON
* HTML tables
* Parquet
* Pickle
* Other Pandas-supported data sources

### 28. Performance and Best Practices

* Vectorization
* Avoiding unnecessary loops
* Efficient filtering
* Efficient data types
* Memory usage
* `copy()`
* Working with large datasets
* Chaining operations
* Pandas best practices

### 29. Data Analysis Practice

* Data cleaning
* Data preprocessing
* Exploratory data analysis
* Statistical analysis
* Grouped analysis
* Time-series analysis
* Real-world datasets
* Problem solving with Pandas

### 30. Pandas Interview & Problem Solving

* Pandas coding questions
* Data manipulation problems
* Data cleaning problems
* GroupBy problems
* Merge and Join problems
* Time-series problems
* LeetCode Pandas problems
* Data Analytics interview questions

## Tools & Technologies

* Python
* Pandas
* Jupyter Notebook
* VS Code
* SQLite
* SQLAlchemy

## Learning Source

Codebasics – Pandas for Data Analysis
