# Week-02-assignment
Project Title: Retail Insights Engine

Overview: 
You have been contracted by a mid-size retail business that has been collecting sales and inventory data over the last couple of years. They want to utilize this data to gain insights into their business.
Your task is to build a Retail Insights Engine that will take in their historical data, process it, analyze it, and provide actionable insights.

Data pre-processing :

The original dataset consists of 110813 rows, 6 columns : 'BillNo', 'Itemname', 'Quantity', 'Date', 'Price', 'CustomerID'.

Negative quantity means returned items and negative price means adjusted values. They need to be dropped.

Itemname has 336 and CustomerID  has 28473 missing values. 

Missing Itemname is filled as 'Unknown_item' and missing customerID is filled as '99999' for easy identification.

Few itemnames start with 'A' , those are identified and set right.

The quantities like Year, Month, Day, Hour, day_of_week are extracted from date for further analysis.

Following Business Analysis questions are answered :

Which product are the top performers? Which products are lagging?
The business has a hunch that certain products sell better at specific times of the year or maybe even days of the week. Using the data, validate this hunch.
Are there products that were once best-sellers but have seen a decrease in sales recently?
Identify the most common products that are bought together. Can you find any product pairs or combinations?
Which are the top 10 most frequent product baskets?
How does basket size vary with the day of the week or time of the month?
Identify different baskets of goods sold, which are the top 10 baskets?
Are there any loyal customers? Identify customers who make frequent purchases.
Can you segment customers based on their total spend?
How often do customers return to make another purchase?
