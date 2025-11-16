# Retail Sales Dataset Analysis
## Project Overview
This repository contains a data analysis project exploring a retail sales dataset with marketing spend information. The dataset includes 1,000 transactions from 2023, covering customer demographics (age, gender), transaction details (quantity, price per unit, total amount), product categories (beauty, clothing, electronics), and marketing spend. The analysis, performed using Python in a Jupyter notebook, provides insights into sales performance, customer behavior, and marketing efficiency.
The primary goals are:
- Understand sales trends and performance across product categories.
- Analyze customer demographics and their purchasing patterns.
- Evaluate the relationship between marketing spend and sales revenue.
- Visualize key metrics to uncover actionable insights.

  ## Dataset Description
  The dataset (retail_sales_dataset_with_marketing.xls) contains 1,000 rows and 10 columns:

- Transaction ID: Unique identifier for each sale.
- Date: Transaction date (mostly 2023, one in 2024).
- Customer ID: Unique customer identifier.
- Gender: Customer gender (male/female).
- Age: Customer age (18-64).
- Product Category: Item category (beauty, clothing, electronics).
- Quantity: Number of items purchased (1-4).
- Price per Unit: Price of each item ($25-$500).
- Total Amount: Total sale value ($25-$2,000).
- Marketing Spend: Marketing cost per transaction ($7.50-$220).

  ## Prerequisites
To run the analysis, ensure you have:

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Required Python libraries (pandas,matplotlib,seaborn)

  ## Key Insights
  #### Overall Transaction Metrics

   - The average transaction amount (Total Amount) is $456.00.
   - The maximum recorded transaction amount is $2,000.00.
   - The average quantity of items sold per transaction is approximately 2.51 units.
   - The dataset contains 1000 total transactions.

  #### Sales Performance by Product Category
  ##### Total Revenue Ranking:
  
   - Electronics generated the highest total revenue at $156,905.
   - Clothing was the second highest with total revenue of $155,580.
   - Beauty recorded the lowest total revenue at $143,515.
  ##### Transaction Volume:
  - Clothing has the highest number of transactions with 351.
  - Electronics is close behind with 342 transactions.
  - Beauty has the lowest transaction count with 307

  ### Temporal and Customer Trends
  - The peak week for overall sales revenue was 2023-05-21, with total revenue of $17,515.
  - May (Month 5) recorded the highest number of total customers (transactions) at 105.
  - Other months with high customer volume are October (96), August (94), and December (91).
  - In terms of weekly volume, the average units sold for electronics (~16.02) is slightly higher than for beauty (~14.55).
  - Female customers made a slightly higher number of transactions (510) than male customers (490).
  ### Marketing Spend and Correlation
  - There is a positive correlation between Quantity (units sold) and Marketing Spend, with a coefficient of approximately 0.456. This suggests that higher marketing expenditure tends to result in a higher volume of units sold.
  - The highest number of transactions that included a non-zero marketing spend were associated with Clothing (male) (177), followed by Clothing (female) (174), and Electronics (male) (172)
