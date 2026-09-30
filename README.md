Movie Theater Ticket Kiosk
--------------------------

This repository contains a simple software engineering exercise for a movie theater self-service ticket kiosk. The system shall allows customers to view movie and showtimes, choose availability of  seats, purchase tickets, and receive confirmation. The system must also prevent duplication of seats.

Tools and Libraries
-------------------

Python, Django, MongoDB, GitHub, Docker, Pytest.


Expanded description for Purchase Ticket
----------------------------------------

Primary Actor: Customer
Precondition: The customer has already selected a movie and showtime

1) The customer goes to the kiosks and checks available seats in their selected choice
2) The customer selects desired seats
3) The system checks availability and if available locks in selection for a period of time to avoid duplication
4) The customer selects desired payment method
5) The system processes payments and confirms order
6) The system generates tickets and shows purchase confirmation
7) The system refreshes seat availability for next customers availability 

Postcondition: The ticket is successfully purchased, the selected seat is reserved, and a confirmation is provided.
   
