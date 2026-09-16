# 📚 Library Management System

## 📌 Project Overview

The **Library Management System** is a CRUD-based web application designed to manage library books, members, and book issue/return records.

This project helps the librarian easily add, view, update, and delete book and member details. It also manages book issuing and returning activities.

## 🎯 Objectives

* Manage library books
* Manage student/member details
* Issue books to members
* Return issued books
* Track available books
* Search books easily
* Perform CRUD operations

## 🛠️ Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* Flask

### Database

* MySQL

### Development Tool

* Visual Studio Code

## 📂 Project Structure

```text
Library-Management-System/
│
├── app.py
├── database.sql
│
├── templates/
│   ├── index.html
│   ├── books.html
│   ├── members.html
│   └── issue_books.html
│
└── static/
    ├── style.css
    └── script.js
```

## 🗄️ Database Tables

### 1. Members

Stores student/member information.

* member_id
* name
* email
* phone
* department

### 2. Books

Stores library book information.

* book_id
* title
* author
* category
* quantity
* available_quantity

### 3. Issue Books

Stores book issue and return information.

* issue_id
* member_id
* book_id
* issue_date
* return_date
* status

## 🔄 CRUD Operations

### Create

Add new books and members.

### Read

View books, members, and issue records.

### Update

Update book and member information.

### Delete

Delete books or member records.

## 📖 Library Operations

1. Add Book
2. View Books
3. Update Book
4. Delete Book
5. Add Member
6. View Members
7. Issue Book
8. Return Book
9. Search Book
10. Check Available Books

## ⚙️ How to Run the Project

### Step 1: Clone or Download the Project

Open the project folder in Visual Studio Code.

### Step 2: Install Flask

```bash
pip install flask
```

### Step 3: Create Database

Open MySQL and run the `database.sql` file.

### Step 4: Configure Database

Enter your MySQL username and password in `app.py`.

### Step 5: Run the Application

```bash
python app.py
```

### Step 6: Open in Browser

```text
http://127.0.0.1:5000/
```

## ✅ Features

* Simple user interface
* Book management
* Member management
* Issue and return management
* Search functionality
* MySQL database integration
* CRUD functionality
* Easy to use

## 🚀 Future Enhancements

* Admin login
* Fine calculation
* Book reservation
* Email notifications
* Dashboard with statistics
* Student login
* Online book search

## 👩‍💻 Developed By

**Name:** Geetha
**Department:** AI & DS
**Project:** Library Management System

## 📄 License

This project is created for educational and academic purposes.
