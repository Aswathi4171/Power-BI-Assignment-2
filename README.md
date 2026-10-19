# Power-BI-Assignment-2
# Power BI Sectional Assignment II

## 📌 Project Overview
This project focuses on data visualization, calculated columns, and DAX measures using Microsoft Power BI. The objective is to analyze order data, customer information, and employee layoffs through interactive visualizations and data calculations.

## 🛠️ Tools Used
- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- Microsoft Excel
- CSV files

## 📂 Datasets Used
The project uses the following datasets:

1. **Amazingcart.xlsx** – Contains order information, including Order ID and Country.
2. **Customer_Data.xlsx** – Contains customer details, product information, quantity, price, and order dates.
3. **Employee_Layoffs.csv** – Contains employee layoff information by location.

## 📊 Tasks Performed

### 1. Data Visualization
Created the following visualizations in Power BI:

- **Clustered Column Chart:** Displays the number of orders by country.
- **Line Chart:** Shows the count of orders over time.
- **Pie Chart:** Represents total employee layoffs by location.

### 2. Calculated Column
Created a calculated column using DAX to calculate the total price.

```dax
New Total Price =
'Customer Data'[Quantity] *
'Customer Data'[Price Per Unit]
```

This calculates the total price using quantity and price per unit.

### 3. DAX Measures
Created DAX measures to perform data calculations:

- **Total Sales:** Calculates the sum of sales.
- **Total Rows:** Counts the total number of rows.
- **Valid Records:** Counts nonblank order IDs.
- **Missing Values:** Counts missing values in the selected columns.
- **Minimum Quantity:** Finds the smallest quantity.
- **Maximum Quantity:** Finds the largest quantity.

## 📈 Key Learnings
- Importing Excel and CSV datasets into Power BI.
- Creating charts and visualizations.
- Using Power Query for data preparation.
- Creating calculated columns with DAX.
- Writing DAX measures for data analysis.
- Analyzing orders and employee layoffs.

## 📁 Project Structure

```text
Power-BI-Sectional-Assignment-II/
│
├── Amazingcart.xlsx
├── Customer_Data.xlsx
├── Employee_Layoffs.csv
├── Power_BI_Sectional_Assignment_II.pbix
└── README.md
```

*Note: Update the filenames in this structure to match the actual files you upload to GitHub.*

## ✅ Conclusion
This project demonstrates practical skills in data visualization, data analysis, calculated columns, and DAX measures using Microsoft Power BI.

It provides hands-on experience in transforming raw datasets into meaningful insights through charts and calculations.

---

**Project:** Power BI Assignment 2  
**Tool:** Microsoft Power BI Desktop
