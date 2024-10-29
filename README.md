# 🏥 Medical Inventory Management System using Data Structures (Queue, Linked List)

Welcome to the **Medical Inventory Management System**, I have created this system suing core C language to implement the use of data structures like queue and linked list. Adding an element, deleting and updating is performed in the above project
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

![image](https://github.com/user-attachments/assets/c220f14a-aa1c-4fb5-9614-aac7a51e4b36)

![image](https://github.com/user-attachments/assets/6270abb4-85eb-43a4-96b6-a1bac320c4de)


🔧 Future Improvements
 - Implement a user login system with different roles (admin, customer).
 - Add graphical user interface (GUI) for an enhanced user experience.
 - Integrate database support for persistent data storage.
