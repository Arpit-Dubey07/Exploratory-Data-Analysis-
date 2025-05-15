# 🛒 Superstore Sales Analysis

This project explores and analyzes the **Superstore** dataset to uncover insights into sales performance across product categories, regions, and time. It uses Python for data cleaning, visualization, and trend analysis.

## 📁 Dataset Overview

The dataset contains 9,994 sales records with the following key columns:

- **Order ID, Order Date, Ship Date**
- **Customer ID, Segment, Region**
- **Product Category, Sub-Category**
- **Sales, Quantity, Discount, Profit**

The data is sourced from a fictional retail chain and simulates sales across the United States.

## 📌 Objectives

1. 🧾 Calculate total sales and profit.
2. 📊 Analyze sales trends across **categories** and **sub-categories**.
3. 🕒 Explore **seasonality** and **year-wise** sales patterns.
4. 🔎 Derive business insights from visualizations.

## 📈 Key Insights

- **Total Sales**: \$2.29 million
- **Top Category**: Technology (36.4% of sales)
- **Top Sub-Category**: Phones and Chairs lead in total sales.
- **Year with Highest Sales**: 2017

## 🛠️ Tools Used

- **Pandas**: Data manipulation
- **NumPy**: Numerical processing
- **Matplotlib & Seaborn**: Data visualization

## 📊 Visualizations

- Pie charts showing sales distribution by category and year
- Horizontal bar plots for sub-category-wise sales
- Temporal sales trends using `groupby` on year and month

## 📂 Files

- `superstore_analysis.ipynb`: Main notebook with EDA and visualizations
- `Sample - Superstore.csv`: The dataset
- `README.md`: Project description and insights

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/superstore-sales-analysis.git
   cd superstore-sales-analysis
