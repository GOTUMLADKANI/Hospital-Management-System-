# Hospital-Management-System
Build by using (Java + MySQL)

This is a desktop-based Hospital Management System developed in Java using Swing for the graphical interface and MySQL for the database.

The main purpose of this project is to digitize basic hospital operations that are usually handled manually. It allows efficient management of patient records, doctor information, room allocation, billing, and user authentication.

This project was developed as part of a semester coursework to apply practical knowledge of Java programming and database systems.

The concepts applied in this project include:

Java GUI development using Swing
Database integration using JDBC
CRUD operations
Basic system design principles

System Features

User login and authentication
Add new system users
Change user passwords
Add, update, and delete doctor records
Add, update, and delete patient records
Admit patients to rooms
Discharge patients from rooms
Manage hospital room details
Generate room bills
Manage hospital services

The system follows a complete workflow starting from patient admission to discharge and billing.

Technologies Used

Java (Swing)
MySQL
JDBC (MySQL Connector)
NetBeans IDE

How the System Works

The application connects to a MySQL database using JDBC for data storage and retrieval. Each module such as patients, doctors, rooms, billing, and services communicates directly with the database to perform required operations.

All records are stored permanently in the database. The system is menu-driven and uses a graphical user interface for easy interaction.

How to Run the Project

Install MySQL on your system.

Create a database and import the provided hp_mgmt_db.sql file.

Open the project in NetBeans or any Java IDE.

Update database credentials in Connect.java.

Compile and run Main.java.


Future Improvements

Apply MVC architecture for better code organization

Improve the user interface design

Encrypt user passwords for better security

Add reporting and analytics features

Convert the system into a web-based application

Author

Gotam Ladkani
Software Engineering Student
