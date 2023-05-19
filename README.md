# Stack Project

## Frame Work Used
Spring boot

## Project Flow
Post data from Postman using request POST and Url (http://localhost:8080/stock)</br>
Save the data in h2 database</br>
Get date from Wed service using Url (http:/localhost:8080/stock/type/{stocktype})</br>
Get date from wed service using Url (http:/localhost:8080/stock/abovePrice/price/{price}/lowerData/date/{date})</br>
Get data from wed service using Url (http:/localhost:8080/stock/cap/{capPercentage})</br>
Update data from Postman using request PUT and Url (http:/localhost:8080/stock/stock/type/id) save the data h2 database</br>

## Summary
1. created model for Stock and used enum class is StockType</br>
2. Made table in h2 database</br>
3. preformed CRUD operation on table Stock</br>
