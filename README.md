# Cafe Sales Data Analysis

## Project Overview
This project focuses on cleaning, exploring, and analyzing a cafe’s transaction-level sales data to uncover key business insights. The analysis follows a complete end-to-end data analytics workflow, including data cleaning, exploratory data analysis (EDA), time-series analysis, and feature normalization.

The goal of this project is to practice and demonstrate core data analysis skills using Python and common data analysis libraries.

---

## Dataset Description
The dataset contains approximately 10,000 cafe transactions with the following attributes:
- Transaction ID
- Item
- Quantity
- Price per Unit
- Total Spent
- Payment Method
- Location
- Transaction Date

The raw data included missing values, invalid entries, and inconsistent data types, making it suitable for real-world data cleaning practice.

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git & GitHub

---

## Data Cleaning & Preprocessing
The following steps were performed to prepare the data for analysis:
- Standardized column names for consistency
- Replaced invalid values such as `"ERROR"` and `"UNKNOWN"` with missing values
- Converted numeric columns from text to numerical data types
- Parsed transaction dates into datetime format
- Removed rows missing critical information (date, item, quantity, price)

After cleaning, the dataset was reduced to a high-quality subset suitable for analysis.

---

## Exploratory Data Analysis (EDA)
Key exploratory steps included:
- Item-wise revenue analysis to identify top-performing products
- Visualization of total revenue contribution by item
- Examination of transaction patterns and sales distribution

These steps helped highlight which items drive the majority of sales.

---

## Time Series Analysis
To understand sales trends over time:
- Daily sales trends were analyzed to observe short-term fluctuations
- Monthly sales aggregation was performed to identify long-term patterns
- A 3-month rolling average was calculated to smooth volatility and reveal underlying trends

This approach provided a clearer view of overall business performance across time.

---

## Feature Scaling
- Min-Max normalization was applied to numerical features such as quantity, price per unit, and total spent
- Normalization prepares the dataset for potential downstream modeling and fair feature comparison

---

## Key Insights
- The dataset required significant cleaning before analysis, reflecting common real-world data issues
- A small number of items contributed disproportionately to total revenue
- Daily sales were volatile, while monthly trends showed relatively stable performance
- Rolling averages helped in identifying the underlying sales trend more clearly


## Conclusion
This project demonstrates a complete data analysis workflow, from raw data cleaning to insight generation. It emphasizes understanding data quality, performing exploratory analysis, and using time-series techniques to support data-driven decision-making.

