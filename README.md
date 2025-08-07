# 🏦 Banking System - Java + MySQL Project

This is a simple **Banking System Console Application** developed in **Java** using **JDBC (Java Database Connectivity)** to perform basic banking operations like:
- Login with Account Number and Password
- Withdraw Amount
- Deposit Amount
- Check Balance
- Print Receipt with Transaction Details

## 🚀 Features

- User authentication (Account number and password check)
- Balance updates after withdrawal/deposit
- Transaction receipt generation with date
- Option to check balance after each transaction
- Console-based interaction using menu-driven logic

## 💻 Technologies Used

- Java
- JDBC (Java Database Connectivity)
- MySQL (Database)
- Scanner (for user input)
- SimpleDateFormat (for receipt timestamp)

## 🗃️ Database Structure

**Database Name**: `atm`  
**Table Name**: `details`

### Table: `details`
| Column Name | Data Type | Description            |
|-------------|-----------|------------------------|
| name        | VARCHAR   | Account holder's name |
| userId      | INT       | Unique account number |
| password    | INT       | Account password      |
| balance     | INT       | Current balance       |

---

