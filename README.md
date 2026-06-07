# 🛒 Shopping Cart — C Console Program

> A simple C console program simulating a shopping cart — enter an item, its price, and quantity to get the formatted total.

---

## 📋 Description

A beginner-friendly C program that takes an item name, unit price, and quantity as input from the user, then calculates and displays the total cost with formatted currency output.

---

## ✨ Features

- Accepts item name (string input via `fgets`)
- Accepts unit price (float) and quantity (integer)
- Calculates total cost: `price × quantity`
- Displays a clean, formatted purchase summary with currency symbol

---

## 🚀 Getting Started

### Prerequisites

- A C compiler (e.g., `gcc`)

### Compilation

```bash
gcc main.c -o main.exe
```

### Run

```bash
./main.exe
```

---

## 💻 Usage Example

```
What item would you like to buy?: Apple
What is the price for each?: 1.50
How many would you like?: 4

You have bought 4 Apple/s
The total is: $6.00
```

---

## 🗂️ File Structure

```
.
└── main.c   # Main source file
└── main.exe #executable file
└── README.md 

```

---

## 🧠 Concepts Used

| Concept | Details |
|---|---|
| `fgets()` | Reading string input safely |
| `scanf()` | Reading float and int input |
| `printf()` | Formatted console output |
| Arithmetic | Float multiplication for total cost |
| String handling | Removing trailing newline from `fgets` |

---

## ⚠️ Known Limitations

- Supports only one item per run (no cart loop)
- No input validation (e.g., negative price/quantity)
- Currency symbol is hardcoded as `$`

---

## 🛠️ Future Improvements

- [ ] Loop to add multiple items
- [ ] Running cart total
- [ ] Input validation
- [ ] Choose currency symbol at runtime

---

## 👤 Author

**Makkena Vennela**

---

