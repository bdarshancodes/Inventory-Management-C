# Inventory-Management-C

A simple **C program** that simulates an inventory system for managing orders of **paper, ribbon, and labels**.
The program uses a `switch` case menu to take input from the user and update the stock levels accordingly.

---

## Features

* Manage three types of inventory items:

  * Paper
  * Ribbon
  * Labels
* Update stock by placing an order.
* Menu-driven input using switch case.
* Handles invalid choices gracefully.

---

## How It Works

1. The user is asked to press a key:

   * **'B' or 'C'** → Ribbon
   * **'E', 'F', or 'D'** → Label
   * **'A' or 'X'** → Paper
2. The program prompts the user to enter the order quantity.
3. It updates the inventory stock and displays the new total.

---

## Example Run

```
please press 'B','C' for ribbon
Please press 'E','F','D' for label
Please press 'A','X' for paper
please enter your choice..
B
enter  ribbon order value:
5
Total ribbon is :83
```

---

## Requirements

* C Compiler (e.g., GCC)

---

## Compilation & Execution

```bash
gcc inventory.c -o inventory
./inventory
```

---

## Future Improvements

* Add file storage to save inventory after program exits.
* Add stock deduction (for sales).
* Add menu loop for multiple orders.

---

## Author

Darshan B
