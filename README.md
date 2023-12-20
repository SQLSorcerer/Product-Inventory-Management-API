# Product-Inventory-Management-API

This is a AWS Lambda function for managing a product inventory using Amazon DynamoDB. The service supports basic CRUD operations (Create, Read, Update, Delete) for products.

## Prerequisites
- AWS Lambda
- Amazon DynamoDB
- Python 3.8 or later

## Setup
1. Create an Amazon DynamoDB table with the name 'product-inventory'.
2. Deploy this Lambda function with the required permissions to access the DynamoDB table.

## Usage

### Endpoints

#### 1. Health Check
- **Path:** `/health`
- **Method:** `GET`
- **Description:** Check the health of the service.

#### 2. Get Product
- **Path:** `/product`
- **Method:** `GET`
- **Description:** Retrieve product details by providing the product ID as a query parameter.
- **Example:** `/product?productId=123`

#### 3. Get All Products
- **Path:** `/products`
- **Method:** `GET`
- **Description:** Retrieve details of all products.

#### 4. Save Product
- **Path:** `/product`
- **Method:** `POST`
- **Description:** Save a new product by providing the product details in the request body.

#### 5. Update Product
- **Path:** `/product`
- **Method:** `PATCH`
- **Description:** Update a product's information by providing the product ID, update key, and update value in the request body.

#### 6. Delete Product
- **Path:** `/product`
- **Method:** `DELETE`
- **Description:** Delete a product by providing the product ID in the request body.


## Contributing
Feel free to contribute by opening issues or creating pull requests. Your feedback and contributions are highly appreciated!
