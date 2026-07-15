# Largest of Three Numbers in JavaScript

## 📌 Overview

This project demonstrates how to find the **largest of three numbers** using JavaScript's built-in **`Math.max()`** function.

The program defines a reusable function that accepts three numbers as arguments and returns the largest value. It is a simple beginner-friendly project that introduces functions, parameters, return values, and JavaScript's Math object.

---

## 🚀 Features

* Finds the largest among three numbers
* Uses JavaScript's built-in `Math.max()` function
* Simple and reusable function
* Beginner-friendly implementation
* Displays the result in the browser console

---

## 🛠️ Technologies Used

* JavaScript (ES6+)

---

## 📂 Project Structure

```text
├── largestNumber.js
└── README.md
```

---

## 💻 Source Code

```javascript
function largest(a, b, c) {
    return Math.max(a, b, c);
}

console.log(largest(10, 25, 15));
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/javascript-largest-number.git
cd javascript-largest-number
```

### Run Using Node.js

```bash
node largestNumber.js
```

Or paste the code into your browser's Developer Console and execute it.

---

## 📋 Sample Output

```text
25
```

---

## 🧠 Concepts Covered

* JavaScript Functions
* Function Parameters
* Return Statement
* `Math.max()` Method
* Console Output

---

## 🔍 How It Works

1. Define a function named `largest()` that accepts three numbers.
2. Pass the numbers to `Math.max()`.
3. `Math.max()` returns the greatest value.
4. Display the result using `console.log()`.

---

## 📖 About `Math.max()`

The `Math.max()` method returns the **largest value** among the numbers provided as arguments.

Example:

```javascript
Math.max(5, 12, 8);   // 12
Math.max(-4, -2, -9); // -2
Math.max(7, 7, 3);    // 7
```

---

## ⏱️ Complexity Analysis

| Operation        | Complexity |
| ---------------- | ---------- |
| Time Complexity  | **O(1)**   |
| Space Complexity | **O(1)**   |

The program performs a constant number of operations regardless of the input values.

---

## 🔮 Future Improvements

* Accept user input dynamically
* Find the largest among multiple numbers
* Implement the logic without using `Math.max()`
* Compare numbers using conditional statements
* Build a simple web interface for user interaction

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

* How to create reusable functions in JavaScript
* How function parameters and return values work
* How to use the built-in `Math.max()` method
* How to display output using `console.log()`

---

## 👨‍💻 Author

**Pranay Jadhao**

Electronics & Telecommunication Engineer

Aspiring Software Engineer | JavaScript | Python | Java | SQL

---

## 📄 License

This project is open-source and available for educational and learning purposes.

