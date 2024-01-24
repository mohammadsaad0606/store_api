The Store API is a backend service that facilitates the management of store-related data, including product information, inventory tracking, and order processing. It provides five endpoints for different CRUD (Create, Read, Update, Delete) operations on products.

Endpoints
Get All Products
Method: GET
Description: Retrieve a list of all products available in the store.

Get Single Product
Method: GET
Description: Retrieve details of a specific product using its unique identifier.

Create Product
Method: POST
Description: Add a new product to the store's inventory.

Update Product
Method: PUT
Description: Update the details of a specific product using its unique identifier.

Delete Product
Method: DELETE
Description: Remove a product from the store's inventory based on its unique identifier.

Install dependencies:
npm install

Configure environment variables:

Create a .env file based on the provided .env.example file.
Set the required variables such as database connection details.


Running the API
npm start
The API will be accessible at http://localhost:3000 by default.

