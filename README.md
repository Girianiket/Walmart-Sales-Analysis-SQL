# Walmart-Sales- DATA-ANALYSIS-SQL

## OBJECTIVE
Analyzed Walmart’s sales data to identify high-performing branches and products, uncover sales trends, and understand customer behavior. The project aimed to explore key factors influencing sales performance across various branches and provide insights to enhance and optimize sales strategies

## DATA SUMMARY

The dataset for this project was sourced from the Kaggle Walmart Sales Forecasting Competition and includes sales records from three Walmart branches located in Mandalay, Yangon, and Naypyitaw. It comprises 1,000 rows and 17 columns containing detailed information on sales transactions.

| Column           | Description                               | Data Type       |
|------------------|-------------------------------------------|-----------------|
| invoice_id       | Invoice of the sales made                 | VARCHAR(30)     |
| branch           | Branch at which sales were made           | VARCHAR(5)      |
| city             | The location of the branch                | VARCHAR(30)     |
| customer_type    | The type of the customer                  | VARCHAR(30)     |
| gender           | Gender of the customer making purchase    | VARCHAR(10)     |
| product_line     | Product line of the product sold          | VARCHAR(100)    |
| unit_price       | The price of each product                 | DECIMAL(10,2)   |
| quantity         | The amount of the product sold            | INT             |
| VAT              | The amount of tax on the purchase         | FLOAT(6,4)      |
| total            | The total cost of the purchase            | DECIMAL(12,4)   |
| date             | The date on which the purchase was made   | DATETIME        |
| time             | The time at which the purchase was made   | TIME            |
| payment          | The total amount paid                     | DECIMAL(10,2)   |
| cogs             | Cost Of Goods Sold                        | DECIMAL(10,2)   |
| gross_margin_pct | Gross margin percentage

## DATA SET USED
- Data set used <a href = "https://github.com/Girianiket/Walmart-Sales-Analysis-SQL/blob/main/Walmart%20Sales%20Dataset.csv"> Click to download Data Set</a>

## SQL QUERY

- SQL Query <a href = "https://github.com/Girianiket/Walmart-Sales-Analysis-SQL/blob/main/SQL%20Queries.sql"> Click to see SQL Query</a>

## ANALYTICAL APPROACH
1. Product Analysis
Conducted a detailed analysis of the dataset to derive insights into various product lines, identify top-performing categories, and highlight areas where performance improvement is needed.

2. Sales Analysis
Analyzed sales trends across different products to evaluate the effectiveness of existing sales strategies and uncover opportunities for enhancing overall sales performance.

3. Customer Analysis
Focused on segmenting customers based on purchasing behavior, examining buying patterns, and assessing the profitability of each customer segment to support data-driven business decisions.


## PROCESS

1.Data Wrangling:
Cleaned and structured the dataset by checking for missing values and ensuring data integrity through database constraints like NOT NULL.

2.Feature Engineering:
Created new columns — time_of_day, day_name, and month_name — to analyze sales trends across different times, days, and months.

3.Exploratory Data Analysis (EDA):
Performed data exploration to uncover key patterns, correlations, and insights supporting the project’s main objectives.


## PROJECT INSIGHT

Yangon and Mandalay branches recorded the highest sales.


Food & Beverages and Health & Beauty were top-performing product lines.


Evening hours and weekends saw maximum sales activity.


Female and member customers contributed more to overall revenue.


E-wallet and cash were the most preferred payment methods.

## QUESTION

1. How many distinct cities and branches are included in the dataset?

2. Which product lines are performing the best in terms of total sales and revenue?

3. What is the most preferred payment method among customers?

4. Which month generated the highest revenue and recorded the highest COGS (Cost of Goods Sold)?

5. Which city contributed the most to overall revenue?

6. Which product line has the highest VAT (tax percentage)?

7. Which branch sold more products than the overall average sales?

8. Which customer type contributes the most to total revenue and VAT?

9. What is the gender distribution of customers across different branches?

10. Which time of day and day of the week receive the highest customer ratings?











