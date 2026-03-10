# Bug Report

**Bug ID:** BR-02  
**Title:** POST /products allows creation of product without required title field

**API Endpoint**
POST https://fakestoreapi.com/products

**Steps to Reproduce**
1. Send POST request to /products
2. Body contains only price field
3. Observe API response

**Expected Result**
API should return 400 Bad Request when required field "title" is missing.

**Actual Result**
API returns 201 Created and product is created.

**Severity**
Medium

**Environment**
Fake Store API
