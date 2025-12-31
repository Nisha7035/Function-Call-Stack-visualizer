# Function Call Stack Visualizer (Python)

This project is a simple Python program that **visualizes how the function call stack works**.

It shows:

* When a function is entered
* When it exits
* The current stack depth
* Indentation to represent call nesting

This is helpful for beginners learning **function calls, execution flow, and stack behavior**.

---

## 📖 What This Project Does

The program uses a global variable called `stack_depth` to track how deep the function call stack is.

Three functions are defined:

* `func1()` calls `func2()`
* `func2()` calls `func3()`
* `func3()` does some work and returns

Each function:

1. Increases the stack depth when entered
2. Prints its status with indentation
3. Decreases the stack depth when exiting

---

## 🧠 Why This Is Useful

* Helps understand how Python executes nested function calls
* Makes the call stack visible in the console
* Useful for learning debugging and tracing program flow

---

## ▶️ How to Run

Make sure you have Python installed, then run:

```bash
python your_file_name.py
```

---

## 🖥️ Example Output

```
 ➡️ Entering Func1 (stack depth:1)
  ➡️ Entering Func2 (stack depth:2)
   ➡️ Entering Func3 (stack depth:3)
   Doing work in func3
   ⬅️ Exiting Func3 (stack depth:3)
  ⬅️ Exiting Func2 (stack depth:2)
 ⬅️ Exiting Func1 (stack depth:1)
```

---

## 📂 Project Structure

```
.
├── main.py
└── README.md
```

---

## 🚀 Future Improvements

* Use recursion for deeper stack visualization
* Convert stack tracking into a decorator
* Replace `print` statements with logging
* Add color formatting for better readability

---


