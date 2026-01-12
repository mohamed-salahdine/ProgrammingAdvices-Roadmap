# 11 - OOP as it Should Be (Applications) 🏦

**"Building the Bank System: OOP in Action."**

This directory contains a fully functional **Console Banking System**. It serves as the capstone project for the Object-Oriented Programming module, applying concepts like Encapsulation and modular design to build a real-world application.

## 🚀 Project Overview: Bank System
A robust console application allowing users to manage bank clients and transactions. This project bridges the gap between ephemeral code (that runs and disappears) and persistent software (that saves data).

## 🔑 Key Features Implemented
- **CRUD Operations:**
  - **Create:** Add new clients with unique Account Numbers.
  - **Read:** List all clients or search for a specific client.
  - **Update:** Modify client details.
  - **Delete:** Remove clients from the system.
- **Transaction System:** Deposit and Withdraw functionality with balance validation.
- **Data Persistence:**
  - Custom **Serialization/Deserialization** logic to save Client Objects to text files (`Clients.txt`).
  - Loading data from disk into `std::vector<clsClient>` objects upon startup.

## 🏛️ Architecture & Design
- **Separation of Concerns:**
  - **Screen Class:** Handles UI and Menus.
  - **Client Class:** Manages Business Logic and Data Access.
  - **Input Validation Library:** Ensures robust user input.
- **Menu System:** A dynamic main menu driving the application flow.

## 🛠️ Stack
- **Language:** C++
- **Storage:** Text Files (Flat File Database)
- **Concepts:** OOP, Vectors, File Streams (fstream).

---
## 🎓 Verification
[📄 **View Certificate of Completion (PDF)**](../Certificates/11-certificate-of-completion-for-11-oop-as-it-should-be-applications.pdf)