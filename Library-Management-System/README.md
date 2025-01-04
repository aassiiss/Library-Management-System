# Library Management System in C++
# Project Overview:

The Library Management System is a console-based application built in C++ designed to facilitate efficient management of library resources for both administrators and students. Students can register or log in to access library information and services. Administrators are empowered to manage library books and student accounts, including tasks such as adding, editing, and viewing book records, issuing books, and handling fines. The system provides a streamlined approach to managing library operations and student interactions.

# Key Features:
The system includes a password-protected login feature for both administrators and students.

# Admin Functions:
Admin Functions:

1. Add a Book: Administrators can add new books to the library's collection.
2. Edit Book Details: Administrators can update the title and author information of a book by referencing its ISBN number.
3. View Book Status: Administrators can check the list of books along with their availability status in the library.
4. View Enrolled Students: Administrators can access a sorted list of registered students based on their roll numbers.
5. View Student Balance: Administrators can view the account balance of individual students.

# Student Functions:

Create an Account: Students can register by providing their roll number, name, and an initial deposit.
View Balance: Students can check the current balance in their account.
Deposit Amount: Students can add money to their account.
Issue a Book: Students can borrow books from the library's available collection.


Account Management:

The system accommodates up to 20 students.
Students pay $20 as an account opening fee and $30 as a security deposit.
Books can be borrowed for $2 for a 10-day period, with fines applicable for late returns based on predefined rules.


Data Storage:

The system uses 2D arrays to maintain information about students and books.
Initially, the library holds 15 books.
Each student account stores details such as roll number, balance, and first name.






# Implementation Overview:
This application is developed in C++ using foundational programming concepts, avoiding the use of classes, pointers, or structures. It leverages 2D arrays, functions, loops, conditional statements (if-else), and switch-case constructs to deliver the desired functionality. The main() function serves as the core, managing user input, displaying options, and invoking the appropriate functions based on the user's choices. The program operates in a loop, allowing users to interact continuously until they choose to exit.

This project is ideal for students who have completed a Programming Fundamentals course or lab and wish to showcase their skills in C++ programming without delving into advanced topics like classes or pointers. It lays a strong foundation for future exploration and growth in C++ programming and software development.