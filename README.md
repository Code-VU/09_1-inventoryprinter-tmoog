[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=10739456&assignment_repo_type=AssignmentRepo)

## Assignment
You are creating a fantasy video game. The data structure to model the player’s inventory will be a dictionary where the keys are string values describing the item in the inventory and the value is an integer value detailing how many of that item the player has. For example, the dictionary value 

`{'rope': 1, 'torch': 6, 'gold coin': 42, 'ring': 1, 'apple': 12}` 

means the player has 1 rope, 6 torches, 42 gold coins, and so on.

Write a function named `displayInventory()` that would take any possible “inventory” and display it like the following:

## Desired Output
```
Inventory:
12 apple
42 gold coin
1 rope
6 torch
1 ring
Total number of items: 62
```

## Starter Code
```python
stuff = {'rope': 1, 'torch': 6, 'gold coin': 42, 'ring': 1, 'apple': 12}

def displayInventory(inventory):
    # your code goes here


if __name__ == "__main__":
    displayInventory(stuff)
```

## Tests
When your code is ready to test, run `pytest` in the terminal.

