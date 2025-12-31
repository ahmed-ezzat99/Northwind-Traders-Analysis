# Data Overview

- Total Quantity: 51K
- Total Sales: $1.4M
- Total Customers: 91
- Total Products: 77
- Total Orders: 830
- Total Shippers: 3

## Key Tables
- Customers (CustomerID, CompanyName, City, Country)
- Orders (OrderID, CustomerID, EmployeeID, OrderDate, ShipVia, Freight, Quantity)
- Employees (EmployeeID, EmployeeName, City, Country)
- Products (ProductID, ProductName, CategoryID, UnitPrice)
- Shippers (ShipperID, CompanyName)
- Dates (Date, Year, Month, Quarter)

## Data Quality Notes
- Tables connected through primary and foreign keys in Power BI
- Measures calculated using DAX
- No critical missing data affecting analysis
