# day02-ecommerce-discount_python

# 🛒 Day 2 – E-commerce Discount System (Python)

This project simulates a simple **E-commerce Discount System** using Python. It calculates the final payable amount based on different discount rules depending on the total purchase value.

---

---

## 📌 Features

* Takes total purchase amount as input
* Applies discount based on predefined conditions
* Calculates final payable amount
* Displays clean and user-friendly output
* Real-world e-commerce logic implementation

---

## 💰 Discount Rules

| Purchase Amount | Discount     |
| --------------- | ------------ |
| Less than ₹500  | No Discount  |
| ₹500 – ₹999     | 10% Discount |
| ₹1000 – ₹1999   | 20% Discount |
| ₹2000 and above | 30% Discount |

---

## 🧠 Concepts Used

* Conditional Statements (`if`, `elif`, `else`)
* Comparison Operators
* Arithmetic Calculations
* Input Handling
* Basic Program Structure

---

## ⚙️ How It Works

1. User enters the total purchase amount
2. Program checks the amount range
3. Applies corresponding discount
4. Calculates final amount:

```
Final Amount = Total Amount - Discount
```

5. Displays total amount, discount applied, and final payable amount

---

## 💡 Example

### Input

```
Enter the Total Purchased:
1500
```

### Output

```
You got 20% Discount!!
Total Amount: ₹1500
Final Amount: ₹1200
```

---

## 🚀 Future Improvements

* Add input validation (negative values, invalid input)
* Improve output formatting (bill style)
* Add multiple product support
* Integrate with a billing system
* Convert into a web-based application using Flask

---

## 🙌 Author

Amrutha D N
---

⭐ If you find this useful, consider giving it a star!
