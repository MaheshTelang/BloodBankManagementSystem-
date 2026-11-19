# BloodBankManagementSystem-
Blood Bank Management System using Java, JDBC, Servlets, JSP, Spring and MySQL
1. Project Description
The Blood Bank Management System is a Java-based web application designed to manage blood donor information efficiently. It provides an interface for administrators to log in, register donors, view donor records, edit donor details and delete donor records.

The application uses Java Servlets, JSP, JDBC and MySQL for its web and database functionality. It also includes demonstrations of Spring Dependency Injection and Java Swing.

2. Technologies and Tools Used
Programming Language: Java
Frontend: HTML, JSP
Backend: Java Servlets
Database Connectivity: JDBC
Database: MySQL
Database Management: XAMPP and phpMyAdmin
Java Framework: Spring Framework (Dependency Injection demonstration)
Desktop GUI: Java Swing demonstration
Web Server: Apache Tomcat 8.5.96
Build Tool: Maven
IDE: Apache NetBeans
3. Features and Functionalities
Administrator login and logout.
Session management and protected donor pages.
Donor registration.
Display of registered donor details.
Display of donor blood groups.
Editing donor information.
Deleting donor records.
MySQL database connectivity using JDBC.
Spring Dependency Injection demonstration.
Java Swing graphical interface demonstration.
4. Database Details
Database Name: blood_bank

The database contains the following seven tables:

ADMIN
BLOOD_GROUP
DONOR
DONATION
BLOOD_STOCK
HOSPITAL
BLOOD_REQUEST
The database export is included in this repository as blood_bank.sql.

5. Installation and Execution Instructions
Prerequisites
Install the following software:

JDK 17 or compatible Java version
Apache NetBeans IDE
XAMPP
Apache Tomcat 8.5.96 or a compatible Tomcat version
Step 1: Clone or Download the Repository
Download the project from this GitHub repository:

https://github.com/yana-codes24/BloodBankManagementSystem

Step 2: Start XAMPP
Open XAMPP Control Panel.
Start Apache and MySQL.
Open phpMyAdmin using http://localhost/phpmyadmin.
Step 3: Import the Database
Create a database named blood_bank.
Select the database.
Open the Import tab.
Choose the blood_bank.sql file.
Click Import.
Step 4: Configure Database Connectivity
Open the DBConnection.java file.

Check and update the database URL, username and password according to your local MySQL configuration.

Step 5: Open the Project
Open Apache NetBeans.
Select File → Open Project.
Choose the downloaded BloodBankManagementSystem folder.
Allow Maven to download the required dependencies.
Configure Apache Tomcat as the application server.
Step 6: Run the Application
Build the project using Clean and Build.
Run the project on Apache Tomcat.
Open the application in your browser.
Local application URL:

http://localhost:8080/BloodBankManagementSystem/

6. Application Screenshots
Screenshots of the application, including the homepage, administrator login, donor registration, donor records, Spring Dependency Injection and Swing interface, will be included in the repository.

7. GitHub Repository
https://github.com/yana-codes24/BloodBankManagementSystem

8. Project Information
Project Title: Blood Bank Management System
