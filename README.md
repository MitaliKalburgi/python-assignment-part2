# python-assignment-part2
 
## Restaurant Menu & Order Management System 

This project is part of a Python assignment focused on using core data structures like **lists, dictionaries, and nested structures** to build a simple Restaurant Order Management System.

---

## 📌 Features Implemented

### ✅ Task 1 — Explore the Menu
- Displayed menu grouped by categories (Starters, Mains, Desserts)
- Calculated:
  - Total number of items
  - Number of available items
  - Most expensive item
  - Items priced under ₹150

---

### ✅ Task 2 — Cart Operations
- Implemented cart as a list of dictionaries
- Features:
  - Add items (with availability check)
  - Prevent duplicate entries (update quantity instead)
  - Remove items from cart
  - Update item quantity
- Simulated a full order flow
- Generated final order summary with:
  - Subtotal
  - GST (5%)
  - Total payable

---

### ✅ Task 3 — Inventory Tracker (Deep Copy)
- Used `copy.deepcopy()` to create a backup of inventory
- Demonstrated deep copy behavior:
  - Changes in original inventory do not affect backup
- Simulated order fulfilment:
  - Deducted stock based on cart
  - Handled insufficient stock cases
- Generated reorder alerts for low stock items

---

### ✅ Task 4 — Daily Sales Log Analysis
- Calculated total revenue per day
- Identified best-selling day
- Found most ordered item across all orders
- Added new day data dynamically
- Recomputed updated statistics
- Printed all orders using `enumerate()` in a structured format

---

## 📁 File Structure
