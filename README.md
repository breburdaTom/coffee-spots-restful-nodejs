### 1. GET /users
1. Id 
2. Name 
3. IsActive 
4. IsAdult 
5. Pocket

### 2. GET /users/{id}
1. Id 
2. Name 
3. IsActive 
4. IsAdult 
5. Pocket 
6. Orders 
   1. Id 
   2. ProductName 
   3. Amount 
   4. Price
 
 ### 3. GET /drink-menu
1. Id 
2. ProductName 
3. Price 
4. IsForAdult 

### POST /buy
- validation if user is 18 and older

1. UserId 
2. ProductId 
3. Price

### 5. GET /summary

1. /summary/all
- returns summary of all orders per product
  
   1. Product 
   2. Amount of orders
   3. UnitPrice 
   4. SummaryPrice

2. /summary/user
- returns summary of all orders per user
   1. UserId 
   2. ordered product 
   3. Price 
