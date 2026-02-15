# train-resevation
�1. Train Seat Reservation System
1. Introduction
The Train Seat Reservation System is a web/mobile-based application designed to allow users to
search, book, modify, and cancel train tickets efficiently. It ensures secure seat allocation,
payment processing, and ticket generation with a unique PNR number.
2. Purpose
To provide a reliable and scalable platform for passengers to book train tickets online while
preventing double booking and ensuring payment security.
3. Scope
The system supports:
 Passenger registration
 Train search and booking
 Payment processing
 Ticket management
 Admin management of trains and schedules
4. Functional Requirements
User Module
1. User registration/login via email or phone.
2. Search trains by source, destination, and date.
3. View seat availability with seat map (AC/Sleeper).
4. Temporarily reserve selected seats (15-minute hold).
5. Make payments via card, UPI, or wallet.
6. Generate e-ticket with unique PNR.
7. Modify or cancel booking with refund rules.
Admin Module
1. Add/update/delete trains.
2. Manage schedules and seat allocation.
3. Monitor bookings and cancellations.
5. Non-Functional Requirements
 System availability: 99.5% uptime.
 Seat booking concurrency control (no double booking).
 Payment encryption using SSL/TLS.
 Response time < 3 seconds for searches.
 Scalable for 10,000+ concurrent users.
6. Acceptance Criteria
 AC-1: User can search Delhi → Mumbai trains for tomorrow.
 AC-2: Available seats displayed by class.
 AC-3: 2 seats can be held for 15 minutes.
 AC-4: Successful payment generates PNR e-ticket.
 AC-5: Cancellation within 24h → 50% refund.
 AC-6: Same seat cannot be booked twice.
7. Compliance & Auditing
 Maintain booking logs for 5 years.
 Payment compliance with RBI guidelines.
 Regular audit of seat allocation system.
