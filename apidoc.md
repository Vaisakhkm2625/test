
# API ENDPOINTS

## users

### Single of user

- GET       /users/{id}     get a user by id
- GET       /users/me       get current logged in user
- POST      /users          create new user 
- PUT       /users/{id}     updates a user by id
- DELETE    /users/{id}     deletes a user by id

- GET       /users/{id}/products/    get list of products of that user
- GET       /users/{id}/products/    get list of products of that user


### Collection of *users*

- GET       /users      collection of all users
    - filter -> /users?page=2&limit=50

## products

- POST      /products      create new product
- GET       /products      collection of all products
- GET       /products/{id} get a products by id
- PUT       /products/{id} updates a product by id
- DELETE    /products/{id} deletes a product by id

/products?page=2&limit=50


