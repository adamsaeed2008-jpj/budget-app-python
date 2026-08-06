#  Budget App (Python)

## Overview
This project was developed as part of the FreeCodeCamp Scientific Computing with Python certification to demonstrate object-oriented programming, financial transaction management, and formatted text output.

The application allows users to manage different budget categories, record deposits and withdrawals, transfer funds between categories, calculate balances, and generate a text-based spending chart that visualizes the percentage of spending for each category.

---

## Features

- Create multiple budget categories
- Deposit funds with optional descriptions
- Withdraw funds with balance validation
- Transfer money between categories
- Check available balances
- View formatted transaction history
- Generate a spending percentage chart
- Object-Oriented Programming (OOP) implementation

---

## Technologies Used

- Python 3
- Object-Oriented Programming (Classes & Methods)
- Lists
- Dictionaries
- String Formatting

---

## Example

```python
food = Category("Food")
food.deposit(1000, "Initial Deposit")
food.withdraw(25.50, "Groceries")

clothing = Category("Clothing")
food.transfer(100, clothing)

print(food)
print(create_spend_chart([food, clothing]))
```

---

## Sample Output

```
*************Food*************
Initial Deposit       1000.00
Groceries              -25.50
Transfer to Clothing  -100.00
Total: 874.50
```

```
Percentage spent by category
100|
 90|
 80|
 70|
 60| o
 50| o
 40| o
 30| o
 20| o  o
 10| o  o  o
  0| o  o  o
    ----------
     F  C
     o  l
     o  o
     d  t
        h
        i
        n
        g
```

---

## Project Structure

```
budget-app-python/
│
├── budget.py
└── README.md
```

---

## Skills Demonstrated

- Python Programming
- Object-Oriented Programming (OOP)
- Class Design
- Financial Calculations
- Data Structures
- String Manipulation
- Problem Solving
- Text-Based Data Visualization

---

## Learning Outcomes

Through this project, I practiced designing reusable Python classes, managing financial transactions, validating user actions, and creating formatted text-based visualizations while strengthening my understanding of object-oriented programming principles.
