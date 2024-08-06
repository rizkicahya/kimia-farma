# Introduction

As a Big Data Analytics Intern at Kimia Farma, my responsibilities will involve a series of challenges that require a deep understanding of data and analytical skills. One of my main projects will be to evaluate Kimia Farma's business performance from 2020 to 2023. Below are the tasks need to complete:

Task: Importing Dataset to BigQuery
In this project, I will importing the provided datasets into BigQuery:

kf_final_transaction.csv
kf_inventory.csv 
kf_kantor_cabang.csv 
kf_product.csv 
I need to import all four datasets to create tables in BigQuery.

In this project, I also required to create an analysis table based on the aggregation of the four tables that have been previously imported. The following columns are mandatory in the table:

transaction_id: Transaction ID code
date: Date of the transaction
branch_id: Kimia Farma branch ID code
branch_name: Kimia Farma branch name
city: City of the Kimia Farma branch
province: Province of the Kimia Farma branch
branch_rating: Customer rating for the Kimia Farma branch.
customer_name: Name of the customer who made the transaction.
product_id: Product code for the medication.
product_name: Name of the medication.
actual_price: Price of the medication.
discount_percentage: Discount percentage applied to the medication.
gross_profit_percentage: Percentage of profit expected from the medication, based on the following conditions:
Price <= Rp 50,000 -> profit 10%
Price > Rp 50,000 - 100,000 -> profit 15%
Price > Rp 100,000 - 300,000 -> profit 20%
Price > Rp 300,000 - 500,000 -> profit 25%
Price > Rp 500,000 -> profit 30%
net_sales: Price after the discount.
net_profit: Profit obtained by Kimia Farma.
transaction_rating: Customer rating for the transaction made.

## Next Challenge

In this project, I will create a performance analytics dashboard for Kimia Farma covering the business years 2020-2023. This dashboard will be developed in Google Looker Studio and will provide insights into various aspects of Kimia Farma's performance over the specified period.
