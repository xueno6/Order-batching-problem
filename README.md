# Order-batch

Order batch problem (OBP) is to consider a minimum-route way to partition a set of orders. 
Each order contains one or more items that have fixed locations in a warehouse. The item-picker 
needs to pick each item in an order with a path going through some racks. Due to the capacity of 
the item-picker, the orders must be separated into bathes, which usually contain 10-20 orders separately. 
The problem is to find the best scheme that minimizes the sum of paths of each bathes picking route.

This project focuses on an OBP problem with an extensive large number of orders (800-1200), which makes the exact approach unpractical.
The project utilized an approximation model to handle this issue. The results outperform existing algorithms.
