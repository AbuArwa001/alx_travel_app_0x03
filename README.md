# Travel App API Documentation

## Overview

This is the API documentation for the Travel App, which allows users to book properties, make payments, and manage their bookings.

## Endpoints

### Properties

- `GET /api/properties/`: List all properties
- `POST /api/properties/`: Create a new property
- `GET /api/properties/{id}/`: Retrieve a specific property
- `PUT /api/properties/{id}/`: Update a specific property
- `DELETE /api/properties/{id}/`: Delete a specific property

### Bookings

- `GET /api/bookings/`: List all bookings
- `POST /api/bookings/`: Create a new booking
- `GET /api/bookings/{id}/`: Retrieve a specific booking
- `PUT /api/bookings/{id}/`: Update a specific booking
- `DELETE /api/bookings/{id}/`: Delete a specific booking

### Payments

- `POST /api/payments/initiate/`: Initiate a payment
- `POST /api/payments/verify/`: Verify a payment
- `POST /api/payments/webhook/`: Handle payment webhook notifications

## Tasks

### Email Notifications

- `send_booking_confirmation_email`: Send a booking confirmation email to the user
- `send_payment_confirmation_email`: Send a payment confirmation email to the 