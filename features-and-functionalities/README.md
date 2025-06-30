# 🛠️ Airbnb Clone – Backend Features & Functionalities

This document outlines the key backend modules and functionalities required for the Airbnb Clone project.

## 📦 Key Functional Modules

### 1. User Management
- Role-based registration (guest, host)
- Secure authentication with JWT
- OAuth login (Google, Facebook)
- Profile editing and preferences

### 2. Property Listings
- CRUD operations for hosts
- Upload property images
- Amenities, location, and pricing data

### 3. Search and Filters
- Search properties by location, price, guests, and amenities
- Paginated results

### 4. Booking System
- Guests can book properties for selected dates
- Prevent overlapping bookings
- Cancel or update bookings
- Track booking statuses

### 5. Payments
- Process guest payments securely via Stripe or PayPal
- Automatically pay out hosts
- Support for multiple currencies

### 6. Reviews & Ratings
- Guests rate properties and leave reviews
- Hosts can respond
- Prevent reviews unless booking completed

### 7. Notifications
- In-app and email alerts for key actions

### 8. Admin Dashboard
- Admin control over users, listings, bookings, and transactions

### 9. Technical Notes
- PostgreSQL, Redis, Django REST Framework
- REST APIs and GraphQL
- Secure file/image storage
- CI/CD with GitHub Actions

---

## 🖼️ Visual Diagram

Below is a system-level overview of all backend functionalities:

![Backend Functionalities Diagram](./backend-functionalities.png)

> Diagram created using [Draw.io](https://draw.io)
