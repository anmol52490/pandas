# Pandas Learning Repository

This repository contains my learning journey with the pandas library, documented through Jupyter Notebooks. Each section covers different essential pandas functionalities with practical examples and explanations.

## Topics Covered

### 1. **DataFrame Basics**
   - Introduction to pandas DataFrames.
   - Creating DataFrames from various data sources (e.g., lists, dictionaries).
   - Indexing and slicing DataFrames.
   - Basic DataFrame operations (adding, modifying, and deleting columns/rows).

### 2. **Reading and Writing Data**
   - Reading and writing data to/from:
     - CSV files (`pd.read_csv()`, `df.to_csv()`).
     - Excel files (`pd.read_excel()`, `df.to_excel()`).
   - Options for handling headers, indices, and data types during reading/writing.

### 3. **Handling Missing Data**
   - **Filling missing data**:
     - Using `fillna()` to replace `NaN` values.
   - **Dropping missing data**:
     - Using `dropna()` to remove rows or columns containing `NaN` values.
   - **Interpolating missing data**:
     - Using `interpolate()` to estimate missing values.
   - **Replacing values**:
     - Using `replace()` to substitute specific values across the DataFrame.

### 4. **Grouping and Aggregation**
   - Using the `groupby()` method to group data by one or more columns.
   - Aggregating grouped data using functions like `mean()`, `sum()`, `count()`, etc.
   - Applying custom aggregation functions.

### 5. **Merging and Concatenating Data**
   - **Concatenating DataFrames**:
     - Using `concat()` to combine DataFrames along rows or columns.
   - **Merging DataFrames**:
     - Using `merge()` to combine DataFrames based on key columns (similar to SQL joins).

## Requirements

To run the notebooks, you will need the following:

- **Python 3.x**
- **Jupyter Notebook**
- **pandas**
- **NumPy** (optional, but useful for some operations)
  
You can install the required libraries by running:

```bash
pip install -r requirements.txt
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/anmol52490/pandas.git
   ```
2. Navigate to the directory:
   ```bash
   cd pandas
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the notebooks to explore the pandas concepts.



