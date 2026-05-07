# Test Cases

## Create User

### Preconditions
API is available.

### Steps
1. Send POST request to /user
2. Provide valid JSON body
3. Click Send

### Expected Result
- Status code is 200
- User is successfully created

---

## Find Pet By ID

### Preconditions
Pet exists in the system.

### Steps
1. Send GET request to /pet/{petId}

### Expected Result
- Status code is 200
- Correct pet information is returned

---

## Delete User

### Preconditions
User exists.

### Steps
1. Send DELETE request to /user/{username}

### Expected Result
- Status code is 200
- User is deleted successfully
