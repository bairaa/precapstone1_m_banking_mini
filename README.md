# 💳 Simple M-Banking System (CLI)

A simple command-line based mobile banking simulation built with Python.

---

## 📌 Overview

This project is a basic banking system that simulates core mobile banking features through a text-based interface.

Users can perform financial transactions and view their transaction history directly from the terminal.

The system demonstrates fundamental programming concepts such as:

- Conditional logic
- Loops
- Functions
- Data structures
- Role handling (if implemented)

---

## ⚙ Features

- 🔐 Secure PIN input (masked input)
- 💰 Balance checking
- 📥 Deposit
- 📤 Withdrawal
- 🔁 Transfer (with transaction fee)
- 📜 Transaction history (sorted: newest → oldest)
- 📊 Formatted transaction table using `tabulate`

---

## 🧾 Transaction History

- Displayed in a formatted table
- Sorted from **newest to oldest**
- Includes:
  - Transaction number
  - Transaction type
  - Amount
  - Remaining balance
  - Transfer fee (if applicable)

---

## 🛠 Built With

- Python 3
- Standard libraries
- `tabulate` (for formatted tables)
- `pwinput` (for masked PIN input)
