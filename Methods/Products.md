# How to view, create, update, delete a product
**View product/s**
- View all products
> Method: GET
> 
> URL: http://127.0.0.1:5000/products
> 
> Click Send to view all products.
> 

- View a product
> Method: GET
> 
> URL: http://127.0.0.1:5000/products/{id}
> 
> Click Send to view the product.
> 

**Create a product**
> Method: POST
> 
> URL: http://127.0.0.1:5000/products
> 
> Sample source code:
> 
> `{`
> 
> `  "name": "Mouse",`
> 
> `  "price": 500,`
> 
> `  "stock": 10`
> 
> `}`
> 
> Click Send to create new product.

**Update a product**
> Method: PUT
> 
> URL: http://127.0.0.1:5000/products/{id}
> 
> Sample source code:
> 
> `{`
> 
> `  "name": "Mouse",`
> 
> `  "price": 250,`
> 
> `  "stock": 5`
> 
> `}`
> 
> Click Send to update the product.

**Delete a product**
> Method: DELETE
> 
> URL: http://127.0.0.1:5000/products/{id}
> 
> Click Send to delete the product.
