# Calculator
# 🧮 Simple Calculator Using Python

A simple desktop calculator application developed using **Python and Tkinter**. The application provides a graphical user interface for performing basic arithmetic operations such as addition, subtraction, multiplication, and division.

## 📌 Project Overview

This project is a beginner-friendly **GUI Calculator** built with Python's built-in **Tkinter** library.

The calculator allows users to enter mathematical expressions using buttons and displays the calculated result. It also handles invalid expressions and errors such as division by zero.

## ✨ Features

* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division
* 🔢 Numeric input from 0–9
* 🔸 Decimal number support
* 🟰 Expression evaluation
* 🔄 Reset / Clear functionality
* ⚠️ Basic error handling
* 🖥️ Simple graphical user interface
* 📐 Fixed-size calculator window

## 🛠️ Technologies Used

| Technology  | Purpose                            |
| ----------- | ---------------------------------- |
| **Python**  | Core programming language          |
| **Tkinter** | GUI development                    |
| **eval()**  | Mathematical expression evaluation |


## ⚙️ Requirements

* Python 3.x
* Tkinter

Tkinter is included with most standard Python installations.

Check your Python version:

```bash
python --version
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/simple-calculator.git
```

### 2. Navigate to the Project Folder

```bash
cd simple-calculator
```

### 3. Run the Application

```bash
python calculator.py
```

The calculator window will open on your desktop.

## 🎮 How to Use

1. Launch the application.
2. Enter numbers using the calculator buttons.
3. Select an arithmetic operator.
4. Enter the next number.
5. Click `=` to calculate the result.
6. Use `RESET / C` to clear the current expression.

### Example

```text
10 + 5
```

Result:

```text
15
```

Another example:

```text
20 / 4
```

Result:

```text
5.0
```

## 🔧 Project Structure

```text
Simple-Calculator/
│
├── calculator.py
├── README.md
└── screenshots/
    └── calculator.png
```

## 🧠 Python Concepts Used

This project demonstrates practical use of:

* Variables
* Functions
* Global variables
* Conditional statements
* Exception handling
* Lambda functions
* String manipulation
* GUI programming
* Tkinter widgets
* Grid layout management
* Event-driven programming

## 🔍 Main Functions

### `press(num)`

Adds the selected number or operator to the current mathematical expression.

### `equalpress()`

Evaluates the entered mathematical expression and displays the result.

### `clear()`

Clears the current expression and resets the calculator display.

## ⚠️ Error Handling

The application uses exception handling to prevent the program from crashing when an invalid mathematical expression is entered.

For example:

```text
10 / 0
```

will display:

```text
error
```

instead of terminating the application.

## 🔮 Future Enhancements

Possible improvements include:

* [ ] Backspace button
* [ ] Keyboard input support
* [ ] Calculation history
* [ ] Square root and percentage operations
* [ ] Scientific calculator functions
* [ ] Dark mode
* [ ] Improved modern UI
* [ ] Better input validation
* [ ] Parentheses support

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Developing desktop applications using Python
* Creating graphical user interfaces with Tkinter
* Handling button events
* Working with functions and variables
* Implementing basic error handling
* Designing a simple user interface
* Understanding event-driven programming

## 👩‍💻 Author

**Asmitha V**

**B.Tech – Information Technology**

Interested in **Python, Web Development, Data Science, UI/UX Design, and Software Development**.

## 📄 License

This project is developed for **educational and learning purposes**.

---

⭐ If you find this project useful, consider giving the repository a star!
