# Student-DB-App-Mini-Project
Student Database App Mini project - IT 3003. Name - M.G.V.O. Ranasinghe, Index no. - s16550, Registration no. - 2022s19602

# Student Database Management System

Overview
A console-based Student Database Management System built with Java, MySQL, and Apache NetBeans. This application allows users to perform CRUD (Create, Read, Update, Delete) operations on student records through a simple text-based interface. The IntelliJ IDEA software was not working for my laptop, therefore I had to use Apache NetBeans software. 

Features - 
- Add new student records
- View individual student details
- View all students in the database
- Update existing student information
- Delete student records

Database Schema -
MySQL database structure:
- ID (Primary Key)
- Name
- Grade
- Date of Birth (DOB)
- Subject

Prerequisites - 
- Java Development Kit (JDK) 24
- Apache NetBeans IDE 27
- MySQL Workbench
- MySQL Connector/J (version 8.0.33)

Installation - 
1. Download the project files
2. Import the project into Apache NetBeans
3. Ensure MySQL is running on your system
4. Create a database named `StudentDB` in MySQL Workbench
5. Update the database connection

Dependencies - 
- MySQL Connector/J 8.0.33
- JSON library 3.2.13

Project Structure - 
Main Files: DatabaseConnection.java, Main.java, Student.java, StudentDB.java, StudentDao.java 
Dependancies: mysql-connector-j-8.0.33.jar, json-3.2.13.jar, JDK 24
Test Packages
Project files: pom.xml

Usage - 
1. Run the application from NetBeans
2. Use the numeric menu to select operations:
   - 1: Add Student
   - 2: View Student
   - 3: View All Students
   - 4: Update Student
   - 5: Delete Student
   - 6: Exit
3. Follow the prompts to perform the desired operations

Code Overview - 
- Main.java: Contains the main method and user interface logic
- Student.java: Defines the Student model class
- StudentDao.java: Data Access Object for database operations
- DatabaseConnection.java: Handles database connection setup

Troubleshooting -
- Ensure MySQL service is running
- Verify database credentials in DatabaseConnection.java
- Check that all required JAR files are properly referenced

License - 
This project is for educational purposes.
