# 📘 Student Grade Calculator (Python)

## 📌 Project Overview
The **Student Grade Calculator** is a beginner-friendly Python program that takes a student's name and marks as input and assigns a grade based on predefined grading rules.  
It also displays encouraging messages for students and handles invalid inputs gracefully.

This project is part of **Week 2: Making Decisions & Repeating Tasks in Python**.

---

## 🎯 Objectives
- Understand decision-making using `if-elif-else`
- Practice loops using `while`
- Learn how to create and use functions
- Implement input validation and error handling
- Build confidence with real-life programming scenarios

---

## 🛠️ Technologies Used
- **Programming Language:** Python 3
- **Concepts Used:**
  - if–elif–else statements
  - while loop
  - functions
  - input validation
  - basic error handling (`try-except`)

---

## 📊 Grading System
| Marks Range | Grade |
|------------|-------|
| 90 – 100 | A |
| 75 – 89 | B |
| 60 – 74 | C |
| 40 – 59 | D |
| Below 40 | F |

---

## ⚙️ How the Program Works
1. The program asks for the **student name**
2. It repeatedly asks for **marks (0–100)** until valid input is given
3. Based on the marks, the program:
   - Calculates grade using a function
   - Displays grade and an encouraging message
4. Handles invalid inputs like:
   - Marks less than 0
   - Marks greater than 100
   - Non-numeric input

---

## 🧠 Function Used
```python
def calculate_grade(marks):
    ...
