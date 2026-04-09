# Superstore Sales Analysis - Complete Portfolio Project

## Project Overview
Comprehensive analysis of Superstore sales data to identify profit drivers, discount impacts, and customer insights. Used Python (Pandas, NumPy, Matplotlib, Seaborn) in Jupyter Notebook.

## Key Business Questions Answered

### Profitability Analysis
1. **Which category is most profitable?** - Technology leads, Furniture lags
2. **Which sub-category is losing money?** - Tables and Bookcases show negative profit
3. **Which month has highest profit?** - December 2016 peak at $17,885 profit

### Regional & Customer Insights
4. **Which region has highest average discount?** - South region leads in discounting
5. **Top 5 customers by lifetime profit** - Ranked by total profit contribution
6. **Profit by Region & Category** - Cross-analysis showing best combinations

### Sales Performance
7. **Sales by Segment & Year** - Consumer segment drives most sales
8. **Monthly profit trend by Region** - Pivot table + resample analysis

### Advanced Analytics
9. **Rolling 3-month average profit** - Smoothing trends for better forecasting
10. **Cumulative profit by region** - Tracking regional performance over time
11. **Rank customers within each region** - Dense ranking using lambda functions

### Discount & Profit Relationship
12. **Products with high discount & low profit** - Identified discount-sensitive items
13. **Correlation between discount and profit** - Scatter plot showing negative correlation
14. **Outlier identification** - Found 5 highest profit and 5 biggest loss products

## Key Findings

### The Profit Drop Discovery
- **December 2016**: $96,999 sales, $17,885 profit (352 units)
- **November 2017**: $118,448 sales, $9,690 profit (459 units)
- **Sales up 22%, Quantity up 30%, but Profit DOWN 46%!**

### Root Cause
Higher discounts in November 2017 across multiple sub-categories caused profit erosion despite higher sales volume.

### Recommendations
1. Cap discounts at 15% for low-margin categories
2. Review discount strategy for Tables and Bookcases (negative profit)
3. Focus marketing on Technology category (highest margin)
4. Investigate South region's high discount usage

## Skills Demonstrated

### Data Manipulation
- Data cleaning & type conversion (datetime, handling missing values)
- Groupby, agg, pivot_table operations
- Multi-index management and unstacking

### Time Series Analysis
- Resampling (monthly, yearly aggregation)
- Rolling window calculations (3-month average)
- Cumulative sums for regional tracking

### Statistical Analysis
- Outlier detection (2 standard deviation method)
- Correlation analysis (scatter plot visualization)
- Percentage change calculations

### Advanced Pandas
- Lambda functions for ranking
- Join operations for period comparison
- np.select for categorical bucketing

### Visualization
- Matplotlib scatter plots
- Correlation visualizations

## Tools Used
- **Python 3.x**
- **Pandas** (data manipulation)
- **NumPy** (numerical operations)
- **Matplotlib & Seaborn** (visualizations)
- **Jupyter Notebook** (development environment)

## Files in Repository
- `Superstore_Analysis.ipynb` - Complete Jupyter notebook with all code and outputs

## How to View
1. Clone this repository
2. Open `Superstore_Analysis.ipynb` in Jupyter Notebook
3. Run cells sequentially to see all analysis

## Dataset Source
Superstore Sales Dataset (2015) - Retail transaction data including sales, profit, discounts, customer segments, and regional information.

## Author
Kashan - Data Analyst Portfolio Project

## Project Status
Completed - All 14+ business questions answered with actionable recommendations
