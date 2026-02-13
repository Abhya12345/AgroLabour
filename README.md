# AgroLabour
Here is a clear "How to Run the Project" section you can directly put in your GitHub README for your AgroLabour (Servlet, JSP, MySQL) project:

How to Run the AgroLabour Project

Follow the steps below to set up and run the AgroLabour project on your local system.

1. Prerequisites

Make sure the following software is installed:

Java JDK 8 or higher

Apache Tomcat 9 or higher

MySQL Server

Eclipse IDE (Enterprise Edition recommended)

XAMPP or MySQL Workbench (for database management)

Web browser (Chrome, Edge, etc.)

2. Import the Project in Eclipse

Open Eclipse IDE

Go to File → Import → Existing Projects into Workspace

Select the AgroLabour project folder

Click Finish

3. Configure Apache Tomcat Server

Open Eclipse

Go to Servers → Right click → New → Server

Select Apache Tomcat v9.0

Set the Tomcat installation directory

Click Finish

Right click project → Run on Server

4. Setup the MySQL Database

Open phpMyAdmin or MySQL Workbench

Create a new database:

CREATE DATABASE agrolabour;


Import the provided SQL file:

agrolabour.sql


Verify database connection in the project:

DB URL: jdbc:mysql://localhost:3306/agrolabour
Username: root
Password: your_password

5. Run the Project

Start Apache Tomcat Server

Open your browser

Enter the URL:

http://localhost:8080/AgroLabour/

