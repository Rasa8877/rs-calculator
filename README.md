# RS Calculator

**RS Calculator** is a simple and beginner-friendly calculator library for Python.
Perfect for new coders learning how to build and use Python modules!

## ✨ Features

* Easy-to-use `calculate()` function
* Accepts full expressions like `"2 + 3 * (4 - 1)"`
* Supports common math operators: `+`, `-`, `*`, `x`, `/`, `//`, `%`, `**`, `^`
* Handles parentheses and multiple operators
* Handles division by zero and invalid input safely
* Beginner-friendly `show_help()` for quick guidance
* Supports alias import as `import rs_calculator as rsc` for convenience

## 🚀 Installation

```bash
pip install rs-calculator
```

## 🧮 Usage

```python
import rs_calculator as rsc

# Simple math
print(rsc.calculate("2 + 3 * 4"))       # 14
print(rsc.calculate("10 / (2 + 3)"))    # 2.0
print(rsc.calculate("5 ^ 2 + 10"))      # 35

# Division by zero
print(rsc.calculate("10 / 0"))          # Error: Division by zero

# Help message
rsc.show_help()
```

## 📚 Supported Operators

| Symbol    | Meaning        |
| --------- | -------------- |
| `+`       | Addition       |
| `-`       | Subtraction    |
| `*`, `x`  | Multiplication |
| `/`       | Division       |
| `//`      | Floor Division |
| `%`       | Modulo         |
| `**`, `^` | Power          |
| `()`      | Grouping       |

## 🔒 Safety

The `calculate()` function uses safe evaluation.
It only accepts numbers, operators, parentheses, and spaces.
Any expression containing unsafe characters will be rejected.

## 🛠️ License

MIT License

## 📬 Contact

GitHub: [https://github.com/Rasa8877/rs-calculator](https://github.com/Rasa8877/rs-calculator)
Email: [letperhut@gmail.com](mailto:letperhut@gmail.com)