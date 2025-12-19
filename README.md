# Bank-Customer-Churn-Report
Bank Customer Churn Report in powerbi
This is a Report about Customer churn in bank what are the reason for customer churning
This report help us to understand what are the metrix affecting our customer to churn more and how we can work on that to increase our customer

First i have transform the data with the help of power query like removing unwanted column(row number,surnames) which doesn't aling with the customer churn
i have change the values of isactivemember column 1 with Active and 0 with inactive ,hascreditcard column 1 with yes and 0 with No ,as it is more readable.

I have created dax for calculating the total customer, customer churn and churn rate 
also created the group for age like (young adult,adult,middle age,senior), group for bank balance (no balance,low balance and medium balance) and one group for tenure (long term,mid term,new customer) with the help of switch function.

I have added 3 cards,5 donut charts and 3 line and stacked column chart and one slicer for filtering the report by gender

This overall report show us that the churn rate is high in senior age group, low balance and new customer people
This give us a direction what we can do next to retain the new Customer.

Here is the snapshot of the report
https://github.com/SaikeerthiBannur/Bank-Customer-Churn-Report/blob/main/Bank%20Customer%20Churn%20Analysis.png




