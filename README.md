# Interactive Ordering System

## Overview

This project is an interactive ordering system for a food truck menu, designed as part of a Python assignment. The system allows users to select items from a menu, place an order, and receive a formatted receipt with the total price.

## Features

- Display a menu with various food categories and items.
- Allow users to select items from the menu.
- Validate user input to ensure correct item selection and quantities.
- Calculate and display the total price of the order.
- Print a formatted receipt for the user.

## Menu Structure

The menu is organized into categories with various items:

- **Snacks**
  - Chips
  - Nachos

- **Meals**
  - Pizza
  - Burger

- **Drinks**
  - Soda
  - Tea
  - Coffee

- **Desserts**
  - Cheesecake

## Usage

To use the interactive ordering system:

1. Open the terminal.
2. Navigate to the directory containing the Python script.
3. Run the script using Python:

   ```sh
   python your_script_name.py

4. Follow the prompts to select menu items and specify quantities.
5. Review the receipt and total price displayed on the screen.

## Requirements

- Python 3.x
- Terminal or command-line interface

## How It Works

1. **Initialization:** An empty order list is created.
2. **Menu Selection:** Users are prompted to select a menu item. Input is validated to ensure it's a number and exists in the menu.
3. **Quantity Input:** Users are prompted to enter a quantity. If input is invalid, the default value of 1 is used.
4. **Order Processing:** Selected items, prices, and quantities are added to the order list.
5. **Receipt Generation:** The order list is processed to generate and display a formatted receipt with total price.

## Example

*Welcome to the Food Truck!*

*Menu:
1. *Snacks*
   - *Chips ($2.00)*
   - *Nachos ($3.50)*
2. *Meals*
   - *Pizza ($8.00)*
   - *Burger ($5.00)*
3. *Drinks*
   - *Soda ($1.50)*
   - *Tea ($2.00)*
   - *Coffee ($2.50)*
4. *Desserts*
   - *Cheesecake ($4.00)*

*Please enter the number of the category you want to order from:*
> *2*

*Please enter the number of the item you want to order:*
> *1*

*Please enter the quantity:*
> *2*

*Your order:*
- *Pizza x2*

*Total Price: $16.00*

## Acknowledgments

- Special thanks ChatGPT for assisting with the code improvements, README formatting, and providing guidance throught the development process. 
- The code structure and example formats were influenced by various sources, including educational forums and resources.
- Developed as part of assigment for AI Boot Camp
- Special thanks to Firas Obeid for the guidance and support

## Source Attribution

- **Code Sources:** All code was developed as part of the assignment unless otherwise specified. External code snippets or resources used are acknowledged in the Acknowledgments section.
- **Assistance:** Acknowledges the use of ChatGPT for general assistance without implying direct help from instructors.

## Contact

For questions or feedback, please contact lesliebarrera.d@gmail.com

