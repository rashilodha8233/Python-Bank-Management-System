# 🏦 Python Bank Account Management System

A comprehensive Python-based simulation of a bank account management system built for the Data Analytics Mentorship Program. The project incorporates core Python concepts such as data structures, functions, file handling, modules, error handling, and numerical analysis using NumPy.

---

## 📌 Project Overview
This project simulates a real-world bank account management system allowing users to create accounts, perform secured financial transactions, track transaction histories, and analyze summary statistics using NumPy. Account data is persistently stored using Python's `pickle` library.

---

## ✨ Key Features

### 1. Account Management
* **Account Creation:** Generates a unique 5-digit auto-generated account number.
* **Account Types:** Supports both `Savings` and `Current` accounts.
* **Authentication:** Password-protected access for individual account security.
* **Account Details:** View account holder name, account type, account number, and current balance.

### 2. Financial Transactions
* **Deposit:** Deposit funds with positive amount validation.
* **Withdrawal:** Withdraw funds with automated insufficient balance verification.
* **Fund Transfer:** Transfer money safely between two existing accounts with real-time balance updates.

### 3. Data Persistence (File Handling)
* Uses Python’s `pickle` library to load data on startup and save all account/transaction states when exiting the system.

### 4. NumPy Analytics & Reporting
* Detailed transaction history logs showing Date/Time, Transaction Type, and Amount.
* **NumPy Summary Statistics:**
  * Total Deposits Amount (`np.sum`)
  * Total Withdrawals Amount (`np.sum`)
  * Average Transaction Amount (`np.mean`)

### 5. Robust Error Handling
* Validates positive monetary inputs.
* Handles non-existent accounts, incorrect passwords, and invalid menu choices smoothly without crashing.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Processing & Analytics:** NumPy
* **Data Persistence:** `pickle`, `os`
* **Utilities:** `random`, `datetime`
* **Environment:** Google Colab / Jupyter Notebook
