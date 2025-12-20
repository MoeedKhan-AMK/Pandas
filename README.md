# PANDAS CONCEPTS PROGRESS

**1. Pandas Fundamentals**
- What Pandas is and why it is used
- Difference between Pandas and NumPy
- Series vs DataFrame
- Use cases in data analysis and real-world datasets

**2. Data Loading & Saving**
- read_csv(), to_csv()
- Reading & writing Excel files
- Understanding file paths
- Common parameters:
  - skiprows
  - nrows
  - header
  - column naming

**3. Data Inspection & Understanding**
- head(), tail()
- shape
- columns
- info()
- describe()
- Basic statistics: min(), max(), mean()

**4. Data Selection & Indexing**
- Column selection
- .loc[] (label-based indexing)
- .iloc[] (position-based indexing)
- Selecting multiple columns
- Row filtering using conditions

**5. Data Manipulation**
- Creating new columns
- Column operations
- apply() with functions
- Renaming columns
- Dropping rows & columns

**6. Boolean Filtering**
- Single condition filtering
- Multiple conditions (&, |)
- Masking data
- Practical filtering examples

**7. Grouping & Aggregation**
- groupby()
- agg() with multiple functions
- Custom aggregations
- Binning data using pd.cut()
- Real-world grouping scenarios

**8. Handling Missing & Dirty Data**
- Identifying missing values
- fillna()
- dropna()
- thresh parameter
- replace() for dirty values (e.g., -99999, strings)
- interpolate() for numeric data

**9. Data Cleaning & Quality Awareness**
- Handling inconsistent data
- Dealing with incorrect or placeholder values
- Understanding real-world data issues
- Data reliability examples (e.g., financial data like Bloomberg)

**10. Data Analysis & Summaries**
- Sorting values
- Value counts
- Aggregations for insights
- Simple analytical use cases

**11. Combining Data**
- pd.concat()
- axis usage
- ignore_index
- keys (tracking data source)
- Basic merge and join concepts

**12. Practical Data Analysis Practice**
- Real-world datasets
- Step-by-step data cleaning workflow
- Exploratory data analysis (EDA)
- Preparing data for visualization & ML
