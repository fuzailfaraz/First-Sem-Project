Seating Arrangement in Stadiums

Overview: This C++ application serves as a Stadium Seating Management System, allowing users to reserve seats, view seating charts, and access booking details. It divides seats into VIP, Regular, and Economy categories, each with a limited number of available spots. Users can book seats by providing their personal information, check the availability of seats, and retrieve information on specific bookings.

Key Features

Seat Reservation System:
Users can choose from three seat categories: VIP, Regular, and Economy. If a seat is free, the system stores the user’s personal details along with the booking.

Seating Layout Display:
The program shows the status of all seats across the three categories (either [Available] or [Reserved]). Seats are presented in rows of five to make it easier to read and view.

Seat Information Lookup:
Users can input a seat’s index number to retrieve details about the ticket holder (including their name, age, UID, and family status).

Menu-Based Navigation:
The system operates with a menu that offers options to book a seat, check seat arrangements, view specific seat details, or exit the application.

File Structure:
Currently, this is a single-file C++ program, but in a larger project, it could be split across multiple files for better structure and maintenance. Here’s how it might look:

📂 StadiumSeatingManagement/
│── 📄 main.cpp → (Contains core logic and functions)
│── 📄 TicketHolder.h → (Header file defining the TicketHolder structure)
│── 📄 BookingSystem.cpp → (Contains functions for booking and viewing details)
│── 📄 DisplaySystem.cpp → (Handles the display of seating arrangements)

Though everything is currently in main.cpp, splitting it into multiple files would enhance organization and ease of future development.
