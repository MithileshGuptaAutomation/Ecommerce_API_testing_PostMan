# Ecommerce API Testing Project - Postman

## Overview
This project demonstrates API testing using Postman for an Ecommerce application.

The project covers:
- Authentication handling
- Bearer token usage
- Dynamic token extraction
- API validation
- Environment variables
- GET and POST requests

## Tech Stack
- Postman
- REST API
- JSON
- Bearer Token Authentication

## APIs Covered

### 1. Login API
POST `/auth/login`

Features:
- User authentication
- Token extraction from response
- Environment variable storage

---

### 2. Get User Profile API
GET `/auth/me`

Features:
- Bearer token authorization
- User profile validation

---

### 3. Get Products API
GET `/products`

Features:
- Product retrieval
- Dynamic product ID extraction
- Response validation

---

## Validations Implemented
- Status code validation
- Token validation
- Response body validation
- Dynamic data extraction

---

## How to Run
1. Import Collection JSON
2. Import Environment JSON
3. Select environment
4. Run APIs sequentially

---

## Author
Mithilesh Gupta
