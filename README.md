# 🏧 ATM Simulator System

A fully functional ATM (Automated Teller Machine) simulator built with Java Swing and MySQL, featuring a complete desktop GUI for banking operations.

---

## ✨ Features

- **User Authentication** — Secure login with Card Number + PIN
- **Multi-step Registration** — Complete account signup flow
- **Banking Operations:**
  - Deposit Money
  - Cash Withdrawal
  - Fast Cash (preset amounts)
  - Balance Inquiry
  - Mini Statement (transaction history)
  - PIN Management
- **Transaction Tracking** — Maintains full history of all transactions

---

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Language | Java |
| GUI Framework | Java Swing (AWT/Swing) |
| Database | MySQL (bankmanagementsystem) |
| JDBC Driver | MySQL Connector/J v9.6.0 |
| Additional Library | jCalendar (date/calendar handling) |
| Build System | Apache Ant (NetBeans project) |

---

## ⚙️ Prerequisites

- Java Development Kit (JDK) installed
- MySQL Server running
- A MySQL database named bankmanagementsystem created
- NetBeans IDE (recommended)

---

## 🚀 How to Run

### Option 1 — Via NetBeans IDE (Recommended)
1. Open NetBeans IDE
2. Click File then Open Project
3. Navigate to the project folder and open it
4. Click Build and Run (or press F6)

### Option 2 — Manual Setup
1. Make sure MySQL is running
2. Create the database: CREATE DATABASE bankmanagementsystem;
3. Update database credentials in Conn.java with your username and password
4. Build and run the project

---

## 📁 Project Structure

ASimulatorSystem/
- Login.java - User authentication
- Signup.java - Registration Step 1
- Signup2.java - Registration Step 2
- Signup3.java - Registration Step 3
- Deposit.java - Deposit operation
- Withdrawl.java - Withdrawal operation
- FastCash.java - Fast cash presets
- BalanceEquiry.java - Balance inquiry
- MiniStatement.java - Transaction history
- Pin.java - PIN management
- Transactions.java - Transaction tracking
- Conn.java - Database connection
- Practice.java - Main entry point
- icons/ - UI assets

---

## ⚠️ Important Note

Before running, update the database password in Conn.java to match your local MySQL credentials. Do not share your credentials publicly.
