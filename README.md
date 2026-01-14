# 🏦 Bank Management System

A **Java Swing based Bank Management System** that simulates basic banking operations such as user registration, login, deposit, withdrawal, and balance enquiry.  
The project uses **MySQL** as the backend database and **JDBC** for database connectivity.

---

## 📌 Features

- Multi-step User Signup (3 Pages)
- Secure Login using Card Number and PIN
- Deposit Money
- Withdraw Money
- Balance Enquiry
- Transaction History
- Simple and user-friendly GUI using Java Swing

---

## 🛠️ Technologies Used

- **Java** (Core Java, Swing, AWT)
- **MySQL** (Database)
- **JDBC** (Database Connectivity)
- **IntelliJ IDEA** (IDE)
- **Git & GitHub** (Version Control)

---

## 🗂️ Project Structure

Bank-Management-System
│
├── src/
│ └── bank/management/system/
│ ├── Login.java
│ ├── Signup.java
│ ├── Signup2.java
│ ├── Signup3.java
│ ├── Deposit.java
│ ├── Withdraw.java
│ ├── BalanceEnquiry.java
│ ├── main_Class.java
│ └── Connn.java
│
├── icon/
│ └── (images used in UI)
│
├── .gitignore
└── README.md


---

## 🧩 Database Design

### Tables Used
- `signup`
- `signuptwo`
- `signupthree`
- `login`
- `bank`

### Example: `bank` Table
```sql
CREATE TABLE bank (
    pin VARCHAR(10),
    date DATETIME,
    type VARCHAR(20),
    amount VARCHAR(20)
);
