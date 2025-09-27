# 📚 E-Learning Platform

## 📌 Overview
An **online learning platform** that connects instructors with students.  
The system allows instructors to upload courses, while students can enroll, watch lessons, and track progress.

---

## ✨ Features

### Students
- User registration & login.  
- Browse courses by category.  
- Enroll in free/paid courses.  
- Watch video lectures & download resources.  
- Track progress & completion status.  

### Instructors
- Create & manage courses.  
- Upload lessons, videos, and materials.  
- View enrolled students.  
- Manage course pricing and availability.  

---

## 🛠️ Tech Stack
- **Frontend:** Vue.js, Bootstrap, Axios  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Other:** JWT Authentication, REST APIs, GitHub  

---

## 📂 Database Design
- `Users` → students & instructors (roles).  
- `Courses` → title, description, price, instructor.  
- `Lessons` → video, resources, linked to courses.  
- `Enrollments` → student-course relationship.  

---

## 🚀 Installation & Run

### Backend (Node.js)
```bash
cd backend
npm install
npm run dev
