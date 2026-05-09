# UNIVERSITY ATTENDANCE APP

## Project Overview

The University Attendance App is a web-based application developed using HTML, CSS, and JavaScript to simplify attendance tracking for students and instructors. The application provides separate login systems and dashboards for tutors (instructors) and students.

Students can register, log in, join courses using course codes, and mark their attendance. Tutors can register, log in, create courses, manage student rosters, and monitor attendance records. The system stores attendance data locally using browser local storage for persistence.

The application is designed with a modern, responsive, and user-friendly interface to ensure smooth navigation across desktop and mobile devices.

---

# Login Module

The application includes separate authentication logic for:

## Tutor Login Logic

Tutors (instructors) can:

* Register using name, email, and password
* Log in securely
* Create and manage courses
* Add or remove students from rosters
* View attendance records
* Monitor student participation

### Demo Tutor Login

* **Email:** `prof@uni.com`
* **Password:** `Pass@123`

---

## Student Login Logic

Students can:

* Register using personal details
* Log in securely
* Join courses using course codes
* Mark attendance
* View attendance summaries
* Track enrolled courses

### Demo Student Login

* **Email:** `student@uni.com`
* **Password:** `Pass@123`

---

# Demo Course Codes

The following sample course codes are used in the application:

| Course Code | Course Name                 |
| ----------- | --------------------------- |
| CSE101      | Data Structures             |
| CSE102      | Computer Networks           |
| CSE103      | Database Management Systems |
| MAT101      | Engineering Mathematics     |
| ENG101      | Technical English           |

Students can join courses by entering the course code.

Example:

```text
Course Code: CSE101
Course Name: Data Structures
```

---

# Objectives

* To develop a university attendance management system.
* To provide secure login and registration for tutors and students.
* To allow students to join courses and mark attendance.
* To enable tutors to manage courses and student rosters.
* To maintain attendance records efficiently.
* To design a responsive and user-friendly interface.
* To implement local data storage for persistence.
* To handle errors and invalid user inputs.

---

# Technologies Used

| Technology    | Purpose                      |
| ------------- | ---------------------------- |
| HTML          | Structure of the application |
| CSS           | Styling and responsive UI    |
| JavaScript    | Application functionality    |
| Local Storage | Data persistence             |

---

# Features of the Application

## 1. User Authentication

The application supports:

* Tutor registration and login
* Student registration and login
* Role-based dashboard access

---

## 2. Student Features

Students can:

* Join courses using course codes
* Mark attendance
* View enrolled courses
* Track attendance status

---

## 3. Tutor Features

Tutors can:

* Create courses
* Manage rosters
* Add or remove students
* Monitor attendance records

---

## 4. Attendance Tracking

The system stores attendance:

* Course-wise
* Student-wise
* Date-wise

---

## 5. Database Management

The application uses local storage to save:

* User details
* Course details
* Attendance records
* Student rosters

---

## 6. Error Handling

The system handles:

* Invalid login credentials
* Duplicate course codes
* Empty form inputs
* Invalid course joins
* Duplicate enrollments

---

## 7. Responsive UI Design

The interface supports:

* Desktop
* Laptop
* Tablet
* Mobile devices

---

# Advantages of the Project

* Easy to use
* Role-based system
* Efficient attendance tracking
* Modern responsive design
* Supports tutor and student workflows
* Simple local data storage
* User-friendly interface

---

# Enhancements

## 1. Firebase Integration

The app can use Firebase Realtime Database for cloud storage.

---

## 2. QR-Based Attendance

Students can scan QR codes to mark attendance.

---

## 3. Face Recognition System

Automatic attendance can be implemented using AI face recognition.

---

## 4. Email Notifications

Attendance alerts and reminders can be sent through email.

---

## 5. Report Generation

Attendance reports can be exported as:

* PDF
* Excel
* CSV

---

## 6. Admin Dashboard

An administrator panel can manage all users and courses.

---

## 7. Mobile App Version

The project can be converted into:

* Android application
* iOS application

using Flutter or React Native.

---

# Limitations

## 1. Local Storage Dependency

Data is stored only in the browser.

---

## 2. No Centralized Database

The current version does not use an online database.

---

## 3. Basic Security

Advanced authentication mechanisms are not implemented.

---

## 4. No Real-Time Synchronization

Changes are not synchronized across multiple devices.

---

## 5. Single Browser Access

Data may be lost if browser storage is cleared.

---

# Testing

The application was tested for:

* Tutor login
* Student login
* Registration functionality
* Course creation
* Course joining
* Attendance marking
* Roster management
* Error handling
* Responsive UI behavior

All modules functioned successfully.

---

# Sample Output Screenshots

## Screenshot 1 – Login Screen

Attach screenshot showing tutor and student login interface.

<img width="1875" height="869" alt="image" src="https://github.com/user-attachments/assets/e2b4b497-d1f6-43c3-a178-d85d5bff2f32" />

---

## Screenshot 2 – Registration Screen

Attach screenshot showing new user registration form.

<img width="1919" height="910" alt="image" src="https://github.com/user-attachments/assets/5acf03c8-d7fa-4fe5-bd05-f89804fa5e3d" />

<img width="1788" height="820" alt="image" src="https://github.com/user-attachments/assets/e36595dd-0941-4642-b18b-9492eba16246" />

---

## Screenshot 3 – Tutor Dashboard

Attach screenshot showing course management options.

<img width="1901" height="923" alt="image" src="https://github.com/user-attachments/assets/25312d14-ed62-4941-a311-b33d8faeafbf" />

---

## Screenshot 4 – Student Dashboard

Attach screenshot showing enrolled courses and attendance marking.

<img width="1898" height="910" alt="image" src="https://github.com/user-attachments/assets/91bd6782-0b0a-44dc-b860-7dffc115cbba" />

---

## Screenshot 5 – Course Creation Screen

Attach screenshot showing course code and course name creation.

<img width="1915" height="909" alt="image" src="https://github.com/user-attachments/assets/6e94c370-d94d-4c0f-a7d0-58103cb7b480" />

<img width="599" height="915" alt="image" src="https://github.com/user-attachments/assets/5a54e9d9-98d6-439a-b712-2ee8e4db4216" />

<img width="597" height="918" alt="image" src="https://github.com/user-attachments/assets/686a4c09-dcd9-401e-af46-add74f856add" />

<img width="591" height="913" alt="image" src="https://github.com/user-attachments/assets/ed6d32bb-67f2-44ba-80c9-e94862670fef" />

<img width="602" height="593" alt="image" src="https://github.com/user-attachments/assets/f59aa8a9-495e-42b6-8ead-463e4d75f30b" />


---

## Screenshot 6 – Roster Management Screen

Attach screenshot showing student roster management.

<img width="580" height="865" alt="image" src="https://github.com/user-attachments/assets/a03118f7-4755-44d7-8852-6d4dda7b51e8" />

---

## Screenshot 7 – Attendance Record Screen

Attach screenshot showing attendance tracking and records.

<img width="605" height="917" alt="image" src="https://github.com/user-attachments/assets/afdd1d57-0684-438f-b68b-3c46c53b14af" />

---

## Screenshot 8 – Mobile Responsive View

Attach screenshot showing mobile-friendly interface.

<img width="599" height="913" alt="image" src="https://github.com/user-attachments/assets/4e5fbd32-3a42-4e47-b6e5-24b1a4197b3d" />

<img width="607" height="814" alt="image" src="https://github.com/user-attachments/assets/70a2a6d0-76a0-40e0-9b7f-70afac771530" />


---

# Conclusion

The University Attendance App successfully demonstrates a complete attendance management system for educational institutions. The application supports tutor and student authentication, course management, attendance tracking, roster handling, and responsive user interaction.

The project effectively showcases front-end development concepts, local database management, role-based access control, and modern responsive UI design. Future improvements can transform the project into a full-scale cloud-based attendance management platform.
