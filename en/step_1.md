Checking whether an item is in a list is easy in Python, you can use the `in` keyword.

```python
search_item = "paper"
items = ["rock", "paper", "scissors"]

if search_item in items:
    print("Found it!")
```

If the item is in the list, the message "Found it!" will be printed.

You can also use a loop to continue executing some code until an item is in a given list. This is useful for validating input. Here we are using the opposite, `not in`.

```python
direction = ""
while direction not in ["N", "S", "E", "W"]:
    direction = input("Please enter a direction (N, S, E or W): ")
print(direction)
```

This loop will keep asking for a new direction until the user enters one that is in the list. Once they have entered a direction in the list, that direction will be printed.
