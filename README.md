# GenAI_Assignment_2# Python Order Processing and Sales Analysis

## Project Description

This project is a Python-based assignment implemented in a **Jupyter Notebook (.ipynb)** using **VS Code**.
The notebook contains multiple tasks that simulate **basic order processing and sales analysis systems** commonly used in retail or e-commerce environments.

The assignment demonstrates practical usage of **Python fundamentals** such as loops, conditional statements, lists, and input validation.

---

# Project Structure

The notebook contains the following tasks:

### Task 1: Order Discount and Tax Calculator

This program accepts an order amount from the user and calculates the final payable amount after applying discounts and tax.

**Features**

* Validates numeric input
* Applies discount based on order value
* Calculates 5% tax
* Displays subtotal and final amount

**Discount Rules**

| Order Amount   | Discount    |
| -------------- | ----------- |
| 2000 or more   | 15%         |
| 1500 – 1999    | 10%         |
| 1000 – 1499    | 7%          |
| Less than 1000 | No discount |

---

### Task 2: Order List Processing

This task processes a predefined list of orders and calculates revenue after discounts.

**Features**

* Iterates through multiple order values
* Applies appropriate discount
* Displays discount percentage for each order
* Calculates total revenue
* Counts number of discounted orders

Example order list:

```
orders = [1200, 2500, 800, 1750, 3000]
```

---

### Task 3: Menu-Driven Order Management System

This task implements a simple **interactive menu system**.

Users can:

1. Add new order amounts
2. View all processed orders
3. Calculate total revenue after discounts
4. Exit the program

**Features**

* Dynamic order storage using lists
* Input validation
* Real-time discount calculations
* Revenue summary generation

---

### Task 4: Daily Sales Analyzer

This program analyzes daily sales values and calculates total revenue while handling special cases.

Example dataset:

```
daily = [200, 150, 0, 400, 50, -1, 300]
```

**Logic**

| Value           | Meaning                        |
| --------------- | ------------------------------ |
| Positive number | Sales amount                   |
| 0               | No sales on that day           |
| -1              | Corrupted data (program stops) |

**Features**

* Displays daily sales report
* Maintains running total
* Detects corrupted data
* Stops processing when invalid data appears

---

# Technologies Used

* Python
* Jupyter Notebook (.ipynb)
* Visual Studio Code

---

# How to Run the Project

Since the assignment is written in a **Jupyter Notebook**, follow these steps:

1. Open **Visual Studio Code**
2. Open the `.ipynb` notebook file
3. Run each cell sequentially

You can run cells by:

* Clicking **Run Cell ▶**
* Pressing **Shift + Enter**

---

# Learning Outcomes

Through this assignment, the following Python concepts are practiced:

* Lists and list operations
* Conditional statements (`if`, `elif`, `else`)
* Loops (`for`, `while`)
* Input validation
* Data processing
* Basic program structuring

---

# Author

Deepna Maria Jimson
Engineer | Web Developer
