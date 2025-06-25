# Tip-calculator

# 💸 Tip Calculator

A sleek, responsive **Tip Calculator Web App** built with **HTML**, **CSS**, and **JavaScript** — perfect for quickly calculating how much each person owes when splitting a bill.

---

## 🔍 Overview

Easily calculate tips and split bills with friends! This lightweight app lets users:

- 💰 Enter the bill amount  
- 🎯 Set a custom tip percentage  
- 👥 Adjust the number of people splitting the bill  
- 📊 Instantly see the **total per person**

Everything updates **live** — no buttons, no delays!

---

## 🚀 Features

✅ **Real-time Calculation**  
✅ **Live DOM Updates** with JavaScript  
✅ **Beautiful UI** with custom fonts and modern layout  
✅ **Fully Responsive** (Mobile-friendly)  
✅ **Input Validation** with error handling (e.g., minimum 1 person)

---

## 🛠️ Tech Stack
|----------|---------|
| Technology | Usage |
| HTML5      | Markup structure |
| CSS3       | Styling and layout |
| JavaScript | Dynamic functionality |
| Google Fonts | Custom font for modern design |


## ⚙️ How It Works

These 3 core functions handle all the logic:

| Function | Purpose |
|----------|---------|
| `calculateBill()` | Calculates and updates the total per person |
| `increasePeople()` | Increments the number of people and recalculates |
| `decreasePeople()` | Decreases the number of people (min 1) and recalculates |

### 📌 Key Elements Accessed via DOM:

| ID | Purpose |
|----|---------|
| `billTotalInput` | User input for bill amount |
| `tipInput` | User input for tip % |
| `numberOfPeople` | Display and logic for how many people split the bill |
| `perPersonTotal` | Output of total per person |

---

## 🧠 Logic Summary

1. **User inputs** bill and tip percentage.
2. App **calculates**:
   - Total tip
   - Grand total (bill + tip)
   - Amount each person should pay
3. Dynamic updates using **JavaScript DOM manipulation**.



