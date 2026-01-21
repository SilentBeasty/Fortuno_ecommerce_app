# Description
This project is a Flask-based RESTful API developed for Activity 4 in IS 312. The application demonstrates how to create, read, update, and delete (CRUD) product data, as well as process customer orders using a database. It uses SQLite for data storage and supports API testing through tools like Postman.

# Frameworks and Libraries Used
- Flask – Web framework for building the API
- Flask-SQLAlchemy – ORM for database management
- Marshmallow – Data serialization and validation
- SQLite – Lightweight database

# How to Run the Application Locally
1. Open PyCharm.
2. Create a new Python project named Fortuno_ecommerce_app.
3. Make sure Flask is installed.
   - If not, open your terminal and install it using: pip install flask
5. Make sure required packages are installed.
   - Open your terminal and install it using: pip install flask flask-sqlalchemy marshmallow
6. Create a Python file named app.py.
7. Copy and paste the provided Flask code into app.py.
8. Run the program.

# Application Testing Tool
Postman is used to send HTTP requests (GET, POST, PUT, DELETE) to test the API.


**How to Install Postman**
1. Go to the official Postman website.
2. Download and install the Postman application.
3. Open Postman after installation.
4. Login or Register an account.


**How to Use the API with Postman**
1. Once the server starts, open a web browser or API testing tool and use the local server URL shown in the terminal (commonly): http://127.0.0.1:5000/
2. Then add "products" at the end of the link: http://127.0.0.1:5000/products


**View product/s**
- View all products
> Method: GET
> URL: http://127.0.0.1:5000/products
> Click Send to view all products.


- View a product
> Method: GET
> URL: http://127.0.0.1:5000/products/{id}
> Click Send to view the product.


**Create a product**
> Method: POST
> URL: http://127.0.0.1:5000/products
> Sample source code:
> `Sample Source Code:
> {
>   "name": "Mouse",
>   "price": 500,
>   "stock": 10
> }`
> Click Send to create new product.



