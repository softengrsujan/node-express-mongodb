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
GET             api/products               get all Tutorials
GET             api/products/:id           get Tutorial by id
POST            api/products               add new Tutorial
PUT             api/products/:id           update Tutorial by id
DELETE          api/products/:id           remove Tutorial by id
DELETE          api/products               remove all Tutorials
GET             api/products/published     find all published Tutorials
GET             api/products?title=[kw]    find all Tutorials which title contains 'kw'
```