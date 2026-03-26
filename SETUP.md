# Course Management System - Complete Setup Guide

## Prerequisites
- Java 8 or higher
- MSSQL Server 2016 or higher
- MSSQL JDBC Driver

## Database Tables

### Students
- id (PK)
- name
- email (unique)
- phone
- enrollment_date

### Courses
- id (PK)
- title
- description
- credits
- instructor_id (FK)

### Instructors
- id (PK)
- name
- email
- department
- hire_date

### Enrollments
- id (PK)
- student_id (FK)
- course_id (FK)
- enrollment_date
- grade

## Features
- Add/Remove/Update Students
- Manage Courses and Instructors
- Handle Student Enrollments
- Track Grades
- Generate Reports