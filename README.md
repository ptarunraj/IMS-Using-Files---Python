# Inventory Management System (Python)

## Overview

This is a simple command-line based Inventory Management System built using Python.
It simulates a basic retail transaction system by reading inventory data from a file, processing purchases, and updating records.

---

## Features

* 📄 Reads inventory from a text file
* 🧾 Generates billing details with timestamp
* 📉 Updates stock after purchase
* ⚠️ Handles insufficient inventory scenarios
* 💾 Stores transaction history in a sales file

---

## Technologies Used

* Python 3
* File Handling (Read/Write/Append)
* Basic Data Structures (Lists, Strings)

---

## Project Structure

```
Inventory.txt   # Stores product details
Sales.txt       # Stores transaction history
main.py         # Main program
```

---

## How It Works

1. Load inventory data from file
2. Accept user details:

   * Name
   * Phone number
   * Email
   * Product ID
   * Quantity
3. Check product availability:

   * If available → process purchase
   * If limited → offer partial purchase
4. Generate bill
5. Update inventory file
6. Save transaction in `Sales.txt`

---

## Edge Cases Handled

* Empty lines in inventory file (`['']` issue due to newline characters)
* Insufficient stock handling
* Safe list updates after processing

---

## 📸 Sample Output

```
-------------------- TR STORES --------------------
Date/Time      : Mon Mar 23 12:00:00 2026
Product Name   : Pen
Price          : 10
Quantity       : 2
--------------------------------------------------
Billing Amount : 20
--------------------------------------------------
```

---

## Future Enhancements

* ✅ Input validation (email, phone number)
* 🖥️ GUI using Tkinter / Web app using Flask
* 🗄️ Database integration (SQLite/MySQL)
* 📊 Sales analytics dashboard
* 🔐 Authentication system for admin/users

---

## Learning Outcomes

* Practical understanding of file-based data storage
* Handling real-world edge cases in data processing
* Writing structured and maintainable Python scripts

---
s or feedback, feel free to connect.
