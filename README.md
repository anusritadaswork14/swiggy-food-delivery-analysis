#Swiggy Food Delivery Data Analysis

### Food Delivery & E-Commerce Analytics | Python | Exploratory Data Analysis

## Project Overview

This project focuses on analysing Swiggy food delivery order data to understand customer ordering behaviour, food preferences, restaurant performance, delivery efficiency and customer satisfaction.

The analysis was carried out as part of the **Sapphire IQ Data Analytics Internship Project** using Python. The objective was to explore the dataset, identify meaningful patterns, compare business performance across different categories and cities, and develop practical recommendations based on the findings.

The project uses Python-based data analysis and visualisation techniques to translate raw order data into useful business insights.

## Project Objectives

The analysis addresses four key objectives outlined in the project brief.

### 1. Overall Order and Customer Patterns

- Understand the typical amount customers spend on food orders.
- Identify the most popular food categories and restaurants.
- Identify the cities receiving the highest number of orders.
- Examine customer ratings, payment preferences and order status.

### 2. Relationships Between Customer Orders and Delivery Performance

- Investigate whether higher-value orders take more time to deliver.
- Compare average order amounts across cities.
- Examine the relationship between delivery time and customer satisfaction.
- Identify food categories receiving higher customer ratings.

### 3. Business Performance Across Different Groups

- Compare order values across food categories and cities.
- Identify cities with longer average delivery times.
- Compare customer ratings across cities and food categories.
- Examine restaurant and food category performance across different cities.

### 4. Ordering Trends and Business Recommendations

- Identify the days with the highest number of orders.
- Determine the busiest ordering hours.
- Analyse food category preferences across different time periods.
- Develop recommendations to improve delivery services, customer satisfaction and business performance.

## Tools and Technologies

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Jupyter Notebook | Interactive analysis environment |

## Project Workflow

The analysis followed these stages:

1. **Data Loading:** Imported the food delivery dataset into Python using Pandas.
2. **Data Exploration:** Examined the dataset structure, dimensions, column information and descriptive statistics.
3. **Data Cleaning:** Checked data quality and handled date and time conversions to support time-based analysis.
4. **Exploratory Data Analysis:** Analysed order patterns, customer behaviour, restaurant performance and delivery metrics.
5. **Statistical Analysis:** Examined numerical distributions, descriptive statistics and correlations between selected variables.
6. **Data Visualisation:** Created charts and heatmaps using Matplotlib and Seaborn.
7. **Business Interpretation:** Identified key observations and developed practical recommendations.

## Analysis and Visualisations

The notebook explores the following areas:

### A. Order and Customer Behaviour
- Order status distribution.
- Food category-wise order distribution.
- Order distribution across cities.
- Payment method preferences.
- Customer rating distribution.
- Average order value across food categories.
- Average customer ratings by food category.

### B. Restaurant Performance
- Top 10 restaurants by number of orders.
- Top 10 restaurants by average order value.
- Restaurant order distribution across cities.

### C. Delivery Performance
- Average delivery time by order status.
- Delivery time distribution using box plots.
- Average delivery time by month.
- Average delivery time across cities.

### D. Time-Based Ordering Trends
- Monthly order trends.
- Order distribution by day of the week.
- Order distribution by hour.
- Food category preferences across different time periods.

### E. Statistical and Relationship Analysis
- Descriptive statistics for numerical variables.
- Correlation matrix and correlation heatmap.
- Relationship between order value and delivery time.
- Relationship between delivery time and customer ratings.
- Average food category ratings across cities.
- Average order value across cities and food categories.

## Key Findings

The exploratory analysis revealed several notable patterns:

- **Order activity:** The dataset contains 15,000 order records, with 14,083 delivered orders, 697 cancelled orders and 220 returned orders.
- **Popular food categories:** North Indian food recorded the highest order count (2,402), followed by Biryani (1,986).
- **Payment preferences:** UPI was the most frequently used payment method, accounting for 6,276 orders.
- **Restaurant performance:** Punjabi Tadka recorded the highest number of orders among the restaurants analysed, with 634 orders.
- **Peak ordering hour:** 8 PM recorded the highest hourly order volume, with 1,886 orders.
- **Average order value:** The overall average order value was approximately ₹611.92.
- **Delivery performance:** The average delivery time was approximately 43.23 minutes.
- **Customer satisfaction:** The average customer rating was approximately 3.99.

### Correlation Insights

The correlation analysis indicated:

- Delivery time and distance had a strong positive correlation (0.84).
- Delivery fee and distance had a strong positive correlation (0.93).
- Delivery time and delivery fee showed a positive correlation (0.78).
- Delivery time and customer rating showed a negative correlation (-0.39).
- Order value and delivery time showed almost no linear correlation (0.001).

These are observed statistical associations and do not establish causation.

## Business Recommendations

Based on the observed patterns, the following opportunities could be considered:

1. **Delivery optimisation:** Review delivery routes and operational processes for longer-distance orders to improve delivery efficiency.
2. **Peak-hour planning:** Allocate delivery resources according to the higher order volumes observed during evening hours.
3. **Customer experience:** Investigate factors associated with lower customer ratings, particularly longer delivery times.
4. **Restaurant performance:** Study high-performing restaurants and food categories to understand customer preferences and identify opportunities for improved partnerships.
5. **City-level strategy:** Compare order volumes, average order values and delivery performance across cities to identify areas requiring operational attention.
6. **Time-based planning:** Use food category preferences across different time periods to support restaurant planning and demand management.

## Conclusion

This project demonstrates how exploratory data analysis can be used to understand food delivery operations and customer behaviour.

By examining order patterns, food preferences, restaurant performance, delivery efficiency and customer ratings, the analysis provides a structured view of the factors relevant to food delivery business performance.

The findings and recommendations can support further investigation into operational efficiency, customer experience and business growth.

## Project Information

**Project:** Swiggy Food Delivery Data Analysis  
**Domain:** Food Delivery & E-Commerce Analytics  
**Organisation:** Sapphire IQ  
**Tools:** Python, Pandas, NumPy, Matplotlib and Seaborn  
**Project Type:** Data Exploration and Exploratory Data Analysis (EDA)
