# SKY-GEN-TASK-3 
Superstore Sales Exploratory Data Analysis (EDA)
SKY GEN— Data Science Internship | Task 03

A Python-based exploratory data analysis project that investigates Superstore sales data to uncover patterns in sales, profit, product categories, customer segments, regions, discounts, and shipping time.
Table of Contents
- Project Overview
- Objectives
- Dataset
- Tools and Libraries
- Key Analyses
- Repository Structure
- Getting Started
- Reported Metrics
- Data Quality Notes
- Recommendations
- Conclusion
Project Overview
Exploratory Data Analysis (EDA) is used to understand a dataset before drawing conclusions or building models. In this project, Python libraries are used to inspect and clean the Superstore data, calculate summary statistics, explore relationships, and create visualizations that can support business decisions.
Objectives
- Understand the dataset structure, columns, and data types.
- Detect missing values and duplicate records.
- Prepare date and numeric fields for analysis.
- Summarize sales, profit, quantity, discounts, orders, and customers when the corresponding source columns are available.
- Compare performance across categories, sub-categories, regions, states, customer segments, and products.
- Examine monthly sales patterns and shipping duration.
- Visualize numerical distributions, relationships, and potential outliers.
- Translate the verified results into business insights and recommendations.
Dataset
The analysis uses a Superstore CSV file, expected to be named:
Depending on the dataset version, columns may include:
- Order information: Order ID, Order Date, Ship Date, Ship Mode
- Customer information: Customer ID, Customer Name, Segment
- Location: Country, City, State, Postal Code, Region
- Product information: Product ID, Category, Sub-Category, Product Name
- Metrics: Sales, Quantity, Discount, Profit
Dataset note: Superstore datasets can vary by source and version. Analyses involving Profit, Quantity, or Discount should only be run when those columns contain valid values from the original data. Do not create random or guessed values to fill missing business metrics.
Tools and Libraries
- Python — analysis and scripting
- Pandas — loading, cleaning, grouping, and summarizing data
- NumPy — numerical operations
- Matplotlib — charts and visualizations
- Seaborn — statistical plots and correlation heatmaps
- Jupyter Notebook — documenting and running the analysis
Key Analyses
The notebook may include the following analyses, depending on which columns are available:
1. Dataset preview, dimensions, data types, and descriptive statistics
2. Missing-value and duplicate checks
3. Sales distribution histogram with KDE curve
4. Monthly sales trends and area chart by category
5. Sales and profit by category and sub-category
6. Sales and profit by region and state
7. Sales by customer segment and shipping mode
8. Top customers and products by sales
9. Products with negative total profit
10. Quantity and discount analysis
11. Shipping duration calculated from order and ship dates
12. Correlation heatmap and pairplot for numerical variables
13. Violin plots and boxplots to examine distributions and potential outliers
Repository Structure
