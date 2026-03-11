# API Testing Project – E-commerce API

This project demonstrates API testing using Postman for a sample e-commerce API.

API tested: https://fakestoreapi.com

## Tools Used

- Postman
- GitHub
- REST API
- Manual API Testing

## API Endpoints Tested

GET /products  
GET /products/{id}  
POST /products  
PUT /products/{id}  
DELETE /products/{id}

## Test Coverage

The project includes:

- API Test Plan
- API Test Scenarios
- Postman Test Collections
- Test Execution Report
- Bug Reports

## Test Types Performed

- Positive API Testing
- Negative API Testing
- Data Validation
- Status Code Validation
- Response Body Validation

## Project Structure

01_API_Test_Plan  
02_API_Scenarios  
03_Postman_Collections  
04_Test_Execution_Report  
05_API_Bug_Reports

## Sample Bug Found

Example bug discovered during testing:

GET /products/9999 returns **200 OK** instead of **404 Not Found** for a non-existing product.

## Author

Manual QA Portfolio Project
