# 🏦 Bank Account Management System

A Java-based console application that manages customer bank accounts by supporting **Account Creation**, **Deposit**, **Withdrawal**, **Fund Transfer**, and **Transaction History**. The system uses **HashMap** for efficient account storage and **LinkedList** for maintaining a transaction ledger for each account.

---

# 📌 Project Information

| Field | Detail |
|--------|--------|
| Register Number | 711524BEE034 |
| Student Name | NITIN G |
| Project Title | Bank Account Management System |
| Domain | Low-Level Design (LLD), built on DSA fundamentals |
| Language | Java |
| Core Concepts | HashMap, LinkedList, Object-Oriented Programming (OOP), Java Collections Framework |

---

# 📖 Overview

The Bank Account Management System is designed to perform basic banking operations through a simple menu-driven console application. It enables users to create bank accounts, deposit and withdraw money, transfer funds between accounts, and maintain transaction history.

The project is implemented using Java and demonstrates Low-Level Design (LLD) principles with Data Structures and Algorithms.

This project includes:

- Account Creation
- Deposit Money
- Withdraw Money
- Fund Transfer
- Account Details
- Transaction History
- HashMap-based Account Storage
- LinkedList-based Transaction Ledger

The system follows Object-Oriented Programming concepts such as:

- Encapsulation
- Abstraction
- Polymorphism
- Composition

---

# 🎯 Objectives

- Create and manage bank accounts.
- Perform deposit and withdrawal operations.
- Transfer money between accounts.
- Maintain transaction history.
- Store account information efficiently using HashMap.
- Demonstrate Java Collection Framework usage.
- Apply Low-Level Design principles.

---

# 🏗️ System Design

## Class Diagram

```
                     BankAccount
                          │
        ┌─────────────────┼─────────────────┐
        │                 │                 │
    Deposit()        Withdraw()       Transfer()
        │                 │                 │
        └─────────────────┼─────────────────┘
                          │
                 Transaction Ledger
                    (LinkedList)
                          │
                 BankManagementSystem
                          │
                         Main
```

---

# 📚 Class Responsibilities

## BankAccount

Stores account information.

### Attributes

- accountNumber
- holderName
- balance
- transactionLedger

### Methods

- deposit()
- withdraw()
- transfer()
- displayDetails()
- showLedger()

---

## BankManagementSystem

Handles the business logic.

Uses

- HashMap<String, BankAccount>

Functions

- createAccount()
- depositMoney()
- withdrawMoney()
- transferMoney()
- displayAccount()
- displayTransactionHistory()

---

# ⚙️ Algorithm

## Account Creation

1. Read Account Details.
2. Create BankAccount Object.
3. Store Account in HashMap.
4. Display Success Message.

### Time Complexity

O(1)

---

## Deposit

1. Read Account Number.
2. Search Account.
3. Update Balance.
4. Record Transaction in LinkedList.

### Time Complexity

O(1)

---

## Withdrawal

1. Read Account Number.
2. Verify Balance.
3. Deduct Amount.
4. Record Transaction.

### Time Complexity

O(1)

---

## Fund Transfer

1. Read Sender Account.
2. Read Receiver Account.
3. Verify Accounts.
4. Check Balance.
5. Transfer Amount.
6. Update Both Ledgers.

### Time Complexity

O(1)

---

## View Transaction History

1. Read Account Number.
2. Access Transaction Ledger.
3. Display All Transactions.

### Time Complexity

O(n)

---

# 🧠 Data Structures Used

## HashMap

Purpose

- Account Storage
- Fast Searching
- Account Retrieval

Operations

Insert

O(1)

Search

O(1)

Delete

O(1)

---

## LinkedList

Purpose

- Transaction History
- Ledger Maintenance
- Ordered Transaction Storage

Operations

Insertion

O(1)

Traversal

O(n)

---

# 💻 Technologies Used

- Java
- Java Collections Framework
- HashMap
- LinkedList
- OOP
- VS Code
- Git
- GitHub

---

# 🚀 Build and Run

Compile

```bash
javac BankAccountManagementSystem.java
```

Run

```bash
java BankAccountManagementSystem
```

---

# 📂 Project Structure

```
Bank-Account-Management-System

├── docs
│   ├── ClassDiagram.png
│   ├── java.code
└── README.md
```

---

# 🏆 Features

- Account Creation
- Deposit Money
- Withdraw Money
- Fund Transfer
- Transaction History
- Account Details
- HashMap Storage
- LinkedList Ledger
- Java OOP Design
- Low-Level Design

---

# 📈 Future Enhancements

- User Login Authentication
- PIN Security
- Database Integration (MySQL)
- GUI using Java Swing
- Interest Calculation
- Online Banking Features
- Monthly Statement Generation
- Account Update & Deletion

---

# 🧠 Key Concepts Demonstrated

- Object-Oriented Programming
- Encapsulation
- Abstraction
- Polymorphism
- Composition
- HashMap
- LinkedList
- Java Collections Framework
- Low-Level Design

---

# 🙋 Author

**NITIN G**

**Register Number:** 711524BEE034

**Department:** B.E. Electrical and Electronics Engineering (EEE)

**College:** KIT – Kalaignarkarunanidhi Institute of Technology

---

# 📄 License

This project was developed as part of the **Low-Level Design (LLD) Mini Project** coursework. It demonstrates the implementation of **HashMap** and **LinkedList** data structures using **Java Object-Oriented Programming** principles to build an efficient **Bank Account Management System**.
