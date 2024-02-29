# Variety Food Truck Ordering System

## Overview
The Variety Food Truck Ordering System is a Python application designed to simulate the process of ordering food from a food truck. It features a user-friendly interface that allows customers to select items from a categorized menu, specify quantities, and review their order before finalizing. The system is built to handle multiple menu categories including Snacks, Meals, Drinks, and Desserts, each with a variety of items and prices.

## Features
- **Categorized Menu**: Customers can browse through different categories like Snacks, Meals, Drinks, and Desserts, each offering a range of items.
- **Dynamic Ordering**: Allows customers to order multiple items across different categories, specify quantities for each, and review their orders.
- **Order Review**: Displays a complete summary of the items ordered along with the total payable amount.

## How to Use
1. **Start the Program**: Run the program to initiate the ordering system. You will be greeted with a welcome message and the available menu categories.
2. **Select Menu Category**: Choose a category from which you want to order by entering the corresponding menu number.
3. **Select Items**: After choosing a category, you'll be presented with the items available. Enter the item number for what you wish to order.
4. **Specify Quantity**: For each item selected, specify the quantity you want to order.
5. **Review and Confirm**: After adding all items to your order, you can review your order and the total amount to be paid.
6. **Complete or Continue Ordering**: Decide whether to finalize your order or continue adding more items.

## Components
- **Menu Dictionary**: A nested dictionary structure that stores the entire menu, categorized into Snacks, Meals, Drinks, and Desserts, with items and prices.
- **Order List**: A list of dictionaries, where each dictionary represents an order item, including its name, price, and ordered quantity.

## Requirements
- Python 3.x

## Sample Output
            
            Welcome to the variety food truck.
            From which menu would you like to order?
            1: Snacks
            2: Meals
            ...
            Total Payable amount is XX.XX

## Limitations
- The current version does not support order modification or cancellation after an item has been added.
- The system operates in a linear fashion, requiring the user to follow the step-by-step process without shortcuts.

## Future Enhancements
- Implementing a GUI for a more intuitive user experience.
- Adding features to modify or cancel items from the order list before finalizing.
- Integrating payment processing functionalities for complete order processing.

## Conclusion
This Python-based ordering system offers a streamlined process for placing orders at a food truck, with a focus on ease of use and flexibility in order selection. Future updates aim to enhance user interaction and order processing capabilities.
