# SQL POJECT: CUSTOMER ORDER FEBRUARY 2022 DATABASE (QualityCenter_Demo_db)

## Description
This project demonstrates SQL queries on a small sample database for a retail scenario.  
It is built in the `QualityCenter_Demo_db` database and includes tables for customers, products, and customer orders for February 2022.  
The project shows SQL query design, table joins, and how to extract meaningful data.

## Database Tables

### Customers
- Stores information about customers  
- Columns: CustomerID, Customer Name, Address, City

### Products
- Stores product information  
- Columns: ProductID, ProductName, Price

### ORDERFEB2022
- Stores customer orders for February 2022  
- Columns: OrderID, ProductName, Quantity, CustomerID
---

## Queries

1. `customers.sql`  
   - Retrieves all customers from the `Customers` table  

2. `orders.sql`  
   - Retrieves all orders from the `ORDERFEB2022` table  

3. `customerXorder_join.sql`  
   - Joins `ORDERFEB2022` with `Customers` and `Products`  
   - Shows detailed information about which customer ordered which product, quantity, and order date  

> **Note:** All queries assume the database in use is `QualityCenter_Demo_db` (`USE QualityCenter_Demo_db;` is included at the top of each SQL file).

---

## Results
Query outputs are saved as CSV files in the `results/` folder:  

- `customers.csv`  
- `orders.csv`  
- `customerXorder_join.csv`  

These results match the output of the corresponding SQL queries.

---

## How to Use
1. Open SSMS (or another SQL client).  
2. Make sure the database `QualityCenter_Demo_db` exists.  
3. Open the `.sql` files from the `queries/` folder.  
4. Run the queries to see the outputs.  
5. Compare with the CSV results in the `results/` folder for verification. 