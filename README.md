# Uncovering Trends in Nigeria’s Sales Data #

## 📊 Project Overview
The “Uncovering Trends in Nigeria’s Sales Data” project is a data analytics and business intelligence project focused on analyzing sales transactions across different regions, products, customers, and sales channels in Nigeria. The main objective is to clean raw sales data, identify meaningful business patterns, and generate insights that support better decision-making. The dataset commonly includes customer information, product categories, sales quantity, revenue, pricing, discounts, and regional performance.

## 📊 Project Objective 
-- Analyze overall sales performance
-- Identify high-performing and low-performing products
-- Understand customer purchasing behavior
-- Detect regional and seasonal sales trends
-- Evaluate profit and revenue generation
-- Build interactive dashboards for visualization
-- Support business decision-making using data insights

## 🗂️ Data Source
Source:https://www.kaggle.com/datasets/lawrenceekeogu/sales-dataset/data

Year / Timeline: Data collected during 2025 to 2026

Dataset Description:

Name - Uncovering Trends in Nigeria’s Sales Data 

Column : 600 rows 

Features : 9 columns

# Key features #
Order ID: Unique identification number for each transaction.

Sale Date / Date: The exact date the transaction occurred.

Customer Name: Name of the buyer.

State / Region: The geographical location or state in Nigeria where the order was placed or shipped to.

Product / Category: The item sold or its general category.

Units Sold / Quantity: The amount of items purchased in the transaction.

Unit Price: The cost per individual item.

Total Sale: The total monetary value of the order.

Sales Channel: Where the purchase was made (e.g., Online, Wholesale, or In-Store).

Profit : actual value in 

## 🛠️ Tools & Technologies
- **Language:** Python (Pandas, numpy, matplotlib,seaborn)
- **Visualization:** Power BI, Matplotlib ,Seaborn, Excel
- **Documentation:** Google Colab

## 🔍 Exploratory Data Analysis ##
## 🧹 Data Cleaning & Preparation

-- Removing duplicates

-- Handling null values

-- Correcting data types

-- Formatting dates

-- Treating outliers

## Added Features ##

Profit : Absolute value

Profit Margin : percentable 

## 🔍 Exploratory Data Analysis (EDA)

Univariate Analysis → distribution of single variables

Bivariate Analysis → relation between two variables 

Multivariate Analysis → relation among Three variables 

## 🔍 Visualization Used ##

-- Histograms(This histogram highlights the spread of Sale)

-- Box Plots(Wide spread means products have varying price ranges,High-price outliers indicate premium or luxury products)

-- Count Plots(This countplot reveals the popularity of product categories)

-- Scatter Plots(This scatterplot shows a positive correlation, indicating that higher-priced items generally lead to higher revenue)

-- Bar Plot (The barplot shows which sales channel—Wholesale, Retail, or Online—contributes most)

-- Heatmaps(This heatmap highlights strong correlations (e.g., strong positive link between UnitsSold and TotalRevenue)

-- Pair Plots(The pairplot serves as a summary It shows the distribution of every metric while highlighting regional clusters)

-- Bubble Charts(These are your "stars"—high revenue and high profit)

-- Violin Plots(Represents the median price for that specific "Units Sold" category)

-- Pivot Tables(This visualization is critical for resource allocation. It identifies "Dead Zones" (low profit/certain channel) and "Gold Mines" (high profit/certain channel)

## 🔍 Dashboard Features 

A dashboard in the Nigeria Sales Data project is designed to provide a clear and interactive view of business performance. It combines charts, KPIs, filters, and visual analytics to help users quickly understand sales trends and make data-driven decisions.

1. KPI Cards (Key Performance Indicators)

2. Sales Trend Analysis

3. Regional Sales Analysis

4. Product Category Performance

5. Customer Analysis

6. Profitability Analysis

7. Discount Analysis

8. Interactive Filters & Slicers
   
## 💡 Key Insights

-- Identified regional and seasonal sales trends using exploratory data analysis.

-- Detected high-performing product categories and customer segments.

-- Analyzed the impact of discounts on profitability.

-- Used visualization techniques to uncover sales anomalies and business opportunities.

-- Built interactive dashboards to support data-driven business decisions.

## 🚀 Recommendations

-- The analysis suggests that businesses should:

-- Focus on profitable regions and products

-- Reduce unnecessary discounts

-- Improve inventory planning

-- Strengthen customer retention

-- Use dashboards for continuous monitoring

-- Apply data-driven strategies for growth

## Conclutions 
The analysis showed that sales performance in Nigeria varies significantly across regions, product categories, customer groups, and time periods. By analyzing historical sales data, the project helped identify profitable opportunities, operational challenges, and customer behavior patterns that directly impact revenue and profitability.

<img width="1291" height="666" alt="Screenshot 2026-05-18 183730" src="https://github.com/user-attachments/assets/75f6d6aa-c040-4cd6-8997-ffef1b066ea9" />


## ⚙️ How to Use
## Step 1: Install Required Software

## Download and install:

Power BI Desktop

Python (optional for Python visuals)

## Step 2: Prepare the Dataset

Your dataset should be in:

CSV format

Excel format (.xlsx)

## Step 3: Open Power BI
Launch Power BI Desktop

Click Home → Get Data

## Select:
Excel

CSV

Browse and load your Nigeria sales dataset.

## Step 4: Clean the Data in Power Query

## After loading:

Click Transform Data

Power Query Editor opens.

## Step 5: Create Relationships (If Multiple Tables Exist)

## If your project contains:

Sales Table

Customer Table

Product Table

## Then:

Go to Model View

Drag matching columns to create relationships.

## Example:

Customer ID ↔ Customer Table
Product ID ↔ Product Table

## Step 6: Create Calculated Measures (DAX)

## Go to:

Modeling → New Measure

## Step 7: Build Dashboard Visualizations

KPI Cards

Use:

## Card Visual

## Step 8: Add Charts

Sales Trend

## Visual:

Line Chart

## Fields:

X-Axis → Order Date

Y-Axis → Sales Amount

## Purpose:

Monthly/yearly sales trends

Regional Analysis
## Visual:
Bar Chart or Map

## Fields:

Region

Sales Amount

## Purpose:

Compare regional performance

## Product Analysis
## Visual:

Pie Chart 

Fields:

Product Category
Sales

## Purpose:

Best-selling products

Profit Analysis

## Visual:
Scatter Plot

## Fields:

Sales

Profit

Purpose:

Understand profitability

## Step 9: Add Filters & Slicers

Use:

Slicer Visual

## Add filters for:

-- Region

-- Product Category

-- Date

-- Customer Segment

Purpose:

Interactive dashboard filtering

## Step 10: Add Python Visuals (Optional)

If using Python charts:

## Enable Python

Go to:

File → Options → Python scripting

Select Python installation path.

Add Python Visual

Select Python Visual

Drag required columns

Paste Python code.

## Step 11: Design Dashboard Properly
-- Best Practices

-- Align charts properly

-- Use consistent colors

-- Keep KPIs at top

-- Add titles and labels

-- Avoid overcrowding visuals

## Step 12: Generate Insights

## Analyze:

Top-performing regions

Sales growth trends

Profitability

Customer behavior

## Step 13: Save the Project

Save Power BI file:

Nigeria_Sales_Dashboard.pbix

Step 14: Export Dashboard

Go to:

File → Export

Export as:

PDF
PowerPoint

https://github.com/Nirosha-mca/Main-project



