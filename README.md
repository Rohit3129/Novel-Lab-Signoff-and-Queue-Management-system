# Novel-Lab-Signoff-and-Queue-Management-system
# 🧪 Lab Sign-Off & Student Request Management System

**Full-stack web platform for academic lab sign-off with role-based access**

---

## 📌 Overview

The **Lab Sign-Off & Student Request Management System** is a web-based application designed to digitize and streamline the laboratory submission and sign-off process in universities. It replaces manual and paper-based workflows with a secure, queue-driven, and role-based system that improves efficiency, transparency, and accountability.

The platform supports three main roles: **Student**, **Assistant**, and **Professor**, each with clearly defined responsibilities and access control.

---

## 🎯 Objectives

* Automate the academic lab sign-off process
* Reduce manual effort and delays in lab verification
* Provide real-time queue and status tracking
* Ensure secure, role-based access control
* Improve transparency and traceability of lab submissions

---

## 🚀 Key Features

### 👨‍🎓 Student

* Submit lab work with file uploads (screenshots/evidence)
* View real-time queue status
* Track submission history and outcomes

### 🧑‍🏫 Assistant

* View and verify pending lab submissions
* Claim and manage requests from the queue
* Flag complex submissions for professor review

### 👨‍🏫 Professor

* Review flagged submissions
* Approve or reject lab work
* Grade submissions and provide feedback

### 🔐 System Features

* JWT-based authentication
* Role-Based Access Control (RBAC)
* Queue management system
* Email notifications for key actions
* Dashboard analytics and request tracking

---

## 🛠️ Technology Stack

* **Frontend:** React, CSS
* **Backend:** Python, Django REST Framework
* **Authentication:** JWT
* **Database:** MySQL
* **Architecture:** RESTful APIs (Microservices-ready)

---

## 🧩 System Architecture (High-Level)

1. React frontend communicates with backend via REST APIs
2. Django REST API handles authentication, business logic, and role access
3. MySQL stores users, submissions, queue data, and audit logs
4. Optional services for notifications and analytics

---

## 📂 Project Structure (Simplified)

```
/frontend    -> React UI
/backend     -> Django REST API
/database    -> MySQL schemas
/docs        -> Documentation & reports
```

---

## 🔒 Security

* Secure JWT-based login
* Role-based endpoint protection
* File upload validation
* Permission checks for all critical actions

---

## 📈 Future Enhancements

* Real-time updates using WebSockets
* Advanced analytics and reports
* Mobile-friendly UI
* Integration with university LMS systems
* Deployment using Docker and cloud services

---

## 👨‍💻 Author

**Rohit Ramesh Lamkhade**
MSc Advanced Computer Science
Swansea University

---

## 📄 License

This project is developed for academic purposes. Licensing can be added if open-sourced.

---

⭐ *If you find this project useful, feel free to star the repository!*

