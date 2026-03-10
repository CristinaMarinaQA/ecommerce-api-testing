
| Test ID | Endpoint | Expected | Actual | Status |
|--------|----------|----------|--------|--------|
| AS-01 | GET /products | 200 OK and list of products | 200 OK | PASS |
| AS-02 | GET /products/1 | Product details returned | Product returned | PASS |
| AS-03 | GET /products/1 | Price > 0 | Price valid | PASS |
| AS-04 | GET /products/1 | Category exists | Category present | PASS |
| AS-05 | GET /products/1 | Rating object exists | Rating present | PASS |
| AS-06 | GET /products/9999 | 404 Not Found | 200 OK | FAIL |
| AS-07 | POST /products | 201 Created | 201 Created | PASS |
| AS-08 | POST /products | Title matches request | Title correct | PASS |
| AS-09 | POST /products | Price matches request | Price correct | PASS |
