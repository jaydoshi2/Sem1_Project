# 📚 LJ Voting System - Welcome to LJ Voting Center! 

## 🚀 Overview

Welcome to the **LJ Voting System**! This Java program is designed for students of the **CEIT** department to cast their votes for their favorite teachers and store the information in organized text files. This project serves as a **fun way** to explore:

- **Java I/O operations** 📝
- **Object-Oriented Programming (OOP) principles** 🧑‍💻
- **Class & Division Handling** in Java 🎓

## 🛠 Key Features

- 🏫 **Class Selection:** Students can enter their class number (1 to 6) and division (A or B).
- 👩‍🏫 **Teacher Voting:** Students can select their favorite teachers by subject (Java or Math).
- 📁 **File I/O:** The program stores student details (name and roll number) into corresponding text files (`1A.txt`, `2B.txt`, etc.).
- 🗳️ **Thank You for Voting!** Displays a friendly message after each vote is cast.

## 📚 Learning Objectives

This project helps you:
- **Learn File I/O in Java**: 📂 Write and read data to/from files using `FileWriter` and `Scanner`. Understand how to store data persistently.
- **Practice OOP Concepts**: 🧑‍💻 Learn about classes, objects, and inner classes (`Students_of_CEIT`) to structure code effectively.
- **Enhance User Interaction**: 💻 Use `Scanner` to take input and manage user-driven functionality with proper formatting and error handling.
- **Condition Handling**: 🚦 Handle multiple conditions with `if`-`else` for class, division, and subject selections.
  
## 🖥️ How It Works

1. **Welcome Screen**: The user is greeted with a welcome message and prompted to enter their class number (1-6) and division (A/B).
   - Example: "Enter your class number (1/2/3/4/5/6)" and "Enter your class division (A/B)"
   
2. **Voting Screen**: Students vote for their favorite teacher based on the selected subject (Java/Math).
   - For Java, teachers include **Komal Langalia, Uma Joshi, Milan Patel**, etc.
   - For Math, teachers include **Dinesh Mehbubani, Hena Shah**, etc.
   
3. **Data Storage**: The student's details (name, roll number) are stored in a text file corresponding to their class and division (e.g., `1A.txt`).

4. **Thank You Message**: After the vote is cast, the system displays a gratitude message to the voter. 🎉


## 💡 Key Java Concepts Used

- **Classes & Objects**: `Students_of_CEIT` represents the main class. Inner classes like `A1`, `A2`, etc., handle individual voting processes.
- **File I/O**: We use `FileWriter` for writing student data into text files and `Scanner` for reading user input.
- **Condition Handling**: `if-else` blocks handle class and division-specific logic, and teacher voting is based on subjects like Java or Math.

