# Week-Two--Assignment-PLP
# Week Two Assignment – Python List Operations

## 📘 Description

This Python script demonstrates basic list manipulation techniques as part of a programming assignment. It covers operations such as appending, inserting, extending, removing, sorting, and indexing within a list.

## 🧠 Learning Objectives

- Create and modify Python lists
- Use built-in list methods like `append()`, `insert()`, `extend()`, `pop()`, `sort()`, and `index()`
- Understand how list operations affect list structure and order

## 🛠️ Features

- Initializes an empty list
- Appends multiple numeric values
- Inserts a value at a specific index
- Extends the list with another list
- Removes the last element using `pop()`
- Sorts the list in ascending order
- Finds and prints the index of a specific value

## 📄 Code Summary

```python
my_list = []
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
my_list.insert(1, 15)
my_list.extend([50, 60, 70])
my_list.pop()
my_list.sort()
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
