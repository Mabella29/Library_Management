# Library Management System - MySQL Database

## 📖 Description
A relational database designed to manage books, authors, members, and loans for a library system. Built with MySQL, this project demonstrates database design principles including table relationships (1-M, M-M), constraints (PK, FK, NOT NULL), and data integrity.

---

## 🗃️ Database Schema
### **Entities (Tables)**
1. **Books** - Stores book details (title, ISBN, etc.).
2. **Authors** - Records author information.
3. **Members** - Tracks library members.
4. **Loans** - Manages book borrowing records.
5. **Book_Authors** - Junction table for books and authors (M-M relationship).

### **ER Diagram**
a screenshot is shown in the image folder

---

## 🛠️ Setup Instructions
### **Prerequisites**
- MySQL Server installed (e.g., MySQL 8.0+).
- MySQL client (e.g., MySQL Workbench, command-line tool).

### **Steps**
1. Clone this repository:
   ```bash
   git clone https://github.com/Mabella29/library_management.git
