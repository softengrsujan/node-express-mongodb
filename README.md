# Node.js Express & MongoDB: CRUD Rest APIs

## Project setup
```
npm update
```

### Run
```
node server.js
```
### Node.js MongoDB Rest CRUD API overview
```
Methods             Urls                Actions
GET             api/products               get all Products
GET             api/products/:id           get Product by id
POST            api/products               add new Product
PUT             api/products/:id           update Product by id
DELETE          api/products/:id           remove Product by id
DELETE          api/products               remove all Products
GET             api/products/published     find all published Products
GET             api/products?title=[samsung]    find all Products which title contains 'samsung'
```