# SQL Retail Customer Sales Analysis
![image](https://github.com/hilxwang/SQL_Retail_Customer_Sales_Analysis/assets/96967687/a88a2d84-f980-4786-b761-0b1081a8d8f4)  

## Description
This project serves as an example of my responsibilities when I was a business analyst at a retail e-commerce company. Due to the confidentiality of data at my previous company, I cannot use the actual data. Therefore, I have utilized a publicly available dataset to demonstrate my SQL capabilities and business sense.

The main objective of this project is to solve ad hoc problems from customers and our business department using SQL queries. It involves common SQL statements such as SELECT, JOIN, WHERE, GROUP BY, etc., to extract and analyze data from different tables and categories. Additionally, some more complex requirements have been achieved using subqueries and Common Table Expressions (CTEs).

## Overview
This project showcases my responsibilities as a Business Analyst at a retail eCommerce company. Unfortunately, due to the confidentiality of data from my previous company, I cannot use their data. Therefore, I have found a similar project online to demonstrate my SQL capabilities and business sense.

The project focuses on solving ad hoc problems from customers and our business department using SQL queries. Commonly used SQL statements such as SELECT, JOIN, WHERE, GROUP BY, etc., are utilized to explore different tables and classifications. Additionally, more complex requirements are addressed using subqueries and common table expressions (CTEs).

## Data Source
The dataset used for this project can be found at the following link: [AdventureWorks Dataset](https://sqlzoo.net/wiki/AdventureWorks)

## Dataset Schema
The project utilizes a dataset with the following main tables:

1. Customer: Contains information about customers, including CustomerID, FirstName, LastName, CompanyName, and EmailAddress.

2. Address: Holds address details such as AddressID, AddressLine1, AddressLine2, City, StateProvince, CountyRegion, and PostalCode.

3. CustomerAddress: Contains information about customers' addresses, including CustomerID, AddressID, AddressType.

4. SalesOrderHeader: Contains sales order information, including SalesOrderID, OrderDate, CustomerID, ShipToAddressID, SubTotal, TaxAmt, and Freight.

5. SalesOrderDetail: Contains the details of each sales order, including SalesOrderDetailID, OrderQty, ProductID, UnitPrice, and UnitPriceDiscount.

6. Product: Contains product details like ProductID, Name, Color, ListPrice, Size, Weight, ProductModelID, and ProductCategoryID.

7. ProductModel: Holds information about different product models and their names.

8. ProductCategory: Provides product category information, including ProductCategoryID, ParentProductCategoryID, and Name.

9. ProductDescription: Contains descriptions of product models in different cultures.

10. ProductModelProductDescription: Associates product models with their corresponding descriptions.

## Usage
In this project, you can find various SQL queries that address different business requirements. The SQL scripts are organized based on their functionality, such as customer analysis, product sales, order details, and more. Each SQL query is commented to explain its purpose and expected results.

## Extra Insights
In addition to answering the main questions, this SQL Retail Customer Sales Analysis project includes some extra insights to showcase different aspects of the data and demonstrate SQL capabilities for more complex analyses.

Daily Active Customer Percentage: Shows the percentage of daily active customers by counting the number of unique customers who placed orders in a day.

Product Profit Margin: Calculates the profit margin for each product model by subtracting the standard cost from the total revenue and expressing it as a percentage.

Customer Lifetime Value (CLV) Analysis: Ranks customers by their total sales in descending order to analyze Customer Lifetime Value (CLV) for a single day.

Total Order Count per Customer: Lists customers with the highest order counts, indicating their purchasing frequency.

Geographic Distribution: Presents the distribution of customers based on their city, state/province, county/region, and postal code.

Customer Segmentation by Product Category: Segments customers based on the product categories they have purchased from, along with their order counts.

Product Unit Price Distribution: Presents the minimum, maximum, and average unit price for each product.

Top Salespersons by Revenue: Identifies the top salespersons based on the total sales revenue they generated.

Total Product Sold and Sales: Provides a summary of the total quantity sold and sales revenue for each product.

View the Details of Individual Sales Orders: Lists the details of individual sales orders, including customer information, product details, and total price.

Product Sales Revenue: Ranks products based on their sales revenue.

Average Order Quantity by Product Category: Calculates the average order quantity for each product category.

Total Quantity Sold: Shows the total quantity sold for each product category.

Number of Products in Different Cultures: Displays the number of products available in different cultures.

Order Detail Analysis: Provides insights into the average order quantity and average unit price for each product.

## Lessons Learned
As a business analyst working with SQL and large datasets, this project demonstrates my understanding of the following key aspects:

### SQL Performance Improvement: 
When dealing with large datasets, optimizing SQL queries is crucial to ensure faster execution and efficient resource utilization. Proper indexing, query optimization, and avoiding unnecessary joins are some of the techniques used to enhance SQL performance.

### Data Quality: 
Ensuring data quality is vital for meaningful analysis and decision-making. This project reflects my awareness of data cleanliness, accuracy, and consistency.

### Business Sense: 
Understanding the context and business requirements behind the ad hoc queries is essential to provide relevant insights. This project showcases my ability to analyze business logics and translate them into actionable SQL queries.

