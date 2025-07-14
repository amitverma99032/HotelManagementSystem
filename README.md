# HotelManagementSystem
The Hotel Management System is a console-based Java application designed to handle hotel room booking, customer details, food ordering, billing, and checkout operations. It supports multiple room types and uses file serialization to store data persistently.

**Key Features:**
Room Booking:

4 types of rooms:

Luxury Double Room

Deluxe Double Room

Luxury Single Room

Deluxe Single Room


User can book available rooms with guest details (name, contact, gender).

Food Ordering:

Menu includes items like Sandwich, Pasta, Noodles, and Coke.

Guests can order food, which is linked to their room and added to the bill.

Billing & Checkout:

System generates a bill combining room rent and food charges.

On checkout, the room is deallocated and made available again.

Room Availability Check:

View the number of rooms available for each room type.

Room Features Display:

View room type specifications (AC/Non-AC, bed type, rent per day, etc.).

Persistent Storage:

Uses Java Serialization to save and load data from a backup file automatically.

   Technologies Used:
Java (Core)

Serialization (Object I/O)

Multithreading (for saving backup asynchronously)

Command-line Interface

