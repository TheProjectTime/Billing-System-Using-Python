# Billing System (OOP-Based)

## 📌 Project Description

The **Billing System** is a simple Python application developed using **Object-Oriented Programming (OOP)** concepts.

The system allows users to add products with their name, price, and quantity. It calculates the subtotal, tax, and final bill, and displays the bill in a clear tabular format.

## ✨ Features

* Add multiple products
* Store product name, price, and quantity
* Calculate total price for each product
* Calculate subtotal
* Calculate tax
* Calculate final/Grand Total
* Display the final bill in tabular format
* Input validation for price and quantity

## 🛠️ Technologies Used

* **Python**
* **Object-Oriented Programming (OOP)**
* Classes and Objects
* Functions/Methods
* Loops and Conditional Statements

## 📂 Project Structure

```text
Billing-System/
│
├── billing_system.py
└── README.md
```

## 🧱 Classes Used

### 1. Product Class

The `Product` class stores information about each product.

**Attributes:**

* `name` → Name of the product
* `price` → Price of the product
* `quantity` → Quantity purchased

It also contains a method to calculate the total price:

```python
price × quantity
```

### 2. Bill Class

The `Bill` class manages all products and performs billing calculations.

**Functions include:**

* Add products
* Calculate subtotal
* Calculate tax
* Calculate final total
* Display the final bill

The default tax rate used in the program is **18%**.

## ▶️ How to Run

### 1. Install Python

Make sure Python is installed on your computer.

### 2. Save the Code

Save the Python program as:

```text
billing_system.py
```

### 3. Run the Program

Open a terminal in the project folder and run:

```bash
python billing_system.py
```

## 📋 Program Menu

The program provides the following options:

```text
===== BILLING SYSTEM =====

1. Add Product
2. Generate Bill
3. Exit
```

### Add Product

Enter:

* Product name
* Product price
* Quantity

The product is added to the current bill.

### Generate Bill

The system displays all added products in a table along with:

* Product price
* Quantity
* Product total
* Subtotal
* Tax
* Grand Total

### Exit

Closes the billing system.

## 🧮 Billing Calculation

The calculations are performed as follows:

```text
Product Total = Price × Quantity

Subtotal = Sum of all Product Totals

Tax = Subtotal × 18 / 100

Grand Total = Subtotal + Tax
```

## 📊 Example

```text
=================================================================
                         FINAL BILL
=================================================================
Product                     Price    Quantity          Total
-----------------------------------------------------------------
Laptop                   50000.00           1       50000.00
Mouse                     1000.00           2        2000.00
-----------------------------------------------------------------
                                      Subtotal : ₹52000.00
                                       Tax (18%) : ₹9360.00
                                    Grand Total : ₹61360.00
=================================================================
                 Thank you for shopping!
=================================================================
```

## 🎯 Objective

The objective of this project is to demonstrate the use of **Object-Oriented Programming in Python** by creating a simple billing system using classes, objects, methods, and basic calculations.

## 👨‍💻 Author

**Anurag Kumar Rana**
