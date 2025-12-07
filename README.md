# 📘 CocoNote – University Note Sharing Platform
*A database‑driven academic resource hub for students*

---

## 🚀 Overview

**CocoNote** is a university‑focused web application where students can **upload, share, download, and upvote academic notes**.  
This project is designed as a **DBMS‑centric system** for an RDBMS course and demonstrates:

- Advanced relational database design  
- Complex SQL queries  
- Stored procedures & triggers  
- Automated engagement features  
- Data integrity and normalization  

Notes are organized by **Department, Course, Semester, and Category** to ensure easy access to resources.

---

## 📌 Features

### 👤 User Management
- Student account creation
- Profile with activity statistics
- Badge rewards system

### 📄 Notes Management
- Upload & manage notes (PDF, image, docs)
- Categorization (Exam Papers, Lab Materials, Lecture Notes, etc.)
- Course & department based organization

### 👍 Engagement System
- Upvoting system
- Download tracking
- Automatic counter updates using triggers

### 🏆 Badge System
- Badges based on:
  - Total uploads
  - Total downloads
  - Total upvotes
- Automatically assigned using SQL triggers

### 📊 Analytics & Reporting
- Top contributors
- Most downloaded notes
- Department‑wise activity
- Course‑wise statistics

---

## 🗂️ Database Design (ERD Summary)

Main Entities:

- User  
- Department  
- Course  
- Category  
- Note  
- Download  
- Upvote  
- Badge  
- User_Badge (junction table)

Key Relationships:

- One User → Many Notes  
- One Course → Many Notes  
- One Category → Many Notes  
- One Note → Many Downloads  
- User ↔ Badge (Many‑to‑Many)

The database includes:
- Primary & Foreign Keys
- Junction tables
- Cascading relationships
- Normalized schema

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP / Node.js / Django (any can be used)  
- **Database:** MySQL / PostgreSQL  

---


## 📜 License

This project is developed for academic and educational purposes only.

## 📁 Project Structure

