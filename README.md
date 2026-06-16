🔍 Exploratory Data Analysis (EDA) | DecodeLabs Internship

📊 Project Overview

Performed exploratory data analysis on the cleaned dataset from
Project 1 to uncover patterns, trends, outliers, and correlations
within 1,200 e-commerce orders.

📁 Files in This Repository

FileDescription

EDA_FINDINGS.txt ---> Full written findings & business insights

Project2Workspace.ipynb ---> Complete analysis notebook

Dataset_Cleaned_Project1.csv --> Dataset cleaned in Project1 

01_distribution_analysis.png -----> Histograms of numeric variables

02_outlier_boxplots.png ----> Boxplots showing outliers

03_categorical_distribution.png----> Bar charts of categorical data

04_correlation_heatmap.png -----> Correlation matrix heatmap

05_scatter_plots.png -----> Quantity vs Price relationships

06_trend_analysis.png -----> Revenue/orders over time


🎯 Goal

Analyze the dataset to understand patterns, trends, and
distributions using descriptive statistics.

🔧 What Was Done

1. Descriptive Statistics

Calculated mean, median, std deviation, min/max for all numeric
fields (Quantity, UnitPrice, TotalPrice).

2. Distribution Analysis

Identified skewness in order values — right-skewed distribution,
meaning most orders are moderate value with a few high-value outliers.

3. Outlier Detection (IQR Method)

Flagged high-value orders beyond Q3 + 1.5×IQR as potential VIP
customer segment.

4. Correlation Analysis

Found strong positive correlation between Quantity and TotalPrice
(validates Project 1 data quality).

5. Trend Analysis

Tracked monthly order volume, revenue trends, top products, and
referral source performance.

💡 Key Business Insights


Median order value is notably lower than mean → revenue

concentrated among a smaller set of high-value orders

Strong correlation confirms cleaned data integrity

Top referral channels drive majority of order volume

Identified outlier orders worth investigating as VIP segment


🛠️ Tools Used

Python, Pandas, Matplotlib, Seaborn, SciPy, Google Colab

📚 Key Learnings


Five-number summary & distribution shape analysis

IQR vs Z-score outlier detection methods

Correlation ≠ Causation principle

Translating statistical findings into business recommendations
