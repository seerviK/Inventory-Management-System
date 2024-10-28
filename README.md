# 🏥 Medical Inventory Management System

Welcome to the **Medical Inventory Management System**, a streamlined solution for managing inventory in medical environments such as hospitals, pharmacies, and clinics. This system offers essential inventory control features along with a shopping cart feature, allowing users to manage products, keep track of quantities, and generate bills for items in the cart.

## 🌟 Features

### Inventory Management
- **Add Items**: Add new items to the inventory with details like ID, name, quantity, and price.
- **Remove Items**: Remove items by name from the inventory with error handling for items not found.
- **Search for Items**: Quickly search for items by name and retrieve details such as ID, quantity, and price.
- **Update Items**: Update quantity and price for existing items in the inventory.
- **Display Inventory**: Display a detailed view of all items, including total price and individual item costs.

### Customer Cart Management
- **Add to Cart**: Add items from inventory to a shopping cart with specified quantity. The system will automatically reduce the inventory stock.
- **Restock Items**: Auto-restocks an item if requested quantity exceeds available stock.
- **Remove from Cart**: Remove items from the cart and return them back to the inventory.
- **View Cart**: Display all items in the cart with a breakdown of costs.
- **Generate Bill**: Summarizes the total price of items in the cart, formatted in a customer-friendly bill.

🖥️ Getting Started
Prerequisites
- C Compiler: You need a GCC-compatible C compiler to compile and run the project.
- Terminal: A terminal or command prompt to execute the program.

🛠 Code Overview
*Inventory Management Functions
 - addItem: Adds a new item to the inventory.
 - removeItem: Removes an item by name.
 - searchItem: Searches for an item and displays details.
 - updateItem: Updates quantity and price for an item.
 - displayInventory: Displays all items in the inventory with a total price summary.
*Cart Management Functions
 - addToCart: Adds items from inventory to cart with specified quantity.
 - removeFromCart: Removes an item from the cart, returning it to inventory.
 - displayCart: Shows all items in the cart with total cost.
 - generateBill: Provides a final bill for all items in the cart.
   
🛡️ Error Handling & Edge Cases
 - Insufficient Stock: Alerts if stock is insufficient, with an option to auto-restock.
 - Memory Allocation Failures: Notifies if memory allocation for any node fails.
 - Inventory Search Failure: Displays a message if an item is not found in inventory or cart.

📜 Sample Output

*******************************************
*  -------------------------------------  *
* | Medical Inventory Management System | *
*  -------------------------------------  *
*    1. Add Item to Inventory             *
*    2. Remove Item from Inventory        *
*    3. Search for an Item                *
*    4. Update Item Information           *
*    5. Display Inventory                 *
*       ----------------------------      *
*      |      Customer's Cart       |     *
*      |    6. Add Item to Cart     |     *
*      |7. Remove item from the cart|     *
*      |     8. Display cart        |     *
*      |    9. Generate Bill        |     *
*       ----------------------------      *
*    10. Exit                             *
*******************************************
Enter your choice:

🔧 Future Improvements
 - Implement a user login system with different roles (admin, customer).
 - Add graphical user interface (GUI) for an enhanced user experience.
 - Integrate database support for persistent data storage.
