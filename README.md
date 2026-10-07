# Week 2 – Python for Data Analysis

## Project Overview

This project demonstrates basic data analysis techniques using Python and Pandas. The analysis is performed on a sales dataset containing 200 records.

## Dataset

The dataset contains sales information such as:

- Order ID
- Customer Name
- Order Date
- Category
- Sub Category
- Product Name
- Quantity
- Unit Price
- Total Price
- Region

## Tasks Performed

### 1. Load CSV and Display Basic Information
- Loaded the sales dataset using Pandas.
- Displayed the first few records.
- Checked dataset shape, columns, data types, and statistical summary.

### 2. Handle Missing Values and Duplicates
- Identified missing values.
- Filled missing numerical values using the mean.
- Filled missing categorical values using the mode.
- Identified and removed duplicate records.

### 3. Group Data by Category
- Grouped sales data by category.
- Calculated total revenue using the `total_price` column.
- Compared revenue across different categories.

### 4. Sort Data by Multiple Columns
- Sorted the dataset by category.
- Sorted total price within each category in descending order.

### 5. Correlation Matrix
- Selected numerical columns.
- Calculated the correlation matrix using Pandas.
- Created a correlation heatmap using Seaborn.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Anaconda

## Files

| File | Description |
|---|---|
| `Week_2_Python_Data_Analysis.ipynb` | Jupyter Notebook containing the complete analysis |
| `SQL_Sales_Dataset_200_Rows.csv` | Sales dataset used for analysis |
| `README.md` | Project documentation |

## Conclusion

This project demonstrates fundamental Python data analysis techniques including data loading, data cleaning, grouping, sorting, and correlation analysis using Pandas and visualization libraries.
