Maven-Market-Report
A Power BI report on the sales of the Maven market.
This report is composed of 7 CSV files and measured tables. This led to the data modeling section, with 2 facts tables and 5 lookup tables. 
The facts table the Transaction data table and the Return data table with the remaining table (Calendar table, Customer table, Store table, Product table, and Region table)
The foreign keys are connected to the primary keys on a many-to-one (*:1)  relationship with a single cross filter with each relationship. The measuring table is a stand-alone but also in the model.
The report consists of two dashboards, one showing topline performance and the other showing store performance. 
Following my analysis there is always a significant difference in the revenue and profit for each quarter, the return for each quarter also varies. At the end of the 4th Qtr and 
rolling into the 1st Qtr of the following year, revenue, profit, total transaction, and total returns increased significantly. 
The second dashboard, with the stores in the USA, has the largest sales with over 180k sales and over 4k returns, the stores in Mexico have over 72k sales and 1k returns, 
and Canada has over 16k and just 400 returns.
