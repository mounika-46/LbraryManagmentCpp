# 📚 Library Management System (C++)


#System Architecture
┌───────────────────────┐       ┌───────────────────────┐
│      Book Class       │       │      User Class       │
├───────────────────────┤       ├───────────────────────┤
│ - title: string       │───┐   │ - name: string        │
│ - author: string      │   │   │ - ID: int            │
│ - ISBN: string        │   └──▶│ - borrowedBooks: list│
│ - isAvailable: bool   │       │ - role: enum         │
└───────────────────────┘       └───────────────────────┘
          ▲
          │
┌───────────────────────┐
│   Transaction Class   │
├───────────────────────┤
│ - bookID: int         │
│ - userID: int         │
│ - issueDate: date     │
│ - returnDate: date    │
└───────────────────────┘

A robust console application for managing library operations using **Object-Oriented Programming** principles in C++.

## ✨ Features
- **User Management**
  - 👩💼 Librarian: Add/remove books, view transactions
  - 👩🎓 Student: Search/borrow/return books
- **Book Operations**
  - 📖 Add new books with title/author/ISBN
  - 🔍 Search books in O(1) time using hashing
  - 📊 Track availability status
- **Transaction System**
  - ⏳ Borrow/return with due dates
  - 💰 Automatic fine calculation
- **Data Security**
  - 🔒 Input validation
  - 🛡️ Exception handling

## 🚀 Getting Started

### Prerequisites
- GNU C++ Compiler (g++)
- Git (optional)


