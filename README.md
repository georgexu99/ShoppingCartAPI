 This Rest API was built on Spring and compiled with maven. To use this api, I ran it through localhost:8080 <-default port
you can use the following URLs:
     http://localhost:8080/Products
     http://localhost:8080/Products?available=true
     http://localhost:8080/Products/{id} (1-3 for the time being)
     http://localhost:8080/Purchase/{id}
     http://localhost:8080/makeCart/{id}
     http://localhost:8080/Cart/AddProduct/{cartId}/{prodId}
     http://localhost:8080//Cart/Purchase/{cartId}

