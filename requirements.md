# 📘 Technical & Functional Requirements – Airbnb Clone Backend

This document outlines the **technical** and **functional** specifications for core backend features of the Airbnb Clone project. Each section includes expected endpoints, inputs/outputs, validation rules, and performance criteria.

---

## 🔐 1. User Authentication

### 🧩 Functional Requirements
- Users must be able to register as guests or hosts.
- Users must log in using email and password.
- JWT-based session authentication is required.
- Optional: OAuth support (Google, Facebook) for third-party login.

### 📡 API Endpoints
| Method | Endpoint       | Description                 |
|--------|----------------|-----------------------------|
| POST   | /api/auth/register | Register a new user        |
| POST   | /api/auth/login    | Log in and return JWT token |
| GET    | /api/users/me      | Retrieve user profile      |

### 📥 Input Specification
#### POST `/api/auth/register`
```json
{
  "first_name": "Jane",
  "last_name": "Doe",
  "email": "jane@example.com",
  "password": "SecurePass123",
  "role": "guest"
}
