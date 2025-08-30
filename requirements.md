# Backend Requirements

## 1. User Authentication
**Endpoints:**
- `POST /auth/register` - Create account
- `POST /auth/login` - User login  
- `POST /auth/logout` - User logout
- `POST /auth/refresh` - Refresh token

**Requirements:**
- JWT tokens with 24h expiry
- Password hashing (bcrypt)
- Email validation
- Role-based access (guest/host/admin)

## 2. Property Management
**Endpoints:**
- `POST /properties` - Create listing
- `GET /properties` - List all
- `GET /properties/:id` - Get details
- `PUT /properties/:id` - Update
- `DELETE /properties/:id` - Delete

**Requirements:**
- Image upload (max 5MB)
- Location validation
- Price validation (>0)
- Availability calendar

## 3. Booking System  
**Endpoints:**
- `POST /bookings` - Create booking
- `GET /bookings` - User bookings
- `GET /bookings/:id` - Booking details
- `PUT /bookings/:id/cancel` - Cancel booking

**Requirements:**
- Date conflict prevention
- Guest count validation
- Payment integration
- Status tracking (pending/confirmed/cancelled)

## 4. Performance
- Response time: <200ms
- Uptime: 99.9%
- Max file size: 5MB
- Concurrent users: 10,000
