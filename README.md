# 📊 Exploratory Data Analysis (EDA) on Sales Data

This project focuses on performing data cleaning, preprocessing, and exploratory data analysis (EDA) on a global retail dataset (Global Superstore). The goal is to uncover key business insights related to sales performance, profitability, and regional trends. <br>

# 📂 Project Overview

The dataset contains transactional sales data with 1000 records and 24 features, including:<br>

Order & Shipping details<br>
Customer & location data<br>
Product categories & sub-categories<br>
Sales, Profit, Discount, Quantity, Shipping Cost<br>
# 🧹 Data Cleaning & Preprocessing

Key steps performed:<br>

Checked for missing values<br>
Identified missing values in Postal Code (806 missing)<br>
Converted:<br>
Order Date → datetime<br>
Ship Date → datetime<br>
Verified data types and structure<br>
Ensured dataset consistency for analysis<br>
# 📊 Exploratory Data Analysis (EDA)
🔹 Summary Statistics<br>
Total Sales: 1,710,971<br>
Total Profit: 288,920<br>
Dataset shape: (1000, 24)<br>
# 🔹 Key Analyses Performed
1. Top-Selling Products<br>
Smartphones dominate top sales (Motorola, Apple, Cisco)<br>
2. Sales by Region<br>

# Top-performing regions:

Western Europe<br>
Oceania<br>
Southern Asia<br>
# 3. Correlation Analysis
Sales vs Profit: +0.53 (positive relationship)<br>
Discount vs Profit: -0.51 (higher discounts reduce profit)<br>
# 4. Profitability Analysis

Most profitable categories:<br>

Technology<br>
Furniture<br>
Office Supplies<br>
# 📈 Data Visualisations

The following visualisations were created:<br>

📊 Bar chart → Sales by category<br>
📈 Line chart → Monthly sales trend<br>
🔵 Scatter plot → Sales vs Profit<br>
🔥 Heatmap → Sales by region & category<br>
# 💡 Key Insights
Technology is the most profitable and highest-selling category<br>
Strong positive relationship between sales and profit<br>
High discounts negatively impact profitability<br>
Sales show seasonality, with peaks at year-end<br>
Western Europe and Asia regions drive the majority of revenue<br>
Some transactions generate negative profit, indicating pricing or cost issues<br>
# 📉 Time Series Analysis
Sales show a consistent upward trend<br>
Clear seasonal spikes, especially during end-of-year periods<br>
Indicates opportunity for targeted seasonal campaigns<br>
# 🚀 Recommendations
Focus on the Technology & Furniture categories for growth<br>
Reduce excessive discounting to protect profit margins<br>
Target high-performing regions (Europe & Asia)<br>
Investigate loss-making transactions<br>
Leverage seasonal trends for marketing campaigns<br>
# 🛠️ Tech Stack
Python<br>
Pandas<br>
NumPy<br>
Matplotlib<br>
Seaborn<br>
Statsmodels<br>
Google Colab<br>
