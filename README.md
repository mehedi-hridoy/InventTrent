# InventTrent - Where Inventory Meets Intelligence

![Project Output](/Output.png)

## Introduction

InventTrent is an intelligent inventory management system that I developed as my final project for the "Object Oriented Programming II" course at Daffodil International University. My name is Mehedi Hasan Hridoy, and this project aims to streamline the inventory management process, reduce manual errors, and provide insightful data to help businesses maintain optimal stock levels.

## Project Objectives

1. **Automate Inventory Management**: To develop a system that automates the process of tracking inventory levels, updating stock, and generating reports.
2. **Implement Low Stock Alerts**: To provide timely alerts for low stock items, ensuring businesses can replenish inventory before it impacts sales.
3. **Facilitate Easy Inventory Access**: To create a user-friendly interface that allows users to easily add, update, delete, and search for inventory items.
4. **Ensure Data Integrity and Security**: To maintain accurate inventory records and secure sensitive data such as login credentials.

## Project Description

InventTrent is designed to manage product details, track stock levels, and generate comprehensive reports. The system allows users to:

- Add new inventory items
- Update existing stock
- Delete items
- Search for items by ID or name
- Display all inventory items
- Receive low stock alerts
- Generate a summary report of the inventory

## Project Features

1. **Add Item**: Add new inventory items with details such as item ID, name, stock, unit, price, supplier, and low stock threshold.
2. **Update Stock**: Update the stock quantity of an existing inventory item.
3. **Delete Item**: Remove an item from the inventory.
4. **Search Item**: Search for inventory items by ID or name.
5. **Display Inventory**: Display the list of all inventory items with their details.
6. **Low Stock Alerts**: Notify the admin of items that have fallen below the specified low stock threshold.
7. **Generate Inventory Summary**: Generate a summary report of the inventory, including the total value of all items.
8. **User Authentication**: Secure login system to ensure that only authorized users can access the inventory management features.

## How the Project Addresses OOP Concepts

InventTrent leverages key object-oriented programming (OOP) concepts:

- **Classes and Objects**: Uses classes such as `Product`, `InventoryItem`, `Inventory`, and `User` to represent different entities and their interactions.
- **Inheritance**: `InventoryItem` class inherits from the `Product` abstract base class.
- **Encapsulation**: Data within each class is encapsulated, with attributes and methods that operate on the data, providing a clear interface for interaction.
- **Polymorphism**: Abstract methods in the `Product` class allow for polymorphism, enabling different item types to implement their version of `calculate_item_amount`.
- **Abstraction**: The `Product` class is an abstract base class that defines the structure for derived classes without implementing all its methods.

## Installation and Usage

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/inventTrent.git
    cd inventTrent
    ```

2. **Install dependencies**:
    Ensure you have `openpyxl` and `schedule` installed:
    ```sh
    pip install openpyxl schedule
    ```

3. **Run the application**:
    ```sh
    python main.py
    ```

## Future Enhancements

- Implementing a graphical user interface (GUI) for more user-friendly interactions.
- Adding more detailed reports and analytics.
- Integrating with other business management systems.
- Enhancing security features for more robust user authentication.

## Author

**Mehedi Hasan Hridoy**  
Department of Computer Science and Engineering  
Daffodil International University

## Conclusion

InventTrent successfully addresses the key challenges in inventory management by automating processes, providing real-time alerts, and maintaining accurate records. The project is modular and scalable, ensuring ease of maintenance and future enhancements, thereby supporting better decision-making and operational efficiency for businesses.
