# API Test Scenarios

## GET Requests

AS-01 – Verify GET /products returns list of products
Expected result: 200 OK and list of products

AS-02 – Verify GET /products/1 returns product details  
Expected result: 200 OK and product object is returned

AS-03 – Verify product price is greater than 0  
Expected result: Price value > 0

AS-04 – Verify product category exists  
Expected result: Category field is present in response

AS-05 – Verify product rating exists  
Expected result: Rating object with rate and count is returned

AS-06 – Verify GET /products/9999 returns error for non-existing product  
Expected result: 404 Not Found

## POST Requests

AS-07 – Verify POST /products creates new product  
Expected result: 201 Created and product is created with new ID

AS-10 – Verify POST /products fails when required fields are missing  
Expected result: 400 Bad Request

AS-08 – Verify created product contains correct title  
Expected result: Title matches the request data

AS-09 – Verify created product contains correct price  
Expected result: Price matches the request data

## PUT Requests

AS-11 – Verify PUT /products/1 updates product successfully  
Expected result: 200 OK and product is updated

AS-12 – Verify updated product contains correct title  
Expected result: Title matches the updated value

AS-13 – Verify updated product contains correct price  
Expected result: Price matches the updated value

## DELETE Requests

AS-14 – Verify DELETE /products/1 deletes product successfully  
Expected result: 200 OK and deleted product returned

AS-15 – Verify deleted product ID is correct  
Expected result: Returned product ID matches deleted product
