### 1. GET /users
a. Id 
b. Name 
c. IsActive 
d. IsAdult 
e. Pocket

### 2. GET /users/{id}
a. Id 
b. Name 
c. IsActive 
d. IsAdult 
e. Pocket 
f. Orders 
 i. I 
 ii. ProductName 
 iii. Amount 
 iv. Price
 
 ### 3. GET /drink-menu
a. Id 
b. ProductName 
c. Price 
d. IsForAdult 

### POST /buy
- validation if user is 18 and older
a. UserId 
b. ProductId 
c. Price

### 5. GET /summary

a. /summary/all 
returns sum of orders per product
  i. Product 
  ii. Amount of orders
  iii. UnitPrice 
  iv. SummaryPrice

b. /summary/user
Vraci vsechny objednavky daneho uzivatele pro vsechny uzivatele: 
  i. UserId 
  ii. ordered product 
  iii. Price 