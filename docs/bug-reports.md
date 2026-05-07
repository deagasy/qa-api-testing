# Bug Reports

## BUG-001

### Title
API returns incorrect status code for invalid pet ID

### Steps to Reproduce
1. Send GET request to /pet/invalid_id

### Actual Result
Status code: 500 Internal Server Error

### Expected Result
Status code: 400 Bad Request

---

## BUG-002

### Title
User login endpoint accepts empty password

### Steps to Reproduce
1. Send login request with empty password

### Actual Result
User is logged in successfully

### Expected Result
Validation error should be returned
