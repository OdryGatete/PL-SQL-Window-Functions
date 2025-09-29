# STUDENT: Gatete Odry
# ID:28450
## DEPARTMENT: SOFTWARE Engineering
# PL-SQL-Window-Functions
## Course:  Database Development with PL/SQL
## Lecturer: Eric Maniraguha
Assignment on PL/SQL Window Functions 2025
   STEP 1
Business Context:
Ishingiro Supermarket has branches across all rwanda and it wants to understand its customer's behaviour and how their product are performing among their branches the sales and marketing team needs reliable information for sales and stock planning

Data challenge:

the company has recorded many transactions and therefore there are unable to see which products are selling most in all districts and they are unable to see if number of customers is increasing or not and without these information sales can not increase on higher level to meet the demand

Expected Outcome:

to get information of best selling products in districts ,getting total sales that happened in the whole month and all this data then will be used to target customers

STEP 2 
Find the Top 5 Products in Each Region:
I will use the RANK() window function to see which products are selling the most in each region.

Calculate Running Total of Monthly Sales:
I will use SUM() OVER() to add up monthly sales and show how the total grows month by month.

Check Month-to-Month Sales Change:
I will use LAG() to compare each month’s sales with the previous month and see the difference.

Group Customers into 4 Spending Levels:
I will use NTILE(4) to divide customers into four groups based on how much they spent.

Find 3-Month Moving Average of Sales:
I will use AVG() OVER() to calculate the average sales for every 3-month period.

STEP 3  
Customer Table 

The customers table stores information about all our customers.  
It includes a unique ID for each customer, their name, and the region they belong to.  
This table helps us track who is buying our products and where they are located.
![Customers Table](/images/CUSTOMER%20TABLE.jpg)

Product table
