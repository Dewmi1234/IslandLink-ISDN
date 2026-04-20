IslandLink ISDN - Centralised Sales Distribution Management System

Group Members
* Dewmi Kavindi - E220099
* Hirusha Nethmidu - E259171
* Haashim Rumy - E184715
* H.A.L. Maduskia - E285867

What we built
IslandLink ISDN is a comprehensive Centralised Island-wide Sales Distribution Management System designed to streamline wholesale sales, inventory management, and logistics operations. The system features a complete end-to-end workflow with three primary user interfaces:
1. Customer Portal: Allows retail customers to browse the product catalog, add items to their cart, and place orders with an integrated checkout system.
2. Admin Dashboard: Enables head office administrators to monitor daily sales metrics, manage product inventory (CRUD operations), and track the status of customer orders.
3. Driver/Logistics View: Provides delivery drivers with real-time job lists, order status updates, and dynamic route tracking utilizing Google Maps.

Technologies Used
* Frontend: HTML5, Tailwind CSS, Vanilla JavaScript
* Backend: Python (Flask Web Framework)
* Database: MySQL
* APIs & Libraries: Google Maps API (for live driver tracking and routing), Flask-CORS

How to run it

1. Database Configuration
1. Open XAMPP and start the Apache and MySQL modules.
2. Open phpMyAdmin (http://localhost/phpmyadmin).
3. Create a new database named islandlink_db.
4. Import the provided databaseSQLCODE.txt script to generate the required tables and insert the initial seed data.

2. Backend Setup
1. Ensure Python is installed on your machine.
2. Open a terminal in the project folder and install the required dependencies:
   pip install flask flask-cors mysql-connector-python
3. Start the Flask server:
   python app.py
   *The backend will now be running on http://127.0.0.1:5000.*

3. Frontend Setup
1. Double-click the index.html file to open it in any modern web browser.
2. Use the following demo credentials to test the system roles:
   * Admin: admin@islandlink.lk | Password: 123
   * Customer: customer@islandlink.lk | Password: 123
   * Driver: driver@islandlink.lk | Password: 123

Academic Supervision
This project was guided by Nimesha Rajakaruna as part of undergraduate coursework.

Git Hub Name - nimesharajakaruna1-beep
