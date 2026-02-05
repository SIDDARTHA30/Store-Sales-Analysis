=# Store Sales Data Analysis using Python

## Project Overview
This project performs data analysis on store sales data to understand sales performance across multiple stores and months.

The dataset contains monthly sales of 100 stores located in different cities.  
The main goal of this project is to analyze sales trends, identify top performing stores, and generate business insights.

---

## Tools Used
- Python
- Pandas
- NumPy

---

## Dataset Information
The dataset contains:
- 100 stores
- City of each store
- Monthly sales from January to December

Columns include:
store_id, city, Jan, Feb, Mar, Apr, May, Jun, July, Aug, Sep, Oct, Nov, Dec

---

## Work Done in This Project

### Data Exploration
- Loaded dataset using Pandas
- Checked dataset shape, columns and data types
- Explored basic structure of the data

### Sales Analysis
- Calculated total sales per month
- Calculated average monthly sales
- Found total yearly sales across stores

### Feature Engineering
New columns were created:
- TOTAL_SALES → total sales per store (Jan–Apr)
- AVERAGE_SALES → average monthly sales per store
- MONTH_MAX → best performing month per store

### Store Performance Analysis
- Identified top 5 stores with highest sales
- Identified bottom 5 stores with lowest sales
- Found store with highest sales in March
- Found store with lowest sales in April
- Identified month with highest overall sales

### Business Queries
- Filtered high performing stores from California
- Sorted stores based on average performance

---

## Key Insights
- February recorded the highest overall sales
- Some stores consistently performed better across months
- Significant variation exists between top and low performing stores
- Sales performance differs across cities

---

## Skills Demonstrated
- Data cleaning and exploration
- Data analysis using Pandas
- Feature engineering
- Business insight generation

---

## Conclusion
This project demonstrates how Python can be used to analyze sales data and generate meaningful business insights.
