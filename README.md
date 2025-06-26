# 🎟️ Ticket Booking System – Design Patterns Project (Python)

This is a command-line ticket booking system created as part of a **Software Design and Architecture** course. It simulates a real-world scenario using multiple design patterns to ensure modular, maintainable, and extensible code.

---

## 💡 Features

- ✅ Validates user name, email, and phone number
- 🎟️ Choose between Standard and VIP tickets
- 🏟️ Pick team and stadium level
- 💳 Select payment method (Vodafone Cash or Credit Card)
- 🎓 Applies group or student discounts automatically
- 📩 Sends real-time SMS and email confirmations (simulated via console)
- 📋 Displays all booked tickets at the end

---

## 🧩 Design Patterns Implemented

| Pattern        | Role |
|----------------|------|
| **Observer**   | Sends email and SMS notifications after a ticket is booked |
| **Strategy**   | Enables flexible selection of payment methods |
| **Decorator**  | Applies dynamic discounts (e.g., student or group discounts) |
| **Singleton**  | Ensures one centralized ticket management system instance |

---

## 🛠️ How to Run

### 1. Make sure Python 3 is installed.

### 2. Run the program:
```bash
python main.py
