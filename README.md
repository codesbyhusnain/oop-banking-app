# 🏦 OOP Banking Application

A **console-based banking system** built in **Python**, demonstrating core **Object-Oriented Programming (OOP)** principles. This project models real-world banking features such as account creation, deposits, withdrawals, transfers, interest handling, and transaction history — all through a terminal-based interface.

---

## ✅ Features

- Create **Checking** and **Savings** accounts  
- Perform **deposits**, **withdrawals**, and **transfers**  
- View detailed **account summaries** and **transaction history**  
- Enforce **monthly withdrawal limits** for savings accounts  
- Apply **monthly interest** to savings accounts  
- Display **bank-wide statistics** for accounts and balances  
- Custom **exceptions** for better error handling  
- Fully **menu-driven CLI** interface for ease of use  

---

## 🧠 OOP Concepts Used

| Concept         | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| **Encapsulation** | Account data is protected via private attributes and public getters/setters |
| **Abstraction**   | `Account` is an abstract base class that defines shared functionality       |
| **Inheritance**   | `CheckingAccount` and `SavingsAccount` inherit from the `Account` class     |
| **Polymorphism**  | Methods like `withdraw()` and `get_account_summary()` behave differently by account type |

---
## ▶️ Getting Started

### Requirements
- Python 3.7 or higher

### Run the Application

# Clone the repository
git clone https://github.com/codesbyhusnain/oop-banking-app.git

# Navigate into the project directory
cd oop-banking-app

# Run the app
python banking_app.py

