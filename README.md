# Superstore Sales Analysis - Data Analysis Project

## 1. Project Definition

This project is about exploring and understanding the sales data of a retail company, the **Superstore Sales Dataset**. The dataset contains information such as order date, ship date, shipping mode, customer segment, region, state, product category, sub-category, sales, quantity, discount, and profit.

The main aim of the project is not just to make graphs, but to first **clean the data and then use it to find simple and useful business patterns**. We will use Python to answer questions such as:

- Which product categories and sub-categories generate the most sales and profit?
- Which regions and states perform best, and which perform worst?
- Which customer segment contributes the most revenue?
- How have sales and profit changed over the months and years?
- Do higher discounts reduce profit?
- Which products are top sellers, and which ones lose money?
- Is high sales always linked to high profit?

The final output will be a cleaned dataset, at least **6 visualizations**, and a short report explaining what we found from the data.

---

## 2. Dataset Used

**Dataset:** Superstore Dataset

**Source:** Kaggle

**Link:** https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The main file we will use for the analysis is **`Sample - Superstore.csv`**.

The file contains:

- **9,994 rows** (order line items)
- **21 columns**
- Information about orders, customers, locations, products, sales, discounts, and profit

### Important columns

| Column | What it tells us |
|---|---|
| `Order Date` | Date when the order was placed |
| `Ship Date` | Date when the order was shipped |
| `Ship Mode` | Shipping method (Standard, Second, First, Same Day) |
| `Segment` | Customer segment (Consumer, Corporate, Home Office) |
| `Region` / `State` / `City` | Where the order was delivered |
| `Category` / `Sub-Category` | Product group |
| `Product Name` | Name of the product |
| `Sales` | Sales amount |
| `Quantity` | Number of units sold |
| `Discount` | Discount applied to the order |
| `Profit` | Profit (or loss) on the order |

---

## 3. Dataset Use Case

This dataset can be used to understand the performance of a retail business from a data-analysis point of view.

For example, a store manager could use this type of analysis to decide which product categories to promote, which regions need attention, which products are losing money, and how much discount is safe to offer.

For our project, we are mainly using the dataset for **learning data cleaning, exploratory data analysis (EDA), visualization, and basic business insight generation**.

We are not trying to predict future sales. The focus is on understanding the data and finding patterns from the available information.

---

## 4. Data Cleaning and Preparation

Before making visualizations, we will clean and prepare the data.

- **Missing values:** check every column for missing values and handle them carefully instead of deleting rows unnecessarily.
- **Duplicates:** check for duplicate records, including repeated `Row ID` values.
- **Data types:** convert `Order Date` and `Ship Date` from text to **datetime**, and confirm that `Sales`, `Quantity`, `Discount`, and `Profit` are numeric.
- **New columns:** create `Order Year`, `Order Month`, and `Profit Margin` (Profit / Sales x 100).
- **Outliers:** inspect extreme sales and profit values using the IQR method and box plots. We will not delete them automatically, because large orders and large losses may be real and important.

---

## 5. Visualizations Planned

We will create at least **6 visualizations**. The final number can be higher if additional plots give useful information.

### Visualization 1 - Sales and Profit by Category

**Graph:** Grouped bar chart

**What we want to understand:** Which of Furniture, Office Supplies, and Technology earns the most sales and profit.

**Expected outcome:** Technology is likely to lead in profit, while Furniture may show high sales but a low profit margin.

---

### Visualization 2 - Sales and Profit by Sub-Category

**Graph:** Horizontal bar chart

**What we want to understand:** Which product groups are strong, and which ones lose money.

**Expected outcome:** Some sub-categories (for example, Tables) may show high sales but negative profit, showing that sales alone do not mean success.

---

### Visualization 3 - Sales and Profit by Region

**Graph:** Bar chart or pie chart

**What we want to understand:** How sales and profit are distributed across regions.

**Expected outcome:** One region will likely lead in sales and profit, while another may show weaker profitability.

---

### Visualization 4 - Sales by Customer Segment

**Graph:** Pie chart or bar chart

**What we want to understand:** Which customer segment brings in the most revenue.

**Expected outcome:** The Consumer segment is likely to contribute the largest share.

---

### Visualization 5 - Top 10 Products by Sales

**Graph:** Horizontal bar chart

**What we want to understand:** Whether a small number of products generate a large part of total sales.

**Expected outcome:** A few products stand out clearly, and we can compare them with the most profitable products.

---

### Visualization 6 - Monthly Sales Trend

**Graph:** Line chart

**What we want to understand:** Whether sales follow a seasonal pattern across months.

**Expected outcome:** Sales are likely to rise in the last months of the year and be lower early in the year.

---

### Visualization 7 - Year-wise Sales and Profit

**Graph:** Line chart or grouped bar chart

**What we want to understand:** Whether the business is growing from year to year.

**Expected outcome:** An overall upward trend in sales, with profit possibly growing at a different rate.

---

### Visualization 8 - Discount vs Average Profit

**Graph:** Bar chart or scatter plot

**What we want to understand:** How different discount levels affect profit.

**Expected outcome:** Higher discounts are likely to be linked with lower or negative profit.

---

### Visualization 9 - Top 10 States by Sales

**Graph:** Horizontal bar chart

**What we want to understand:** Which states contribute the most to total sales.

**Expected outcome:** A small group of states is likely to account for a large share of sales.

---

### Visualization 10 - Correlation Heatmap

**Graph:** Heatmap

**What we want to understand:** How `Sales`, `Quantity`, `Discount`, and `Profit` relate to each other.

**Expected outcome:** Sales and profit show a positive relationship, while discount shows a negative relationship with profit. Correlation does not prove cause and effect.

---

## 6. Python Libraries / Tools We Will Use

| Tool | Used for |
|---|---|
| **Python** | Main language for cleaning, analysis, and visualization |
| **Pandas** | Reading the CSV, cleaning, grouping, filtering, creating new columns |
| **NumPy** | Numerical operations and calculations |
| **Matplotlib** | Bar charts, line charts, histograms, scatter plots, pie charts |
| **Seaborn** | Statistical plots and the correlation heatmap |
| **Google Colab / Jupyter Notebook** | Writing and running code step by step, keeping charts and notes together |
| **Kaggle** | Source of the dataset |
| **Git and GitHub** | Version control and publishing the project |

---

## 7. What We Expect to Learn from the Dataset

- Which categories, sub-categories, regions, and segments perform best.
- Why high sales do not always mean high profit.
- How sales change over time.
- How discounts affect profitability.
- How outliers can affect analysis.

Each graph will be followed by a **short insight** explaining what we can learn from it.

---

## 8. Final Deliverables

1. **Cleaned dataset / cleaned dataframe**
2. **Jupyter notebook (`.ipynb`)** with the complete analysis
3. **At least 6 visualizations**
4. **Short insights for each visualization**
5. **Final summary / report** explaining the main findings
6. **GitHub repository** with documentation

---

## 9. GitHub Repository and Documentation



```text
Superstore-Sales-Analysis/
│
├── Superstore-Sales-Analysis.ipynb   # Complete analysis notebook
├── Sample - Superstore.csv           # Dataset
└── README.md                         # Project documentation (this file)
```

### How to run the project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Superstore-Sales-Analysis.git
   ```
2. Open Google Colab and upload `Superstore-Sales-Analysis.ipynb`.
3. Upload `Sample - Superstore.csv` when the notebook asks for it.
4. Run the cells from top to bottom to reproduce the analysis.

---

## 10. Project Flow

```text
Kaggle Dataset
      ↓
Load CSV using Pandas
      ↓
Check data shape and columns
      ↓
Data Cleaning
(Missing Values + Duplicates + Data Types + Outliers)
      ↓
Data Preparation
      ↓
Exploratory Data Analysis
      ↓
Create 6+ Visualizations
      ↓
Write Short Insights
      ↓
Final Report / Conclusion
```

---

## 11. Conclusion

This project will use the Superstore Sales dataset to practice the complete basic data-analysis workflow. We will start with raw data, clean it properly, create meaningful visualizations, and explain the business patterns we find in simple language.

The goal is to show not only that we can write Python code and make graphs, but also that we can **understand a dataset and turn it into useful information for decision making**.

---

**Project By:** Ridham Patel and Purv Banugariya
