This project is a simple Inventory Management System implemented in Python. It allows users to manage an inventory of items by performing actions such as adding, removing, updating quantities, and displaying the current inventory.

**Features**
Add Items: Allows users to add new items to the inventory with a specified quantity.
Remove Items: Users can remove items from the inventory.
Update Item Quantity: Users can update the quantity of an existing item (increase or decrease).
Show Inventory: Displays all items in the inventory with their current quantities.
User Interaction: Menu-based interface that lets users choose the desired action.

**Requirements**
Python 3.x or later.

1. Clone the Repository
Clone this repository to your local machine:
Copy code
git clone https://github.com/yourusername/inventory-management.git

2. Run the Program
Navigate to the project folder and run the Python script:
Copy code
cd inventory-management
python inventory.py

3. Menu Options
Once the program is running, a menu will be displayed with the following options:

Add Item: Add a new item to the inventory.
Remove Item: Remove an item from the inventory.
Update Item Quantity: Update the quantity of an existing item (you can add or subtract the quantity).
Show Inventory: Display the current list of items and their quantities.
Exit: Exit the program.
4. Interacting with the Program
You will be prompted to enter the necessary information such as item name, quantity, etc. Based on the selected option, the system will carry out the corresponding operation.

For example:

To add a new item, you will be asked for the item's name and quantity.
To remove an item, you will provide the item's name, and it will be deleted from the inventory.
To update an item’s quantity, you will specify the change in quantity (use negative numbers to decrease the quantity).


**Code Explanation**
add_item(): This function adds a new item to the inventory with the provided name and quantity.
remove_item(): This function removes an item from the inventory based on the item name.
update_item_quantity(): This function allows users to update the quantity of an existing item in the inventory.
show_inventory(): This function prints out the current state of the inventory, listing all items and their quantities.
main(): The main function provides a menu for users to interact with the program and make their selections.

**Customization**
You can easily modify the system to suit your needs:

Change Item Names: Modify the item names to match what you are managing.
Add More Functions: You can extend the system by adding more features like searching for items or saving the inventory to a file.
**License**
This project is open-source and available under the MIT License. Feel free to fork, modify, and contribute!
