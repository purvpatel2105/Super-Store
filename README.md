# Superstore-Sales-Analysis 📊

Data cleaning, exploratory data analysis and visualization of Superstore sales data using Python.

# Superstore Sales Analysis 📊

## 📌 Project Overview

This project analyzes the **Superstore Sales Dataset** using Python.

The main purpose of this project is to clean the dataset, explore sales and profit patterns, analyze customer segments and regions, and create meaningful visualizations to understand business performance.

The project follows a complete data analysis workflow starting from **raw CSV data → data cleaning → exploratory data analysis → visualization → business insights**.

## 🎯 Objectives

* Load and understand the Superstore dataset
* Clean and prepare the data for analysis
* Check missing values and duplicate records
* Analyze data types and date columns
* Analyze total sales, profit and quantity
* Analyze sales by category and sub-category
* Analyze sales and profit by region
* Analyze customer segments
* Analyze shipping methods
* Find top-selling products
* Find most profitable products
* Analyze monthly and yearly sales trends
* Analyze the relationship between discount and profit
* Perform correlation analysis
* Create meaningful data visualizations
* Generate useful business insights

## 📂 Dataset

The dataset used in this project is the **Superstore Dataset**.

📂 [Dataset – Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The dataset contains information such as:

* Row ID
* Order ID
* Order Date
* Ship Date
* Ship Mode
* Customer ID
* Customer Name
* Segment
* Country
* City
* State
* Postal Code
* Region
* Product ID
* Category
* Sub-Category
* Product Name
* Sales
* Quantity
* Discount
* Profit

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## 🔍 Data Cleaning & Preparation

The dataset was inspected and prepared before performing the analysis.

The following steps were performed:

1. Loaded the CSV dataset using Pandas
2. Checked the dataset shape and column names
3. Checked missing values
4. Checked duplicate records
5. Examined data types
6. Converted `Order Date` into proper date format
7. Converted `Ship Date` into proper date format
8. Extracted the year from `Order Date`
9. Verified numerical columns such as Sales, Quantity, Discount and Profit
10. Prepared the dataset for exploratory data analysis

## 📊 Exploratory Data Analysis

The project analyzes different aspects of the Superstore business data.

### 💰 Overall Business Performance

The following metrics were calculated:

* Total Sales
* Total Profit
* Total Quantity Sold
* Average Order Value
* Overall Profit Margin

### 📦 Category Analysis

Sales and profit were analyzed across:

* Furniture
* Office Supplies
* Technology

The analysis helps identify which categories generate the highest sales and profit.

### 🏷️ Sub-Category Analysis

The project analyzes:

* Sales by Sub-Category
* Profit by Sub-Category

This helps identify the best-performing and low-performing product groups.

### 🌎 Regional Analysis

Sales and profit were analyzed across different regions.

The project identifies:

* Region with highest sales
* Region with highest profit
* Regional sales distribution
* Regional profit performance

### 👥 Customer Segment Analysis

Sales were analyzed across:

* Consumer
* Corporate
* Home Office

This helps understand which customer segment contributes the most revenue.

### 🚚 Ship Mode Analysis

Sales were analyzed based on different shipping methods:

* Standard Class
* Second Class
* First Class
* Same Day

### 🏆 Product Analysis

The project identifies:

* Top 10 products by sales
* Top 10 most profitable products
* Bottom 10 products by profit

This helps understand which products contribute most to business performance.

## 📅 Time-Based Analysis

The project analyzes sales trends over time.

### Monthly Analysis

Monthly sales were calculated to identify:

* High-sales months
* Low-sales months
* Overall sales trends

### Yearly Analysis

Year-wise sales and profit were analyzed to understand business growth and performance over different years.

## 📉 Discount & Profit Analysis

The relationship between **Discount** and **Profit** was analyzed.

This helps understand whether increasing discounts have an effect on average profit.

A visualization was created to observe the relationship between discount levels and profitability.

## 🔗 Correlation Analysis

Correlation analysis was performed on the following numerical variables:

* Sales
* Quantity
* Discount
* Profit

A correlation matrix and heatmap were created to understand relationships between these variables.

## 📊 Data Visualizations

The project includes several visualizations such as:

* Sales by Category
* Profit by Category
* Sales by Region
* Sales by Customer Segment
* Top 10 Products by Sales
* Monthly Sales Trend
* Sales vs Profit
* Top 10 States by Sales
* Sales and Profit by Category
* Discount vs Average Profit
* Correlation Heatmap
* Year-wise Sales and Profit
* Sales by Sub-Category
* Profit by Sub-Category

These visualizations make it easier to identify important business patterns and trends.

## 💡 Key Insights

From the analysis, we can understand that:

* Sales and profit vary significantly across categories.
* Different regions contribute differently to overall sales and profit.
* Customer segments have different levels of sales contribution.
* A small number of products generate a significant portion of sales.
* Some products generate high sales but comparatively lower profit.
* Sales performance changes over time.
* Discounts can have an impact on profitability.
* Sales, quantity, discount and profit have different relationships with each other.
* Some states and regions contribute significantly to overall business performance.
* Profitability is not always directly proportional to sales.

## 📈 Business Analysis

The analysis can help businesses:

* Identify high-performing product categories
* Identify profitable and low-profit products
* Understand customer segment performance
* Compare regional performance
* Monitor sales trends
* Understand the effect of discounts
* Improve product and pricing strategies
* Make data-driven business decisions

## 📁 Project Structure

```text
Superstore-Sales-Analysis/
│
├── Superstore-Sales-Analysis.ipynb
├── Sample - Superstore.csv
└── README.md
```

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Superstore-Sales-Analysis.git
```

### 2. Open Google Colab

Upload:

```text
Superstore-Sales-Analysis.ipynb
```

### 3. Upload the Dataset

Upload the Superstore CSV file when requested by the notebook.

### 4. Run the Notebook

Run the cells from top to bottom to reproduce the analysis.

## 📌 Project Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Date Conversion
     ↓
Exploratory Data Analysis
     ↓
Statistical Analysis
     ↓
Data Visualization
     ↓
Business Insights
     ↓
Conclusion
```

## 📚 Learning Outcomes

Through this project, the following skills were developed:

* Python Data Analysis
* Pandas
* NumPy
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Matplotlib
* Seaborn
* GroupBy Analysis
* Time-Series Analysis
* Correlation Analysis
* Business Intelligence
* Data Interpretation

## ✅ Conclusion

This project demonstrates the complete process of analyzing a real-world retail dataset using Python.

Starting from raw Superstore sales data, the project performs data inspection, cleaning, exploratory analysis, visualization and business interpretation.

The analysis provides useful insights into **sales, profit, products, customer segments, regions, discounts and time-based trends**.

Python libraries such as **Pandas, NumPy, Matplotlib and Seaborn** were used to transform raw data into meaningful information.

Overall, this project demonstrates how data analysis can be used to understand business performance and support **data-driven decision making**.

## 👨‍💻 Project By

**Your Name**

Superstore Sales Analysis
Data Analysis Project

## ⭐ If you found this project useful

Feel free to ⭐ star this repository and use the project for learning and educational purposes.
