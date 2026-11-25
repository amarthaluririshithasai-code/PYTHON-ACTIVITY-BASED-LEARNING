# Project 1 – Progressive Electricity Billing System

## Description
The Progressive Electricity Billing System is a Python-based project that calculates electricity bills based on the number of units consumed. It applies different charges for different consumption slabs, adds fixed charges and a 5% surcharge, and compares the current bill with the previous month's bill to identify unusual increases.

## Objectives
- Calculate electricity charges based on consumption.
- Apply progressive slab rates.
- Calculate fixed charges and surcharges.
- Determine the final electricity bill.
- Identify unusual increases in monthly bills.

## Assumptions
- 0–100 units: ₹2 per unit.
- 101–200 units: ₹3 per unit.
- Above 200 units: ₹5 per unit.
- Fixed charge: ₹50.
- Surcharge: 5% of energy charges.
- An increase above 20% is considered unusual.

## Technologies Used
- Python 3
- Conditional Statements
- Arithmetic Operators
- Variables and User Input

## How to Run
1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Run the Python file.
4. Enter the electricity units and previous bill amount.
5. View the calculated electricity bill.

## Sample Output
```text
Enter electricity units: 80
Enter previous bill: 200

Energy Charge: Rs. 160.00
Fixed Charge: Rs. 50.00
Surcharge: Rs. 8.00
Final Electricity Bill: Rs. 218.00
Bill Status: Normal Increase
```

## Conclusion
This project demonstrates how Python can be used to calculate electricity bills using progressive slab rates, arithmetic operations, and conditional statements.
