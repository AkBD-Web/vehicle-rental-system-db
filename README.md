# Vehicle Rental System

## Overview

This project is a simple database design for a Vehicle Rental System. It manages users, vehicles, and bookings.

---

## Tables

### Users

This table stores user information such as name, email, password, phone number, and role (Admin or Customer).

### Vehicles

This table stores vehicle details like name, type (car, bike, truck), model, registration number, rental price, and status.

### Bookings

This table stores booking information such as which user booked which vehicle, start date, end date, status, and total cost.

---

## Relationships

- One user can have many bookings
- One vehicle can have many bookings
- Each booking is connected to one user and one vehicle

---

## SQL Queries

### 1. INNER JOIN

This query shows booking details with customer name and vehicle name.

### 2. NOT EXISTS

This query finds vehicles that have never been booked.

### 3. WHERE

This query finds available vehicles of a specific type (for example, car).

### 4. GROUP BY and HAVING

This query shows vehicles that have more than 2 bookings.

---

## Tools Used

- DrawSQL (for ERD design)
- Beekeeper Studio (for running queries)
- PostgreSQL (for database)

---

## Submission

- [ERD Link](https://drawsql.app/teams/ak666/diagrams/vehicle-rental-system)
- [Viva Video Link](https://drive.google.com/file/d/1gOaGfTmfty7xeJuvkUuMxRKvzEklbWTw/view)

## Conclusion

This project demonstrates basic database design, relationships, and SQL query skills for a real-world vehicle rental system.
