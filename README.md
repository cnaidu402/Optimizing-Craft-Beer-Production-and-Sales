# Optimizing-Craft-Beer-Production-and-Sales

# Overview
This project explores the factors that influence the quality, efficiency, and market trends of craft beer production. Using an extensive dataset and advanced analytics techniques, the project aims to uncover actionable insights to improve the brewing process, enhance resource utilization, and optimize profitability.

# Data
Source: Kaggle - Brewery Operations and Market Analysis Dataset
Size: 2.4 GB (9,545,009 x 20)
Key Features:
Batch ID, Brew Date, Beer Style, SKU
Location, Fermentation Time, Temperature
pH Level, Gravity, Alcohol Content
Bitterness, Color, Ingredient Ratio
Volume Produced, Total Sales, Quality Score
Brewhouse Efficiency, Loss Metrics (Brewing, Fermentation, Bottling/Kegging)
Objectives
Analyze alcohol trends and market requirements.
Improve brewhouse efficiency by identifying critical loss points.
Determine the most efficient and profitable beer styles.
Provide actionable insights for manufacturers.
# Approach
# 1. Data Preparation
Combined 10 data splits into a single DataFrame.
Performed data cleaning to address missing values and inconsistencies.
Derived new features for better analysis.
# 2. Exploratory Data Analysis (EDA)
Visualized trends, distributions, and relationships using statistical and visualization tools.
# 3. Machine Learning
Built predictive models using Logistic Regression with an accuracy of 50.0078%.
Root Mean Squared Error (RMSE) on test data: 0.4241.
# 4. Insights and Recommendations
Market Analysis: Ale is the most sold beer style, but it's the least efficient. Innovative manufacturing methods are suggested.
Bitterness Levels: Increase production of level 40 bitterness, which aligns better with sales demand.
# Tools and Techniques
Data Processing: Apache Spark on Databricks for scalability and efficiency.
Modeling: Regression models to estimate quality and optimize processes.
Visualization: Statistical tools for analyzing trends and patterns.
# Key Insights
Market Trends: Seasonal impacts, like the sales dip in December 2021 due to the pandemic.
Efficiency Challenges: Significant loss points identified during brewing and fermentation.
Sales Optimization: Aligning production with bitterness levels in demand.
# Conclusion
This project highlights the importance of data-driven decision-making in the brewing industry. By leveraging big data analytics and machine learning, we provide manufacturers with valuable strategies to enhance quality, efficiency, and profitability.
