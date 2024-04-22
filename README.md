# Student-Management-System
To run the Student Management System (StudentMS) project, follow these step-by-step instructions:

Prerequisites:
XAMPP, WAMP, LAMP, or any local web server environment installed on your system.
PHP and MySQL are properly configured and running.
Access to PHPMyAdmin for database management.

Steps:

Download and Extract:
Download the zip file containing the StudentMS project.
Extract the zip file to obtain the studentms folder.

Move to Root Directory:
Copy the studentms folder.
Paste it inside the root directory of your web server.
For XAMPP: xampp/htdocs
For WAMP: wamp/www
For LAMP: var/www/html

Database Setup:
Open your web browser and navigate to http://localhost/phpmyadmin.
Log in to PHPMyAdmin using your credentials.

Create Database:
In PHPMyAdmin, click on the Databases tab.
Enter studentmsdb as the database name and click Create.

Import SQL File:
Select the newly created studentmsdb database from the left sidebar.
Click on the Import tab.
Choose the studentmsdb.sql file located in the SQL file folder of the extracted studentms folder.
Click Go to import the database structure and data into studentmsdb.

Access the Project:
Open your web browser.
Navigate to http://localhost/studentms to access the frontend of the Student Management System.

Login to Admin Panel:
Use the following credentials to access the admin panel:
Username: admin
Password: Test@123

Login to Student/User Panel:
Alternatively, you can login to the student/user panel using:
Username: anujk3
Password: Test@123
Or register a new student/user if desired.

Note:
Ensure that your web server (XAMPP, WAMP, LAMP) is running.
Make sure file and folder permissions are set correctly for the studentms folder.
After successful login, explore the features of the Student Management System such as student enrollment, course management, attendance tracking, and more.
Customize or extend the project as needed based on your requirements.

By following these steps, you should be able to set up and run the Student Management System project on your local environment for testing and exploration.





