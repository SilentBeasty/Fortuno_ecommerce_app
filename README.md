# Description
This project is a Flask-based RESTful API developed for Activity 4 in IS 312. The application demonstrates how to create, read, update, and delete (CRUD) product data, as well as process customer orders using a database. It uses SQLite for data storage and supports API testing through tools like Postman.

# Frameworks and Libraries Used
- Flask – Web framework for building the API
- Flask-SQLAlchemy – ORM for database management
- Marshmallow – Data serialization and validation
- SQLite – Lightweight database

# How to Run the Application Locally
**Option 1:** Manual Setup (Recommended for Learning)
1. Open PyCharm.
2. Create a new Python project named Fortuno_ecommerce_app.
   - Make sure Flask is installed.
      - If not, open your terminal and install it using: `pip install flask`
   - Make sure required packages are installed.
      - `Open your terminal and install it using: pip install flask flask-sqlalchemy marshmallow`
3. Create a Python file named app.py.
4. Copy and paste the provided Flask code [app.py](https://github.com/SilentBeasty/Fortuno_ecommerce_app/blob/98e7aff4182d91cf8a40a3ee2ba4a59b47aa3b49/Fortuno_ecommerce_app/app.py) into app.py.
5. Run the program.

**Option 2:** Using ZIP File
1. Download the project ZIP file from: [Fortuno_ecommerce_app.zip](https://github.com/SilentBeasty/Fortuno_ecommerce_app/blob/8407dc5680ba02bc3cd34d9d26d29c24fd429269/Fortuno_ecommerce_app.zip)
2. Extract (uncompress) the ZIP file.
3. Place the extracted folder into your desired project directory.
4. Open Pycharm.
   - Make sure Flask is installed.
      - If not, open your terminal and install it using: `pip install flask`
   - Make sure required packages are installed.
      - Open your terminal and install it using: `pip install flask flask-sqlalchemy marshmallow`
5. Click the Main Menu.
6. Select Open.
7. Choose the extracted project folder.

# Application Testing Tool
Postman is used to send HTTP requests (GET, POST, PUT, DELETE) to test the API.

**How to Install Postman**
1. Go to the official [Postman website](https://www.postman.com/downloads/?fbclid=IwZXh0bgNhZW0CMTAAYnJpZBExT3E5RXJYRGNtMEdYWEZXVXNydGMGYXBwX2lkEDIyMjAzOTE3ODgyMDA4OTIAAR4jHY4-O90VI2vOCvINNlIP2kvbv24vywdxPUZGCgyEBpUmj3ATbyL6Pu6fMw_aem_QGr6RQilFRu18PxEbE7nyA).
2. Download and install the Postman application.
3. Open Postman after installation.
4. Login or Register an account.
   

**How to Use the API with Postman**
1. Start the Flask server. Once it’s running, open the Postman application.
2. Use the local server URL displayed in the terminal (commonly: http://127.0.0.1:5000/).
3. Append the desired endpoint to the URL:
   - For products: http://127.0.0.1:5000/products
   - For orders: http://127.0.0.1:5000/orders
5. Use Postman to view, create, update, or delete data:
   - [Product API Methods](https://github.com/SilentBeasty/Fortuno_ecommerce_app/blob/b73e74300b527915e859433e8b7695f8742406b8/Methods/Products.md)
   - [Order API Methods](https://github.com/SilentBeasty/Fortuno_ecommerce_app/blob/b73e74300b527915e859433e8b7695f8742406b8/Methods/Orders.md)
