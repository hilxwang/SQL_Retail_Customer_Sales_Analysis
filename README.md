# SQL_Retail_Customer_Sales_Analysis
Database Reference(https://sqlzoo.net/wiki/AdventureWorks)  
Customer(CustomerID, FirstName, MiddleName, LastName, CompanyName, EmailAddress)  
CustomerAddress(CustomerID, AddressID, AddressType)  
Address(AddressID, AddressLine1, AddressLine2, City, StateProvince, CountyRegion, PostalCode)  
SalesOrderHeader(SalesOrderID, RevisionNumber, OrderDate, CustomerID, BillToAddressID, ShipToAddressID, ShipMethod, SubTotal, TaxAmt, Freight)
SalesOrderDetail(SalesOrderID, SalesOrderDetailID, OrderQty, ProductID, UnitPrice, UnitPriceDiscount)
Product(ProductID, Name, Color, ListPrice, Size, Weight, ProductModelID, ProductCategoryID)
ProductModel(ProductModelID, Name)
ProductCategory(ProductCategoryID, ParentProductCategoryID, Name)
ProductModelProductDescription(ProductModelID, ProductDescriptionID, Culture)
ProductDescription(ProductDescriptionID, Description) 

![image](https://github.com/hilxwang/SQL_Retail_Customer_Sales_Analysis/assets/96967687/a88a2d84-f980-4786-b761-0b1081a8d8f4)

Lesson Learned
business, SQL performence, understand business logics(how many items), ad hoc analysis
data accurcy, data modeling 
