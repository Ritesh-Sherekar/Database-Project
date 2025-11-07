# Course Selling Platform – Backend (PHP + MySQL)

This project is a backend implementation of an online **Course Selling Platform** similar to Udemy, developed using **PHP** and **MySQL**.  
It supports **Teacher** and **Student** roles, course creation, enrollment, authentication, and secure role-based access.

---

## 🚀 Features

### ✅ User Roles

#### **1. Teacher**
- Create new courses  
- Update or delete created courses  
- Add course description, price, and category  
- View students enrolled in their courses  

#### **2. Student**
- Browse all available courses  
- Enroll in courses  
- View enrolled courses  
- See course details  

---

## 🔐 Authentication & Security
- Login & Signup for Student/Teacher  
- Role-based access  
- Password hashing using `password_hash()`  
- Token-based login session (simple token or JWT depending on implementation)  

---

## 📚 Course Management
- Create / Update / Delete courses (Teacher only)  
- List all courses  
- Fetch course details  
- Fetch teacher-specific courses  

---

## 🎓 Enrollment Module
- Students can enroll into courses  
- Prevent duplicate enrollments  
- Teacher can view list of enrolled students  
- Student can view purchased/enrolled courses  

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | PHP (Core PHP / OOP PHP) |
| Database | MySQL |
| ORM | Native SQL Queries |
| Authentication | PHP Sessions or Token System |
| API Format | JSON Based REST APIs |
| Testing | Postman |

---

## ⚙️ Installation Guide

### ✅ 1. Clone the Repository
```bash
git clone https://github.com/Ritesh-Sherekar/Database-Project.git
cd Database-Project

