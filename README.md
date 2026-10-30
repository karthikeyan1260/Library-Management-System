# 📚 Library Management System using Python

A simple **Library Management System** developed using Python and Object-Oriented Programming (OOP). This project manages book details, calculates due dates, checks submission status, and automatically calculates fines for overdue book returns.

## 📌 Project Overview

The Library Management System is designed to simplify book return tracking by calculating due dates based on the issue date and borrowing period.

It also identifies whether a book is returned on time or late and calculates the applicable fine based on the number of overdue days.

## 🎯 Problem Statement

Manually calculating book due dates and overdue fines can be time-consuming and may lead to calculation errors.

This project provides a Python-based solution that automates date calculations, submission tracking, and fine calculations.

## 🛠️ Technology Stack

- **Programming Language:** Python
- **Concepts:** Object-Oriented Programming (OOP)
- **Inheritance:** Parent and Child Classes
- **Constructors:** `__init__()`
- **Date Handling:** Custom Date Calculation Logic
- **Conditional Statements:** `if-else`
- **Loops:** `for` and `while`
- **User Input:** `input()`

## ⚙️ How It Works

1. Enter the book name.
2. Enter the book ID.
3. Provide the book issue date in `DD/MM/YYYY` format.
4. Enter the borrowing period in days.
5. Provide the book submission date.
6. The system calculates the due date.
7. It compares the submission date with the due date.
8. If the book is returned late, the system calculates the overdue days and total fine.

## 💰 Fine Calculation

The system applies a fixed fine of **₹10 per overdue day**.

**Formula:**

```python
Total Fine = Overdue Days * Fine Per Day
```

Example:

- Fine Per Day = ₹10
- Overdue Days = 5
- Total Fine = ₹50

## 🧠 Key Features

- Book details management.
- Automatic due-date calculation.
- Custom date conversion logic.
- Leap-year calculation.
- Handles different month lengths.
- Checks book submission status.
- Calculates overdue days.
- Automatically calculates late submission fines.
- Uses inheritance without the `super()` function.

## 🏗️ Project Structure

```text
Library-Management-System/
│
├── Library Management System.ipynb
└── README.md
```

## 💻 Code Concepts Implemented

### 1. Classes and Objects

Created two classes:

- `Book` – Stores book name and book ID.
- `LibraryManagement` – Manages issue dates, borrowing periods, submission dates, and fine calculations.

### 2. Inheritance

The `LibraryManagement` class inherits from the `Book` class.

```python
class LibraryManagement(Book):
```

### 3. Parent Constructor Without super()

Initialized parent-class attributes directly using:

```python
Book.__init__(self, Book_Name, Book_ID)
```

### 4. Leap Year Calculation

Implemented custom logic to identify leap years.

```python
def is_leap_year(self, Year):
    return Year % 400 == 0 or (Year % 4 == 0 and Year % 100 != 0)
```

### 5. Fine Calculation

Calculates the fine based on overdue days.

```python
Overdue_Days = Submission_Total - Due_Total
Fine = Overdue_Days * self.Fine_Per_Day
```

## 📊 Sample Output

```text
Enter Book Name: Python Programming
Enter Book ID: B101
Enter Issued Date (DD/MM/YYYY): 01/10/2026
Enter Period (Days): 10
Enter Submission Date (DD/MM/YYYY): 16/10/2026

----- Library Management -----
Book Name        : Python Programming
Book ID          : B101
Issued Date      : 01/10/2026
Period           : 10 Days
Due Date         : 11/10/2026
Submission Date  : 16/10/2026
Status           : Submitted Late
Overdue Days     : 5
Fine Per Day     : ₹ 10
Total Fine       : ₹ 50
```

## 🌍 Real-World Applications

- School and college libraries.
- Public library management.
- Corporate libraries.
- Book lending services.
- Educational institutions.

## 📚 My Learnings

Through this project, I gained practical knowledge of:

- Python Object-Oriented Programming.
- Classes, objects, and inheritance.
- Constructor implementation.
- Date calculation algorithms.
- Leap-year logic.
- Conditional statements and loops.
- Implementing real-world business logic.

## 🚀 Future Enhancements

- Multiple book management.
- Student and member registration.
- Book availability tracking.
- Database integration using SQLite or MySQL.
- Book issue and return history.
- Graphical User Interface (GUI).

## 👨‍💻 Author

**Karthikeyan**

Aspiring GenAI Developer

---

⭐ If you find this project useful, consider giving this repository a star!

**#Python #PythonProjects #OOP #LibraryManagementSystem #GenAI**
