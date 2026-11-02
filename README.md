# LMS-edX-Website
Requirement Analysis, SRS Documentation, System Design, and ER Diagram for an edX-inspired Learning Management System (LMS).

## 🎓 Learning Management System (LMS) – edX Website

A requirement analysis and system design project for an edX-inspired Learning Management System (LMS). This project focuses on analyzing user roles, defining system requirements, designing LMS modules, and creating the database structure.

### 📌 Project Overview

The LMS is designed to support online learning activities, including course management, student enrollment, quizzes, assignments, progress tracking, notifications, and payments.

### 👥 User Roles

- **Super Admin:** Full system control, user management, roles, permissions, and payments.
- **Admin:** Course management, instructor approval, and student management.
- **Instructor:** Create courses, upload lessons, create quizzes and assignments, and monitor student progress.
- **Editor:** Edit and approve or reject course content.
- **Student:** Register, enroll in courses, watch lessons, submit assignments, and receive certificates.
- **Guest:** Browse public courses, search courses, and view course details.

### ⚙️ Functional Requirements

- Authentication and Authorization
- Role-Based Access Control (RBAC)
- User Management
- Course Management
- Lesson Management
- Enrollment System
- Quiz System
- Assignment Management
- Progress Tracking
- Notification System
- Payment System
- Analytics

### 🔒 Non-Functional Requirements

- Performance: Support up to 100K users and 10K concurrent users.
- Security: Password hashing, CSRF protection, XSS protection, SQL injection prevention, and secure file uploads.
- Scalability: Multiple servers and cache support.
- Availability: Target 99.9% uptime and backup support.
- Maintainability: Clean architecture.
- Usability: Easy-to-use interface and mobile-responsive design.

### 🛠️ Proposed Tech Stack

- **Frontend:** Blade / React / Vue
- **Backend:** PHP Laravel
- **Database:** MySQL
- **Cache & Queue:** Redis
- **Storage:** AWS S3
- **Realtime:** Pusher / WebSocket
- **Server:** Nginx
- **Deployment:** Docker
- **CI/CD:** GitHub Actions

### 📚 Project Documentation

- [View Complete LMS Documentation)](https://app.notion.com/p/Learning-Management-System-LMS-of-the-edX-Website-376f7701a79c802eb8d4ea78a8e16f85?source=copy_link)
- [ER Diagram]([./docs/ER_Diagram.pdf](https://app.eraser.io/workspace/exsUFzdGia6KUoKZVxBI?origin=share&diagram=SPmQSpAD6J5lhbmG6mcxV))

### 🗂️ ER Diagram & System Design

[View LMS ER Diagram and System Design on Eraser.io](https://app.eraser.io/workspace/exsUFzdGia6KUoKZVxBI?origin=share&diagram=SPmQSpAD6J5lhbmG6mcxV)

