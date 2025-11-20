# Continuous Calculator in C

A simple, interactive, and user-friendly **Continuous Calculator** built using the C programming language. This program performs arithmetic operations repeatedly without restarting, making it ideal for students learning control flow, switch-case logic, and basic error handling in C.

---

## 📌 Overview

This calculator allows users to:

* Enter an initial number
* Perform continuous operations (+, –, ×, ÷)
* See updated results after every step
* Clear the current calculation anytime
* Quit the program whenever needed

The program is designed to mimic the behavior of a basic handheld calculator, focusing on smooth user interaction and logical structure.

---

## 🧠 Features

### ✔ Continuous Operation

Perform multiple arithmetic calculations in sequence without resetting.

### ✔ Clear Function (`C`)

Resets the display to **0** and restarts the calculation.

### ✔ Quit Option (`Q`)

Gracefully exits the program with a closing message.

### ✔ Error Handling

* Prevents division by zero
* Detects invalid operators
* Prompts the user to retry without crashing

### ✔ Clean Display

Shows the result after every valid operation in an easy-to-read format.

---

## 🛠 Technologies Used

* **Language:** C
* **Compiler:** GCC / Any standard C compiler
* **Concepts Used:**

  * Loops
  * Switch–case
  * Input validation
  * Arithmetic operations
  * Control flow management

---

## 📂 How to Compile and Run

### **1. Compile**

```bash
gcc calculator.c -o calculator
```

### **2. Run**

```bash
./calculator
```

---

## 🎯 Example Interaction

```
------ CONTINUOUS CALCULATOR ------
Display: 0

Enter a number: 10
Enter operator (+, -, *, /, C to clear, Q to quit): +
Enter next number: 5
Display: 15.00

Enter operator: *
Enter next number: 2
Display: 30.00
```

---

## 📘 Learning Outcomes

By exploring this program, users will understand:

* How to build interactive console applications
* Handling continuous user input
* Applying switch-case for decision making
* Implementing logic for persistent calculations
* Managing runtime errors gracefully

---

## 🤝 Contributions

Feel free to suggest improvements, open issues, or submit pull requests to enhance the calculator’s functionality or interface.

---

## 📜 License

This project is open-source. You may modify and use it for learning or development purposes.

---
