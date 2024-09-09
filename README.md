# Python-Data-Analysis-Project-1
My First Data Analysis Project: Diwali_Sales_Analysis

Data Loading & Inspection:

Loaded the Diwali sales dataset using pandas and inspected its shape, columns, and basic info.
Identified and removed unnecessary columns ('Status', 'unnamed1') and checked for missing values.
Handling Missing Data:

Removed rows with missing values to ensure a clean dataset for analysis.
Data Type Conversion:

Converted the 'Amount' column to an integer type for accurate computations.
Renaming Columns:

Renamed 'Marital_Status' to 'Shadi' for better clarity (although not necessary for final code).
Descriptive Statistics:

Used describe() to get summary statistics on 'Age', 'Orders', and 'Amount' columns, providing insights into the central tendencies and distribution.
Gender-based Sales Analysis:

Analyzed sales amounts by gender using groupby() and visualized it with a seaborn bar plot.
Added data labels to improve the clarity of visualizations.
Age Group Analysis:

Grouped data by 'Age Group' and visualized total sales using seaborn.
Examined the contribution of each age group to total sales.
State-wise Orders & Sales:

Created state-wise visualizations for top 10 states by total orders and sales.
Generated bar plots to showcase states with the highest order and sales volumes.
Marital Status Analysis:

Explored the relationship between marital status, gender, and sales using a grouped bar plot.
Occupation-wise Analysis:

Visualized the distribution of customers by occupation to identify target customer profiles.
Product Category Analysis:

Analyzed product categories contributing the most to total sales and displayed results through a bar plot.
Top Product Sales:

Examined the top 10 products by number of orders and visualized them to highlight the best sellers.
Key Learnings:
Data Cleaning: Efficiently handled missing data and unnecessary columns.
Visualization: Mastered seaborn for creating clear, informative bar plots.
Data Analysis: Gained insights into customer behavior by gender, age group, and product categories.
Next Steps: I will continue refining my analysis and learning more about advanced techniques like correlation and predictive modeling.

