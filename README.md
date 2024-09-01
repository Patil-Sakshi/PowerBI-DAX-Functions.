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

2)Sum of Orders.
-->Sum of Orders = SUM(Orders[Qunatity])

3)Profit Cost
-->Profit Cost = SUM(Orders[Selling Price]) - SUM(Orders[Product Cost])

4)Total Profit
-->Total Profit = (SUM(Orders[Selling Price]) - SUM(Orders[Product Cost])) * SUM(Orders[Quantity])

5)New Column VS New Measure
New column- the data is static.
New Measure- the data is dynamic , means it will give the differnt value for all the rows.

