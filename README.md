# HS-CoffeeMachine


Coffee Machine Simulator

This Java project simulates a coffee machine. It can prepare different types of coffee (espresso, latte, cappuccino), keep track of the available ingredients (water, milk, coffee beans), and handle transactions.

Features

Buy Coffee: You can choose to buy an espresso, latte, or cappuccino. The program checks if there are enough ingredients to make your selection. If not, it will inform you what ingredient is missing.
Fill Machine: You can refill the ingredients in the machine - water, milk, coffee beans, and disposable cups.
Take Money: You can take all the money out of the machine.
Check Remaining Ingredients: You can check the remaining quantities of water, milk, coffee beans, and disposable cups, as well as the amount of money in the machine.
Usage

Run the main method in the CoffeeMachine class. The program will prompt you to choose an action: buy, fill, take, remaining, or exit. Depending on your choice, you can interact with the coffee machine as described in the features.

Code Structure

The CoffeeMachine class contains all the logic for the coffee machine operations. It has methods for each action (getActionBuy, fillMachine, takeMoney, sellEspresso, sellLatte, sellCappuccino, printDetails) and maintains the state of the machine (amount of water, milk, coffee beans, cups, and money).

Note

This is a console-based program and all interactions happen in the console/terminal.
