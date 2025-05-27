# 📚 Library Management System (C++)

A high-performance console application to manage book records, user roles, and transactions using **Object-Oriented Programming** principles and file handling.

## 🛠️ Tech Stack
- **Language**: C++ (STL)
- **Paradigms**: OOP (Classes, Inheritance, Polymorphism)
- **Storage**: File Handling (Text/CSV)
- **Tools**: Git, GNU Compiler (g++)

## ✨ Key Features
- **User Roles**: 
  - Librarian (Add/Delete books, View all transactions)
  - Student (Search/Borrow/Return books)
- **Book Management**:
  - Add new books with title/author/ISBN
  - Search books in O(1) time using hashing
  - Track availability status
- **Transaction System**:
  - Borrow/return with due dates
  - Fine calculation for late returns
- **Data Security**:
  - Input validation
  - Exception handling

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mounika-46/library-management-cpp.git
##compile and run
 g++ main.cpp -o library && ./library


##System Design
+-------------------+       +-------------------+       +-------------------+
|     Book Class    |       |    User Class     |       | Transaction Class |
|-------------------|       |-------------------|       |-------------------|
| - title: string   |<>-----| - name: string    |<>-----| - bookID: int     |
| - author: string  |       | - ID: int         |       | - userID: int     |
| - ISBN: string    |       | - role: enum      |       | - issueDate: date |
| - isAvailable: bool|       +-------------------+       | - returnDate: date|
+-------------------+                                   +-------------------+
