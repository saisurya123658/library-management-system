# 📚 Library Book Search and Borrow System

A full-stack web-based Library Management System that allows students to search, borrow, and access books, audiobooks, and documents online, while enabling administrators to manage library resources efficiently.

This system modernizes traditional library operations by digitizing book management, borrowing, multimedia access, and student interactions through a secure web interface.

---

## 🚀 Features

### 👨‍💼 Admin Features
- Secure admin login
- Add, update, and delete books
- Manage students
- Upload and manage audiobooks
- Upload and manage documents (PDFs, notes)
- Track borrowing and return status
- View student borrowing history
- Send reminders and communicate with students
- Monitor system activity

### 🎓 Student Features
- Secure student login
- Search and browse books
- Borrow and return books
- View borrowing history
- Listen to audiobooks online
- View documents and PDFs in browser
- Update profile
- Chat with admin

### 🔐 Security Features
- Role-based access control
- Password hashing
- Session-based authentication
- Input validation and sanitization
- Secure file upload handling

---

## 🏗️ System Architecture

The system follows a 3-layer architecture:

- Presentation Layer: HTML, CSS, Bootstrap frontend
- Application Layer: PHP backend logic and APIs
- Data Layer: MySQL database

---

## 🛠️ Technology Stack

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript
- AJAX

### Backend
- PHP

### Database
- MySQL

### Tools
- XAMPP / WAMP / LAMP
- VS Code
- phpMyAdmin
- Git & GitHub
- Postman

---

## 📁 Project Structure

```
Library_Management/
│
├── admin/
│   ├── admin_dashboard.php
│   ├── manage_books.php
│   ├── manage_students.php
│   ├── upload_audio.php
│   ├── upload_document.php
│
├── student/
│   ├── student_dashboard.php
│   ├── my_borrowings.php
│   ├── audio.php
│   ├── documents.php
│
├── assets/
│   ├── css/
│   ├── images/
│   └── icons/
│
├── config/
│   ├── db.php
│   └── config.php
│
├── uploads/
│   ├── audio/
│   ├── documents/
│   └── book_covers/
│
├── index.php
├── login.php
└── database.sql
```

---

## ⚙️ Installation Guide

### Step 1: Install Requirements

Install the following software:

- XAMPP / WAMP / LAMP
- Git
- VS Code (recommended)

---

### Step 2: Clone Repository

```bash
git clone https://github.com/yourusername/library-management-system.git
```

Move project folder into:

```
xampp/htdocs/
```

---

### Step 3: Setup Database

1. Open phpMyAdmin  
2. Create new database:

```
library_management
```

3. Import file:

```
config/database.sql
```

---

### Step 4: Configure Database Connection

Open file:

```
config/db.php
```

Update credentials:

```php
$host = "localhost";
$user = "root";
$password = "";
$dbname = "library_management";
```

---

### Step 5: Run Project

Start Apache and MySQL in XAMPP.

Open browser and go to:

```
http://localhost/Library_Management/
```

---

## 🧪 Testing

Tested features:

- Admin login
- Student login
- Book add/delete
- Borrow and return system
- Audio streaming
- Document viewing
- Role-based access

Tools used:

- Browser DevTools
- Postman
- Manual testing

---

## 📊 Database Tables

Main tables include:

- users
- books
- borrow
- audiobooks
- documents
- categories
- logs

---

## 🎯 Objectives Achieved

- Digital library automation
- Real-time borrow tracking
- Multimedia support
- Secure role-based system
- Scalable backend architecture

---

## 🔮 Future Enhancements

- Mobile app version
- AI book recommendations
- Fine management system
- Chatbot integration
- Analytics dashboard
- Multi-language support

---

This project is developed for educational purposes.

---

## ⭐ Support

If you like this project, please star the repository.
