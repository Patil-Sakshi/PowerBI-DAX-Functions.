# PowerBI-DAX-Functions.

All the DAX Query.


1)Count of orders.
--> Count of Orders = COUNT(Orders[Order ID])
   //calculating total orders from Orders table. <-- this is the comment.

Another Method to Count the Orders.
-->Count of Orders = COUNTROWS(Orders)
[COUNTROWS- Counts the number of rows in a table.]

Another Method to Count the Orders.
-->Unique Count of Orders = DISTINCTCOUNT(Order[Order ID])

