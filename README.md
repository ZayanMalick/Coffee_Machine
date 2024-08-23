# Coffee Machine Project:

## Project Overview:

This project simulates a simple coffee machine using Python. The program allows users to choose from a menu of drinks, processes payments, and checks if the machine has sufficient resources to make the selected drink. 

## The project is divided into four Python files:

### main.py: 
    The main program that controls the coffee machine.

### coffee_maker.py:
    Manages the resources of the coffee machine.

### menu.py: 
    Contains the menu and drinks available in the coffee machine.

### money_machine.py: 
    Handles the money transactions and calculations.

## Files:

1. main.py
   
          This is the main entry point of the project. It imports the Menu, CoffeeMaker, and MoneyMachine classes and uses them to create an interactive coffee machine experience.

3. coffee_maker.py
   
       This file contains the CoffeeMaker class, which models the machine that makes the coffee. It manages the resources (water, milk, coffee) and checks if there are sufficient resources to make the selected drink.

4. menu.py
   
        This file defines the Menu and MenuItem classes. The Menu class holds the available drink options, while the MenuItem class models each drink with its ingredients and cost.

5. money_machine.py

        This file contains the MoneyMachine class, which handles all money-related operations. It processes the coins inserted by the user, checks if the payment is sufficient, and calculates the change.

## How to Run the Project:

Ensure you have Python installed on your machine.

Clone this repository to your local machine.

Navigate to the project directory.

## Run the main.py file using the command:
        python main.py

## Follow the on-screen prompts to interact with the coffee machine:

## Project Features:

### Drink Selection: 
    Choose from a menu of drinks including Latte, Espresso, and Cappuccino.

### Resource Management: 
    The coffee machine tracks and reports its resources (water, milk, coffee) and checks if it has enough to make the selected drink.

### Payment Handling:
    The machine calculates the cost of the selected drink, processes coin payments, and provides change if needed.

## License:
This project is licensed under the MIT License.
