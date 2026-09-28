# Day-111-Find-Index
# Python Day 111 - Find Index of an Element

This program finds the position of an element in a list using the `index()` method.

## Example

List:

```text
[10, 20, 30, 40, 50]
```

Element:

```text
30
```

Output:

```text
Position of 30 = 2
```

## Concepts Used

* List
* `index()` method
* Variables
* List indexing
* Finding the position of an element

## How It Works

1. A list of numbers is created.
2. The number whose position needs to be found is stored in a variable.
3. The `index()` method searches for that number in the list.
4. The position of the number is stored in `position`.
5. The position is displayed.

Python list indexing starts from `0`.

## Python Code

```python
numbers = [10, 20, 30, 40, 50]

print("List:", numbers)

number = 30

position = numbers.index(number)

print("Position of", number, "=", position)
```

## Output

```text
List: [10, 20, 30, 40, 50]
Position of 30 = 2
```

## Goal

The goal of this project is to understand the `index()` method and learn how to find the position of an element in a Python list.
