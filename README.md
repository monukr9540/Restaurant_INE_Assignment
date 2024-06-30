# Restaurant_INE_Assignment
Objective
This web application allows customers to browse the restaurant menu and place orders. It includes two user roles: customers and restaurant staff. Customers can browse the menu, add items to their cart, and place orders. Restaurant staff can view incoming orders and list new items in their menu.

Technologies Used
Front-end: React
Back-end: Node.js/Express.js
Database: MongoDB
Authentication: JWT

#Customer Interface

Login Page:
Customers can log in using their basic details.

Menu Browsing:
Displays a list of menu items with details such as name, description, price, and image.

Menu items are categorized (e.g., appetizers, main courses, desserts, drinks).

Order Placement:
Customers can select their food item and add items to their cart.
Customers can review their cart, adjust quantities, and remove items.

Order Viewing:
Displays current submitted order details.


#Restaurant Staff Interface

Order Management:

Displays a list of incoming orders with details such as order items, and total amount.

Menu List Updation:
Admin can update new food items in their menu list.

#Authentication

User Roles:
Authentication is implemented for both customers and staff.
Only authenticated staff can access order management features.
