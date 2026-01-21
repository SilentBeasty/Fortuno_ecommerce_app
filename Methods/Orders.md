# How to view, create, update, delete a order
**View all orders**
> Method: GET
> 
> URL: http://127.0.0.1:5000/orders
>  
> Click Send to view all orders.

**Create a order**
> Method: POST
> 
> URL: http://127.0.0.1:5000/orders
> 
> Sample source code:
> 
> `{`
> 
> `  "product_id": 1,`
> 
> `  "quantity": 1`
>
> `}`
> 
> Click Send to create new order. 

**Delete a order**
> Method: DELETE
> 
> URL: http://127.0.0.1:5000/orders/{id}
> 
> Click Send to delete the order.
