HR Management System - JavaFX Project

Project Overview

This JavaFX-based HR Management System was developed by Navdeep Singh (ID: 23094413) as part of a lab project. The application consists of multiple GUI pages and enables basic HR functionality such as login authentication, employee record creation, updates, deletions, and viewing.

Technologies Used

JavaFX

Replit

JUnit (for future testing)

MySQL (planned but not implemented)

Project Structure

GUI Pages Implemented:

Login Page: Accepts email and password.

Dashboard Page: Offers navigation to Admin, Employee, Logout, and Exit.

Admin Page: Allows full CRUD operations on employee records.

Employee Page: Similar interface with CRUD capabilities.

Alternate Implementation Note

Due to difficulties in connecting the application to a live MySQL database, the developer implemented an alternative:

Instead of connecting to MySQL, a new file called EmployeeData.java was created to hold sample employee records.

This file simulates database functionality and provides the following:

Sample user credentials for login.

Predefined employee records (name, role, email, salary).

In-memory storage for runtime record manipulation (Create, Update, Delete, View).

As a result, the application functions as expected for demonstrating all CRUD operations and login validation.

Screenshots Included (in accompanying DOCX file)

Login Page

Invalid Login Message

Dashboard Page

Admin Page (with working Create, Update, Delete, View)

Employee Page (same as Admin layout and functionality)

How to Run

Clone or download the project.

Open it in replit.

Run Main.java.

Project Status

 Fully functional without database using simulated data SQL database not integrated due to connection issues

Author

Navdeep Singh Student ID: 23094413
