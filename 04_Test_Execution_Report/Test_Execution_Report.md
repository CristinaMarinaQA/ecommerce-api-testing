
| Test ID | Endpoint | Expected | Actual | Status |
|-------|-------|-------|-------|-------|
| AS-01 | GET /products | 200 | 200 | Pass |
| AS-02 | GET /products/1 | Verify API returns single product | PASS |
| AS-03 | GET /products/1 | Verify product price is greater than 0 | PASS |
| AS-04 | GET /products/1 | Verify product category exists | PASS |
| AS-05 | GET /products/1 | Verify product rating exists | PASS |
| AS-06 | GET /products/9999 | Verify API returns error for non-existing product | FAIL |
