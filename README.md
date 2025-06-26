# 🏟️ Ticket Booking System – Python Design Patterns Project

This is a console-based ticket booking application developed as part of a **Software Design & Architecture** course. It uses four major design patterns to structure a real-world simulation.

---

## 🔧 Features

- Book football match tickets (Standard or VIP)
- Input validation for names, emails, and phone numbers
- Choose teams, stadium levels, and payment method
- Apply group or student discounts dynamically
- Sends SMS and Email confirmation on booking
- Multiple bookings supported in one session

---

## 🧩 Design Patterns Implemented

| Pattern        | Purpose                                                                 |
|----------------|-------------------------------------------------------------------------|
| **Observer**   | Notifies via email & SMS after booking (`EmailNotifier`, `SMSNotifier`) |
| **Strategy**   | Selects payment method at runtime (`VodafoneCashPayment`, `CreditCard`) |
| **Decorator**  | Applies dynamic discounts (`GroupDiscountDecorator`, `StudentDiscount`) |
| **Singleton**  | Ensures one central ticket manager instance (`TicketManager`)           |

---

## ▶️ How to Run

### 1. If you're using Python locally:
```bash
cd ticket-booking-patterns
python src/main.py
