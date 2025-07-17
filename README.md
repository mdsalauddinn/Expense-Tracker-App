# 📊 Simple Expense Tracker App

This is a beginner-friendly Android app built using **Java** and **XML layouts**. It helps users keep track of their daily expenses, including **amount**, **category**, and an optional **description**.

---

## ✨ Features

- 🏁 **Splash screen** with animation  
- ➕ Add new expense with amount, category, and optional description  
- 📜 Auto-scrollable list to view all added expenses  
- 🔁 Reset button to clear all expenses  
- 🎯 Simple UI using `LinearLayout`, `RelativeLayout`, and `ScrollView`  
- ✅ No external storage or database — purely memory-based (resets on app close)

---

### 📁 Project Structure

```bash
com.example.expenseTracker/ ├── MainActivity.java # Displays all added expenses ├── addExpense.java # Activity to input new expense details ├── screen_splash.java # Splash screen logic ├── res/ ├── layout/ ├── activity_main.xml ├── activity_add_expense.xml ├── screen_splash.xml ├── drawable/ ├── values/ ├── strings.xml ├── anim/ └── transition_x.xml # Entry animation

---

## 🧠 Concepts Used

- `startActivityForResult()` with `ActivityResultLauncher`
- Dynamic `TextView` creation inside `LinearLayout`
- UI components: `ScrollView`, `RelativeLayout`, `Button`, `EditText`, `TextView`
- Conditional layout building using Java
- Simple animations (`AnimationUtils`)
- String formatting and input validation

---

## 📦 How to Run

1. Clone this repo or copy the source files
2. Open in **Android Studio**
3. Build & Run on emulator or real device (API 21+ recommended)

---

## 💡 Future Improvements

- 🔄 Store expenses using SQLite or Room to persist data
- 📅 Group expenses by date
- 📈 Show graphs and totals
- 🔍 Add filters and search functionality

---

## 🙋‍♂️ Developed By

**Md Salauddin**  
1st Year CSE Student  
[LinkedIn](https://www.linkedin.com/in/mdsalauddinn/)

---

## 📜 License

This project is for educational purposes. Feel free to use, share, or modify with credit.

