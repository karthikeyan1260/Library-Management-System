# 📚 Library Management System Using Python

A simple **Library Management System** built with Python to manage book details, calculate due dates, track submission status, and calculate fines for overdue books. This project demonstrates core **Object-Oriented Programming (OOP)** concepts, including classes, objects, and inheritance.

## 📌 Project Overview

The Library Management System helps track the borrowing and return process for individual books. It calculates the due date based on the issue date and borrowing period, compares the due date with the actual submission date, and calculates the applicable fine.

## 🎯 Problem Statement

Manual tracking of book issue dates, due dates, and return dates can lead to calculation errors. This project provides a Python-based solution to simplify date calculations and determine overdue fines accurately.

## 🛠️ Technology Stack

- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Concepts:** Object-Oriented Programming (OOP)
- **OOP Features:** Classes, Objects, Inheritance
- **Logic Implemented:** Date calculations, leap-year handling, conditional statements, and fine calculation

## ⚙️ Features

- 📖 Accepts book name and book ID.
- 📅 Takes the issue date, borrowing period, and submission date as input.
- 🗓️ Calculates the due date automatically.
- ✅ Identifies whether a book was submitted on time or late.
- ⏳ Calculates the number of overdue days.
- 💰 Calculates a fine of **₹10 per overdue day**.
- 📆 Handles leap years and varying month lengths.

## 🔄 How It Works

1. Enter the book name and book ID.
2. Enter the issue date in `DD/MM/YYYY` format.
3. Specify the borrowing period in days.
4. Enter the actual submission date.
5. The program calculates the due date.
6. It compares the submission date with the due date.
7. If the book is returned late, the program calculates the overdue days and total fine.
8. The complete book and submission details are displayed.

## 💻 Sample Output

```text
----- Library Management -----
Book Name        : Python Basics and Core
Book ID          : PY1010
Issued Date      : 10/10/2026
Period           : 30 Days
Due Date         : 09/11/2026
Submission Date  : 15/11/2026
Status           : Submitted Late
Overdue Days     : 6
Fine Per Day     : ₹ 10
Total Fine       : ₹ 60
```

## 🧮 Fine Calculation

**Formula:**

`Total Fine = Overdue Days × Fine Per Day`

**Example:**

- Due date: 09/11/2026
- Submission date: 15/11/2026
- Overdue days: 6
- Fine per day: ₹10
- **Total fine: ₹60**

If the book is submitted on or before the due date, no fine is charged.

## 🚀 How to Run the Project

### Prerequisites

- Python 3
- Jupyter Notebook or JupyterLab

### Steps

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   ```

2. Navigate to the project directory:

   ```bash
   cd YOUR-REPOSITORY
   ```

3. Open the notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Library Management System.ipynb` and run the cells.

**Note:** Replace `YOUR-USERNAME` and `YOUR-REPOSITORY` with your actual GitHub username and repository name.

## 📂 Project Structure

```text
Library-Management-System/
│
├── Library Management System.ipynb
└── README.md
```

## 📚 Concepts Learned

- Creating classes and objects in Python
- Implementing inheritance using `Book` and `LibraryManagement`
- Using constructors and `super()`
- Working with user input
- Implementing custom date calculations
- Handling leap years and month lengths
- Applying conditional logic
- Calculating overdue fines

## 🔮 Future Enhancements

- Support multiple books and borrowers.
- Maintain a record of issued and returned books.
- Add book availability tracking.
- Store library records using a database.
- Implement search, update, and delete operations.
- Add input validation and a graphical user interface.

## 👨‍💻 Author

**Karthikeyan**

Connect with me on [LinkedIn](https://www.linkedin.com/in/karthikeyans12/) and explore my projects on [GitHub](https://github.com/).

## ⭐ Support

If you find this project useful, consider giving the repository a star!

---

*Built with Python as a hands-on project to strengthen programming and OOP fundamentals.*
