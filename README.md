# 📊 Sales Dashboard in Microsoft Excel

## 📌 Project Overview

This project demonstrates how to build a professional Sales Dashboard in Microsoft Excel using Pivot Tables, Pivot Charts, Slicers, and Excel formulas.

The dashboard provides business insights such as total sales, profit, quantity sold, regional performance, category performance, monthly sales trends, and top-performing products.

This project was created as part of my Data Analyst learning journey.

---

# 🎯 Objectives

- Learn Excel for Data Analytics
- Practice data cleaning and formatting
- Create Pivot Tables
- Build interactive Pivot Charts
- Design a professional dashboard
- Perform business analysis
- Prepare a portfolio project for Data Analyst interviews

---

# 🛠 Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Excel Tables
- Slicers
- Timeline Filter
- Excel Formulas

---

# 📂 Dataset

The dataset contains sales transactions including:

- Order ID
- Order Date
- Customer Name
- Region
- State
- Category
- Product Name
- Sales
- Quantity
- Profit

---

# 📈 Dashboard Features

✅ KPI Cards

- Total Sales
- Total Profit
- Total Orders
- Total Quantity

✅ Charts

- Sales by Region
- Sales by Category
- Monthly Sales Trend
- Profit by State
- Top 10 Products

✅ Interactive Filters

- Region
- Category
- Date Timeline

---

# 🚀 Step-by-Step Project Development

## Step 1: Import Dataset

- Open Microsoft Excel
- Load the sales dataset
- Check for missing values
- Verify data types

---

## Step 2: Convert Data into an Excel Table

- Select the dataset
- Press Ctrl + T
- Enable "My table has headers"
- Rename the table to:

SalesData

Why?

Excel Tables automatically expand when new data is added and make formulas easier to read.

---

## Step 3: Create KPI Cards

Create the following formulas:

### Total Sales

=SUM(SalesData[Sales])

### Total Profit

=SUM(SalesData[Profit])

### Total Orders

=COUNTA(SalesData[Order ID])

### Total Quantity

=SUM(SalesData[Quantity])

Format KPI cards using:

- Large Font
- Bold
- Background Color
- Center Alignment

---

## Step 4: Create Sales by Region Pivot Table

Rows

Region

Values

Sales

Create a Clustered Column Chart.

Business Insight

Identify the highest and lowest sales regions.

---

## Step 5: Create Sales by Category

Rows

Category

Values

Sales

Create a Doughnut Chart.

Business Insight

Understand category contribution to total sales.

---

## Step 6: Create Monthly Sales Trend

Rows

Order Date

Group Dates

- Months
- Years

Values

Sales

Create a Line Chart.

Business Insight

Identify seasonal sales trends.

---

## Step 7: Create Profit by State

Rows

State

Values

Profit

Sort Largest to Smallest.

Create a Horizontal Bar Chart.

Business Insight

Identify the most profitable states.

---

## Step 8: Create Top 10 Products

Rows

Product Name

Values

Sales

Apply Value Filters

Top 10

Sort Largest to Smallest.

Create a Column Chart.

Business Insight

Identify the best-selling products.

---

## Step 9: Add Slicers

Insert slicers for:

- Region
- Category
- Segment

Connect slicers to every Pivot Table.

---

## Step 10: Add Timeline

Insert Timeline using

Order Date

Allow users to filter the dashboard by year or month.

---

## Step 11: Dashboard Design

Arrange all charts professionally.

Dashboard Layout

Top

- KPI Cards

Middle

- Sales by Region
- Sales by Category

Bottom

- Monthly Sales Trend
- Profit by State
- Top 10 Products

Use a consistent color theme.

---

# 📊 Business Insights

The dashboard answers questions such as:

- Which region generates the highest sales?
- Which category contributes the most revenue?
- Which state generates the highest profit?
- What are the monthly sales trends?
- Which products perform best?

---

# 📚 Skills Learned

✔ Excel Tables

✔ Pivot Tables

✔ Pivot Charts

✔ Data Cleaning

✔ Dashboard Design

✔ Business Analysis

✔ Data Visualization

✔ Excel Formulas

✔ Interactive Reporting

---

# 🎯 Interview Questions Covered

- What is a Pivot Table?
- Why use Excel Tables?
- Difference between Bar and Column Charts
- Why use Line Charts?
- When should Doughnut Charts be used?
- How do Slicers work?
- What are KPIs?
- How do Pivot Charts update automatically?

---

# 📸 Dashboard Preview

(Add dashboard screenshot here)

dashboard.png

---

# 📁 Project Structure

Sales-Dashboard/

│── Sales Dashboard.xlsx

│── Dashboard Screenshot.png

│── README.md

│── Dataset.xlsx

---

# 👨‍💻 Author

Shashi Kumar

🎓 BCA Graduate

📚 MCA Student in 3rd 

🎯 Aspiring Data Analyst

GitHub:
https://github.com/shashibabu123

LinkedIn:
https://www.linkedin.com/in/shashi-kumar-74225b334

---

# ⭐ Future Improvements

- Power Query Integration
- Power Pivot
- Power BI Dashboard
- SQL Data Source
- Python Automation
- Forecasting
- Interactive Navigation Buttons 
