# LakbayPH

## Introduction
LakbayPH is a specialized web-based Multi-Carrier Aggregator designed specifically for the Philippine provincial transport landscape. It serves as a centralized digital platform connecting commuters with provincial transport providers, covering major hubs across Luzon, Visayas, and Mindanao. Developed for PH-TRANSIT CONNECT INC., this system aims to transform the traditional "chance passenger" model into a modern, data-driven experience. 

## Key Features
* Aggregates schedules and routes from various partner bus lines, such as Victory Liner and Ceres.
* Provides 24/7 access to seat inventories to eliminate physical queuing.
* Integrates secure cashless payment gateways like GCash, Maya, and the Philippine national QR code standard, QRPH.
* Generates unique QR-coded e-tickets for successful transactions and terminal check-ins.
* Instantly updates seat availability across the network to prevent overbooking, utilizing temporary holds for "Pending" seats.
* Sends automated trip reminders via email.

## User Roles
* **User:** Commuters and tourists who search, book, and pay for trips.
* **Admin:** Representatives from bus companies with full access to system logs, financial reports, user roles, schedule management, and manual payment verification.
* **Marshal:** Terminal staff with limited access specifically responsible for scanning e-ticket QR codes during boarding.

## Tech Stack & Operating Environment
* **Frontend:** React.js or Vue.js for a mobile-responsive user interface.
* **Backend:** Node.js (Express) or Python (Django/Flask).
* **Database:** PostgreSQL or MySQL for relational data integrity.
