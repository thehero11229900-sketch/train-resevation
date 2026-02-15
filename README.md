#  Train Seat Reservation System

A web/mobile-based application that enables passengers to search, book, modify, and cancel train tickets efficiently.  
The system ensures secure seat allocation, safe payment processing, and automatic ticket generation with a unique **PNR number**.

---

##  Introduction

The **Train Seat Reservation System** is designed to provide a seamless digital ticket booking experience.  
It prevents double booking through concurrency control and ensures secure payment transactions.

---

##  Purpose

To provide a reliable, secure, and scalable platform for online train ticket booking while:

- Preventing seat duplication
- Ensuring encrypted payment processing
- Maintaining booking transparency and compliance

---

##  Scope

The system supports the following functionalities:

-  Passenger registration & authentication  
-  Train search & seat booking  
-  Payment processing  
-  Ticket generation & management  
-  Admin management of trains & schedules  

---

##  Functional Requirements

###  User Module

1. User registration/login via email or phone.
2. Search trains by source, destination, and date.
3. View seat availability with seat map (AC / Sleeper).
4. Temporarily reserve selected seats (15-minute hold).
5. Make payments via:
   - Credit/Debit Card
   - UPI
   - Wallet
6. Generate e-ticket with unique **PNR number**.
7. Modify or cancel booking based on refund rules.

---

###  Admin Module

1. Add / Update / Delete trains.
2. Manage schedules and seat allocation.
3. Monitor bookings and cancellations.

---

##  Non-Functional Requirements

-  System Availability: 99.5% uptime  
-  Concurrency Control: No double booking  
-  Security: Payment encryption using SSL/TLS  
-  Performance: Response time < 3 seconds for searches  
   Scalability: Supports 10,000+ concurrent users  

---

## Acceptance Criteria

| ID   | Description |
|------|------------|
| AC-1 | User can search Delhi → Mumbai trains for tomorrow |
| AC-2 | Available seats displayed by class |
| AC-3 | 2 seats can be held for 15 minutes |
| AC-4 | Successful payment generates PNR e-ticket |
| AC-5 | Cancellation within 24 hours → 50% refund |
| AC-6 | Same seat cannot be booked twice |

---

##  Compliance & Auditing

- Maintain booking logs for 5 years.
- Payment compliance with RBI guidelines.
- Regular audit of seat allocation system.





