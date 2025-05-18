🚗 CARCADDY – Car Rental Automation System
CARCADDY is a full-stack automation system designed to digitize and streamline the operations of a car rental business. It manages employee records, customers, car fleets, rentals, and business reports efficiently through an intuitive interface and smart automation.

📦 Modules Overview
1. Employee Management
Handles employee lifecycle within the system.

Register new employees with default login credentials.

Enforce password update on first login.

Auto-expire temporary accounts.

Email notifications for deactivated or expired accounts.

2. Car Management
Core module to manage rental car fleet.

Add, update, view, and delete car details.

Filter/search cars by status or vehicle type (with invalid case handling).

Set car status to “maintenance” with alerts.

Maintenance recommendation engine based on mileage and usage.

Logs maintenance history for each car.

Sends email alerts for car servicing.

3. Customer Management
Maintains customer information and booking behavior.

Add/update customer details and generate unique customer IDs.

Track bookings and maintain history.

Loyalty point system for repeat customers (redeemable).

Blacklisting mechanism for problematic customers (blocks further bookings).

4. Rental Management
Manages the end-to-end car booking process.

Book cars by customer ID, applying available discounts.

Modify booking details (car type, rental duration).

Cancel bookings with reason logging.

Return confirmation and car status update post-rental.

Accurate fare calculation including discount logic.

5. Reports Management
Provides business insights to support strategic decisions.

Identify most and least booked cars.

Track top customers by number of bookings.

Analyze income per car model.

Generate revenue reports for selected periods.

🔧 Technology Stack
Backend: Java, Spring Boot, Spring Data JPA, MySQL

Frontend: Thymeleaf (HTML template engine)

Tools: IntelliJ IDEA, MySQL Workbench, Postman

🎯 Outcome
CARCADDY enhances operational efficiency, reduces manual effort, ensures timely maintenance, and delivers meaningful business insights — all contributing to an improved rental service experience.
