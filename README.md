# Java Course Management System

## Overview
This Java Course Management System is designed to manage course registrations, students, and instructors efficiently. It uses Microsoft SQL Server (MSSQL) as the database and Java Database Connectivity (JDBC) for database operations.  

## Features
- Manage students and their information
- Manage courses and their details
- Manage instructors and their assignments
- Registration and deregistration of students for courses
- Retrieve reports on course registrations

## Database Design
### Entities:
1. **Students**  
   - id (int, Primary Key)  
   - name (varchar)  
   - email (varchar)  
   - phone (varchar)
   - ...

2. **Courses**  
   - id (int, Primary Key)  
   - title (varchar)  
   - description (text)  
   - credits (int)
   - ...

3. **Instructors**  
   - id (int, Primary Key)  
   - name (varchar)  
   - department (varchar)
   - ...

4. **Enrollments**  
   - student_id (int, Foreign Key)  
   - course_id (int, Foreign Key)

## Technologies Used
- Java
- MSSQL Database
- JDBC

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Hammadullah1/course-management-system.git
   ```
2. Set up the MSSQL database and configure the JDBC connection in the application.
3. Follow the provided instructions to run the application.

## Usage
- Compile the Java files:
  ```bash
  javac *.java
  ```
- Run the application:
  ```bash
  java Main
  ```

## Contribution
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bugs.

## License
This project is licensed under the MIT License.