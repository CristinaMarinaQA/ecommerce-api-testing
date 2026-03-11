# API Bug Reports

This folder contains bug reports identified during the API testing of the Fake Store API.

## Bugs Included

BR-01 – GET /products/9999 returns 200 OK for a non-existing product instead of 404 Not Found.

BR-02 – POST /products allows creation of a product even when required fields (such as title) are missing.

## Bug Report Structure

Each bug report contains:

- Bug ID
- Title
- API Endpoint
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Environment

These bug reports were documented during manual API testing using Postman.
