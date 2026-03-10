**Bug ID:** BR-01  
**Title:** GET /products/9999 returns 200 instead of 404

**API Endpoint**
GET https://fakestoreapi.com/products/9999

**Steps to Reproduce**
1. Send GET request to /products/9999
2. Observe the API response

**Expected Result**
API should return 404 Not Found for non-existing product.

**Actual Result**
API returns 200 OK.

**Severity**
Medium

**Environment**
Fake Store API
