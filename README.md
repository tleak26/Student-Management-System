# 🎓 Student Management System

A **Python-based desktop application** built with **PyQt6** and **SQLite** to manage student records efficiently.  
This app allows users to **add**, **edit**, **search**, and **delete** student information through a clean and interactive graphical interface.

---

## 🧰 Features

✅ Add new students with name, course, and mobile number  
✅ View all student records in a table  
✅ Edit existing student details  
✅ Search for a student by name  
✅ Delete a student record  
✅ Data persistence using SQLite  
✅ Simple, user-friendly interface built with PyQt6  

---

## 🏗️ Project Structure

student-management-system/
│
├── main.py # Main application file
├── database.db # SQLite database (auto-created)
├── icons/ # Icon images (add.png, search.png, etc.)
├── requirements.txt # Python dependencies
├── screenshots/ # Optional folder for screenshots
└── README.md # Project documentation

---

## ⚙️ Installation Guide

Follow these steps to set up and run the project locally.

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

2️⃣ Create and Activate a Virtual Environment

python -m venv venv
# Activate the virtual environment
# For Windows:
venv\Scripts\activate

3️⃣ Install Required Dependencies
Install all project dependencies using:

pip install -r requirements.txt

4️⃣ Run the Application

python main.py

🗃️ Database Setup
The application uses a SQLite database file named database.db.
If it doesn’t exist, create it manually with the following schema:

CREATE TABLE students (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    name TEXT NOT NULL,
    course TEXT NOT NULL,
    mobile TEXT NOT NULL
);

🧩 How It Works

Launch the app and view all student records in the main table.
Use the menu or toolbar to add, search, edit, or delete students.
Clicking a row enables Edit and Delete buttons in the status bar.
All changes are immediately reflected in the database.

📦 requirements.txt
Here’s the content for your requirements.txt file:

PyQt6==6.6.1

Create this file in your project folder by running:
echo PyQt6==6.6.1 > requirements.txt

🧱 Technologies Used

Python 3.x
PyQt6 – GUI framework for desktop apps
SQLite3 – Lightweight relational database engine
QTableWidget, QDialog, QMessageBox – for GUI components

