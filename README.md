# 💳 Bank Management System – C++ Console Project

This repository contains a simple Bank Client Management System built in C++, as part of:

> 🔷 Course 07 - Algorithms and Problem Solving Level 3  
> 🎓 From [ProgrammingAdvices.com](https://www.programmingadvices.com) by *Mohammed Abu-Hadhoud*

---

## 📌 Description

This project simulates basic banking operations through a console interface. It allows managing clients and storing their data in a text file. The program uses structured programming techniques to perform CRUD operations on client records.

### 🔧 Features

- 📂 Load and display all clients
- ➕ Add a new client
- 📝 Update existing client information
- ❌ Delete a client
- 🔍 Search for a client by account number
- 💾 Store client data in Clients.txt using custom serialization
- 🧠 Uses core concepts:
  - struct
  - vector
  - fstream
  - enum
  - string manipulation
  - input validation

---

## 🧱 Data Structure

`cpp
struct sClient {
    string AccountNumber;
    string PinCode;
    string Name;
    string Phone;
    double AccountBalance;
    bool MarkForDelete = false;
};

The client data is saved in Clients.txt in the format:

AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance


---

📋 Menu Options

[1] Show Client List
[2] Add New Client
[3] Delete Client
[4] Update Client Info
[5] Find Client
[6] Exit


---

📂 File Structure

BankProject/
│
├── main.cpp          → Main source code
├── Clients.txt       → File-based database
└── README.md         → Project documentation


---

▶️ How to Run

1. Open the project in Visual Studio or any C++ compiler.


2. Build and run main.cpp.


3. Follow the on-screen instructions from the console menu.




---

🧠 What I Learned

Dealing with text files (fstream) as data storage

Parsing and writing structured data to files

Organizing code using struct, functions, and enums

Simulating real-world applications using C++

Improving debugging and problem-solving skills



---

📚 Course Information

Course: 07-Algorithms and Problem Solving Level 3

Instructor: Mohammed Abu-Hadhoud

Platform: ProgrammingAdvices.com

YouTube Channel: Programming Advices



---

🙋‍♂️ Author

Abed-El-Hassib Lakhdari
Student in Computer Science | Problem Solver | Passionate about Programming
