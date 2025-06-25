# 💰 Transaction Tracker – Flask CRUD App

A lightweight web application built using Python’s **Flask** framework that allows users to perform full CRUD (Create, Read, Update, Delete) operations on financial transactions. This app is perfect for learning Flask basics, routing, templating, and working with dynamic data using in-memory Python structures.

---

## 📦 Features

- 🔍 **Read**: View a list of all transactions
- ➕ **Create**: Add a new transaction with date and amount
- ✏️ **Update**: Edit existing transactions
- ❌ **Delete**: Remove transactions by ID
- 🧠 **Simple In-Memory Data**: Uses a Python list to store transaction data (no database needed)

---

## 🛠️ Technologies Used

- Python 3
- Flask (routing, request handling, templates)
- HTML5 + Bootstrap (UI forms)
- VS Code or any Python IDE

---

## 🧪 Sample Transaction Data (In-Memory)

```python
transactions = [
    {'id': 1, 'date': '2023-06-01', 'amount': 100},
    {'id': 2, 'date': '2023-06-02', 'amount': -200},
    {'id': 3, 'date': '2023-06-03', 'amount': 300}
]
