Checking whether an item is in a list is easy in Python: you can use the `in` keyword like in the example here. If the item is in the list, the message "Found it!" will be printed.

```python
search_item = "paper"
items = ["rock", "paper", "scissors"]

if search_item in items:
    print("Found it!")
```

You can also use a loop to continue executing a bit of code until an item is in a given list. This is useful for validating input. Below we are using the opposite of the `in` keyword: `not in`.

```python
direction = ""
while direction not in ["N", "S", "E", "W"]:
    direction = input("Please enter a direction (N, S, E or W): ")
print(direction)
```

This loop will keep asking for a direction until the user enters one that is in the list. Once they have entered one of the directions given as options, that direction will be printed.
