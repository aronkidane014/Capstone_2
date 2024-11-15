# Capstone_2

## Project Overview

This project demonstrates data cleaning and analysis skills using Python and Jupyter Notebook. It involves working with two main datasets: a customer list and transaction data. The project is split into two primary tasks:

1. **Customer List Cleanup**: Cleaning and standardizing customer data for consistency and usability.
2. **Transaction Data Analysis**: Analyzing transaction data to gain insights into sales trends, popular products, and top customers.

The cleaned and analyzed data enables business stakeholders to make data-driven decisions by providing clear insights into customer behavior and sales patterns.

## Files in This Project

- **CapStone_2.ipynb**: Jupyter Notebook containing the code for data cleaning, transformation, and analysis.
- **cleaned_customer_list.csv**: CSV file containing the cleaned customer list after applying data cleaning steps.
- **cleaned_transaction_data.csv**: CSV file containing the cleaned transaction data.
- **customer_list_updated.csv**: Original customer list file (before cleaning).
- **transaction_data.csv**: Original transaction data file (before cleaning).
-  **time_filtered_transaction_data.csv**: cvs file the time of the future removed.

## Data Cleaning Steps

### Customer List Cleanup

1. **Removed Extra Spaces**: Standardized column names by removing any extra spaces.
2. **Cleaned Non-Standard Characters**: Removed any special characters from the "name" column to ensure consistency.
3. **Formatted Phone Numbers**: Converted phone numbers to a consistent format (NNN-NNN-NNNN).
4. **Filled Missing Values**: Replaced any missing values in the "sms-opt-out" column with "N" for consistency.

### Transaction Data Cleanup

1. **Date Formatting**: Converted date columns to datetime format to facilitate time-based analysis.
2. **Duplicate Removal**: Identified and removed duplicate rows to ensure data integrity.
3. **Missing Values Check**: Checked for and handled missing values in essential columns.
4. **Saved Cleaned Data**: Exported the cleaned data into new CSV files for further analysis.

## Data Analysis and Insights

### Monthly Sales Trend

The monthly sales trend chart illustrates the fluctuation in total sales over a period from July 2023 to October 2024. Key observations include:

- **Seasonal Variations**: The chart shows visible peaks and dips in sales throughout the year, which may indicate seasonal demand patterns.
- **High Sales Periods**: Significant sales spikes are observed in specific months like April and October, possibly linked to holidays or promotions.
- **Low Sales Periods**: Dips in sales are noted around August and December, which may indicate lower demand or off-peak seasons.

### Top 5 Products by Revenue

The analysis of the top 5 products by revenue revealed the following insights:

- **Popular Products**: The most popular products in terms of revenue include items like *Thuringer Rostbratwurst* and *Cte de Blaye*.
- **Sales Distribution**: These products contribute significantly to total sales, showing strong customer preference or effective marketing.
- **Revenue Contribution**: Understanding which products generate the most revenue helps prioritize stock management and promotional efforts.

### Top 10 Customers by Spending

An analysis of the top 10 customers by spending provided valuable insights:

- **High-Spending Customers**: Customer IDs 27 and 1 lead in spending, highlighting key customers who contribute the most to sales.
- **Customer Loyalty**: The analysis of top spenders helps identify loyal customers who could be targeted for exclusive promotions or loyalty rewards.
- **Revenue Impact**: Knowing top-spending customers allows the business to create targeted marketing strategies, potentially enhancing customer retention and revenue.

### Peak Sales Product for Each Month

Analyzing the peak sales product for each month shows the following:

- **Product Popularity by Month**: Certain products, such as *Thuringer Rostbratwurst* and *Cte de Blaye*, dominate sales in specific months.
- **Demand Patterns**: Seasonal changes in product popularity can indicate shifting consumer preferences or the impact of marketing campaigns.
- **Inventory Management**: Understanding peak sales products by month can help optimize inventory and reduce stockouts.

## Conclusion

This project successfully cleansed and analyzed customer and transaction data, revealing crucial insights into customer spending habits, product popularity, and monthly sales trends. By identifying high-revenue products, top-spending customers, and seasonal sales patterns, this analysis equips stakeholders with actionable data to enhance marketing strategies, improve inventory management, and foster customer loyalty.



