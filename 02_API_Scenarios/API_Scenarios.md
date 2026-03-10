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

## PUT Requests

AS-07 – Verify POST /products creates new product  
Expected result: 200 OK and product is created with new ID

AS-08 – Verify created product contains correct title  
Expected result: Title matches the request data

AS-09 – Verify created product contains correct price  
Expected result: Price matches the request data
