# SQL-Task7- Creating Views

## Objective:
To learn and apply SQL views for abstraction, reuse, and better query management.

##  Tables Used:
- `Customers (CustomerID, CustomerName, City)`
- `Orders (OrderID, OrderDate, CustomerID, Amount)`

## Views Created:

1. **CustomerOrders**  
   Shows order details along with customer name and city using LEFT JOIN.

2. **HighValueOrders**  
   Filters orders where amount > 200.

3. **ValidCustomerOrders (WITH CHECK OPTION)**  
   Only includes orders where `CustomerID IS NOT NULL`, and prevents inserting invalid data.

4. **TotalOrdersPerCustomer**  
   Aggregates total orders and order value per customer.

##  Key Concepts Applied:
- `CREATE VIEW`
- `WITH CHECK OPTION`
- Aggregation with `GROUP BY`
- `LEFT JOIN` for combining tables
- Reusability and abstraction in SQL logic

