# BankExtention

<div align="center">

<img src="https://github.com/SP-XD/SP-XD/blob/main/images/dev-working_rounded.gif?raw=true" width="40%" />

# 🏦 Bank Extension System
### C++ Console Application | OOP | Clean Design

</div>

---

## 📌 Project Description

**Bank Extension System** is a **console-based banking application** developed using **C++** and **Object-Oriented Programming (OOP)** principles.

The project simulates real-world banking operations while focusing on:
- Clean architecture
- Separation of concerns
- Reusable utility libraries
- Strong programming fundamentals

This project was implemented as part of my structured learning journey in backend development.

---

## 🎯 Project Goals

- Apply **OOP concepts** in a real project
- Build reusable and maintainable code
- Practice backend-oriented problem solving
- Simulate real banking workflows

---

## 🧠 System Flow

1. Application starts from `main.cpp`
2. Login screen is displayed
3. User authentication is validated
4. System runs continuously until user exits

👤 Core Entities
🔹 clsPerson
Base class representing a person in the system.

Responsibilities:

First Name

Last Name

Email

Phone

Full Name generation

Used as a parent class for system users and clients.

🔹 clsUser (Current User Context)
clsUser CurrentUser = clsUser::Find("", "");
Stores the currently logged-in user

Accessible across the system

Enables permission-based operations

🏦 Clients Management Module
Supports full CRUD operations:

➕ Add Client

✏️ Update Client

❌ Delete Client

🔍 Find Client

📄 List All Clients

Designed to simulate real banking customer management.

📚 Custom Utility Libraries
All libraries are implemented from scratch and designed to be reusable.

📅 clsDate Library
Features:

Date validation

Leap year detection

Date comparison

Add / subtract days, months, years

Business days & vacation calculations

Monthly & yearly calendar printing

System date & time handling

✔ Independent
✔ Reusable
✔ Clean API

🔤 clsString Library
String manipulation utilities:

Case conversion

Split & Join

Trim (Left / Right / Full)

Word counting

Reverse words

Replace text

Remove punctuations

Vowel counting

✅ clsInputValidate
Centralized input validation:

Numeric range validation

Safe input handling

Date validation

Prevents invalid runtime input

🎲 clsUtil Library
General-purpose utilities:

Random numbers & strings

Password & key generation

Array shuffling

Swap functions (int, double, string, char, bool, Date)

🧱 Programming Concepts Applied
Object-Oriented Programming (OOP)

Encapsulation & Abstraction

Static vs Non-Static Methods

Utility & Helper Classes

Global State Management

Enums & Structs

Console-Based UI

Clean Code Principles

🛠️ Technologies & Tools
🔹 Languages & Paradigms
C++

Object-Oriented Programming

🔹 Tools
Visual Studio Community

Git & GitHub
