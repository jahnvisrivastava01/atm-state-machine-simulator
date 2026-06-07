# 🏧 ATM State Machine Simulator

A simple and interactive ATM Simulator built using **Python** and **Object-Oriented Analysis & Design (OOAD)** concepts.

---

## 🚀 Project Overview

This project simulates the working of an ATM machine using a **State Machine Model**.

Users can:

✅ Insert Card
✅ Enter PIN
✅ Withdraw Money
✅ Deposit Money
✅ Check Balance
✅ Exit ATM

The project demonstrates how software moves through different states during execution.

---

## 🎯 OOAD Concepts Used

| Concept            | Implementation        |
| ------------------ | --------------------- |
| Class              | ATM                   |
| Object             | atm                   |
| Encapsulation      | balance, pin, state   |
| State Machine      | ATM state transitions |
| Object Interaction | User ↔ ATM            |

---

## 🔄 ATM State Flow

```text
Idle
 │
 ▼
Card Inserted
 │
 ▼
PIN Verified
 │
 ▼
Transaction
 ├── Withdraw
 ├── Deposit
 ├── Check Balance
 └── Exit
      │
      ▼
     Idle
```

---

## 🖥️ Sample Execution

### Insert Card

```python
atm.insert_card()
```

Output:

```text
Card inserted successfully.
```

---

### Verify PIN

```python
atm.enter_pin("1234")
```

Output:

```text
PIN verified successfully.
```

---

### Withdraw Money

```python
atm.withdraw(1000)
```

Output:

```text
Withdrawn ₹1000
Remaining Balance ₹4000
```

---

### Deposit Money

```python
atm.deposit(500)
```

Output:

```text
Deposited ₹500
Current Balance ₹4500
```

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Object-Oriented Programming (OOP)
* State Machine Modeling

---

## 📚 Learning Outcomes

* Understanding State Diagrams
* Applying OOP Principles
* Modeling Real-World Systems
* Implementing State Transitions
* Object Interaction Design

---

## 🌟 Future Improvements

* Transaction History
* GUI Dashboard
* UML Diagram Generation
* Data Persistence
* Multiple User Accounts

---

## 👩‍💻 Author

**Jahnvi Srivastava**

⭐ If you like this project, consider giving it a star!

