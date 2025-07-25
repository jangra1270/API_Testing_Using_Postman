# API Documentation

## 1. Login API
- **Method**: POST
- **Endpoint**: `/api/login`
- **Headers**: `Content-Type: application/json`
- **Body**:
```json
{
  "email": "user@example.com",
  "password": "123456"
}
```
- **Expected Result**: 200 OK, returns token

## 2. Get User Profile
- **Method**: GET
- **Endpoint**: `/api/user/profile`
- **Headers**: `Authorization: Bearer <token>`
- **Expected Result**: 200 OK, user details returned

## 3. Logout API
- **Method**: POST
- **Endpoint**: `/api/logout`
- **Headers**: `Authorization: Bearer <token>`
- **Expected Result**: 200 OK, user logged out successfully
