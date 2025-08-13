# Student Attendance Management System

## Student Information
- **Name:** Kazi Abu Jafor Arif  
- **ID:** 231-115-068  
- **Section:** B  
- **University:** Metropolitan University  
- **Course:** CSE 224 (Database Management System)
-  **Course Teacher:** Fahmidur Rahman Sakib

---

## Project Objective
A PHP/MySQL web application for managing student attendance with:

- Admin and Teacher panels
- Class and section management
- Daily attendance recording
- Report generation and export

---

## Database Design

### ER Diagram
![ER Diagram](https://github.com/kaziarif1/student-attendance-management-system/blob/main/ER%20Diagram/Student%20Attendance%20Management%20System%20_%20Mermaid%20Chart-2025-08-09-091114.png)

**Key Entities:**
- Admin
- Teacher
- Student
- Class
- Section (Class Arm)
- Attendance

---

## Implemented Functionalities

### Admin Panel
- Manage classes and sections
- Assign class teachers
- Enroll students
- Set up academic terms and sessions

### Teacher Panel
- Mark daily attendance by section
- View student lists
- Generate attendance reports
- Export reports to Excel

---

## Technology Used
- **Language:** PHP 7.4
- **Database:** MySQL
- **Frontend:** HTML, CSS, Bootstrap
- **Type:** Web Application

---

## Screenshots

### Login Page
![Login Page](https://github.com/kaziarif1/student-attendance-management-system/blob/main/screenshot/admin%20log%20in%20page%20picture.png)

### Admin Dashboard
![Admin Dashboard](https://github.com/kaziarif1/student-attendance-management-system/blob/main/screenshot/admin%20dashboard.png)

### Teacher Dashboard
![Teacher Dashboard](https://github.com/kaziarif1/student-attendance-management-system/blob/main/screenshot/cl%20dashboard.png)

### Attendance Taking Page
![Attendance Page](https://github.com/kaziarif1/student-attendance-management-system/blob/main/screenshot/attendnce%20taking.png))


## 1. Prerequisites
- [XAMPP](https://www.apachefriends.org/) (or any PHP + MySQL environment)
- PHP 7.4+ recommended
- MySQL

---

## 2. Steps

1. **Download the Project**
   - Download the ZIP file or clone from your repository:
     ```bash
     git clone (https://github.com/kaziarif1/student-attendance-management-system.git)
     ```

2. **Move to XAMPP htdocs**
   - Place the folder inside:
     ```
     C:/xampp/htdocs/
     ```

3. **Import the Database**
   - Open phpMyAdmin: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
   - Create a new database:
     ```
     attendancemsystem
     ```
   - Import the `.sql` file located in:
     ```
     DATABASE FILE/attendancemsystem.sql
     ```

4. **Run the Project**
   - Open in browser:
     ```
     http://localhost/attendance_management/
     ```

---

## Demo Video
📺 **Watch Full Demonstration:** [Click Here](https://drive.google.com/file/d/1iXnL-4R-msdwQnH5D7YsNlGrSFnkHlja/view?usp=sharing)  
*(Video covers all system features, frontend/backend explanation, and database queries)*


---
