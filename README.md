# Sales-insights-data-analysis

In this project I’ve simulated a business problem resolution to a hardware company in India.

# AtliQ Hardware
- Is a company which supplies computer hardware and peripherals to many clients across India;
- The company has a head office in Dehli and regional offices throughout India.

The sales director is facing a lot of challenges such as:
The marketing is growing dynamically and then he’s struggling in terms of tracking the sales, needing more accurate insights about the company sales, and then take the necessary decisions.

I used SQL queries in MySQL Workbench to take a look into the data and Tableau for ETL and visualizations to create the insights.

After a quick data exploration in MySQL, here are some initial findings:

The database contains 5 tables: customers, date, markets, products, and transactions;
There are 17 markets, 279 products, and 38 customers;
The observation period is from january 2018 to june 2020;
The total revenue in 2020 was $ 142,23 Mi, 42% less than 2019, which was $ 336,45 Mi;
Most of the transactions data are in INR currency, but we have 4 records in U$ currency.
And we got Paris and New York on the “sales markets” table. We’re going to deal with it in the ETL process.

The dashboard shows all the main information about the company sales, such as Revenue, Sales Quantity, Revenue and Sales by Market, Revenue Trend, Top 5 Customers and Top 5 Products.
It can be filtered by YEAR and MONTH inside the observation period, so the sales director can have a deeper and quick view of the sales to support his decision making process.
