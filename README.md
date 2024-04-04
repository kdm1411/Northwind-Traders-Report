# Northwind-Traders-Report - A PowerBi Project.
![image](https://github.com/kdm1411/Northwind-Traders-Report/assets/150349346/5f82bd6f-f802-444c-b5a4-1986104775e6)


### Project Overview.
---

This data analysis project aims to provide important insight into Northwind Traders Sales Performance in the first half of 2015. By analyzing various aspects of Northwind data, we seek to identify trends, makes data driven decisions, make better operation decision and smarter decision in the second halh of 2015. Northwind Traders is a fictitious company that imports and exports food around the world.

### Data Source.
---

Northwind Traders Data: The dataset used for this analysis are 'categories.csv', 'customers.csv', 'employees.csv', 'order_details.csv', 'orders.csv', 'products.csv', shippers.csv' files containing detailed informarion on Northwind Traders between 2013 and 2015

### Tools.
---

- Microsft PowerBi - Data Cleaning, Data Analysis & Creating Reports

### Data Cleaning.
---

The database had minimum dirty data in all tables. Nulls only appeared in the ShippedDate column in the Orders table, accounting for unshipped orders.

### Data Modelling.
---

When I loaded the database onto Power BI, a snowflake model was generated. However, I established the correct relationships between the tables. To connect the tables, I used the primary key of each table and established the appropriate relationships , including inactive relationships. This was necessary because of better visualisation. 

<img width="867" alt="image" src="https://github.com/kdm1411/Northwind-Traders-Report/assets/150349346/515b1708-c0cb-477f-a9e6-a46e265ee4fa">

### Exploratory Data Analysis.
---

EDA involves exploring the Northwind Traders data to answer key questions, such as:

Since the database contains multiple tables, I had to ask several questions in order to analyze each of them to get important insight and suggest data driven solutions to grow the business even more in the second half of 2025. To make things easier, I organized my questions into five sub-headings.

Overviev;
1. What is the total Sales?
2. How many order have been processed?
3. How many products have been sold?
4. What is the sales trend over the first half of 2015?

Customer;
1. Who are the top 5 customers by net sales?
2. Which country has the most sales?

Product;
1. What are the top 5 selling products?
2. Which category has the most purchases?
3. How many products have been discontinued?

Customer;
1. Who are the top 5 customers by Total sales?
2. Which country has the most sales?

Shipping;
1. Who is the most active employee in terms of sales made?

### Data Analysis.
---

Based on the overview, the total sales for the first half of 2015 is  $469.81k

<img width="490" alt="image" src="https://github.com/kdm1411/Northwind-Traders-Report/assets/150349346/d29016b3-a825-4003-8ba6-2dc533c60fbd">

The total number of orders received was 270, with 691 products sold.
The most sold category is Beverages with sales of $122k. Categories like Dairy products and Meat & Poultry also follow suit showing that most customers ordered mostly beverages and edibles.

<img width="417" alt="image" src="https://github.com/kdm1411/Northwind-Traders-Report/assets/150349346/f21ae4d1-d777-43f0-84ae-4371a9b478c4">

USA top the country with the biggest purchase with $101k in the first half of 2015 follow by Germany and Austria also Boise and Graz top the city by $43k sales


<img width="412" alt="image" src="https://github.com/kdm1411/Northwind-Traders-Report/assets/150349346/a28536d2-8618-4908-8ab8-c27a1caae366">

So far, there are 81 customers from 21 different countries. The 5 top paying customers are Jose Pavaratti($43k), Roland Mandel(43k), Horst Kloss($41k), Mario Pontess($24k), Patricia McKenna($23k).

<img width="415" alt="image" src="https://github.com/kdm1411/Northwind-Traders-Report/assets/150349346/99d3b80d-67cf-4eb2-aa6f-08e0af323c6b">


In the first hald of 2105, there was a sharp increase in total sales in April of over $134k, almost 7x more than the lowest sales($19k) month which was in May.


<img width="409" alt="image" src="https://github.com/kdm1411/Northwind-Traders-Report/assets/150349346/90e8bba0-91ca-44ea-830e-3745fc04b42d">

The employee with the highest sales is Janet Leverling with $82k follow by Andrew Fuller with $80k






  
  






