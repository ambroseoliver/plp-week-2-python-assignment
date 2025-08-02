# 📋 Python List Operations Practice

This is a simple Python program that demonstrates common **list operations**, including appending, inserting, extending, removing, sorting, and searching for values.

Great for beginners looking to practice working with Python lists! 🐍

---

## 🔧 What This Program Does

1. **Creates an empty list** called `my_list`
2. **Appends** values: `10, 20, 30, 40`
3. **Inserts** the value `15` at the second position (index `1`)
4. **Extends** the list with another list: `[50, 60, 70]`
5. **Removes** the last element from the list
6. **Sorts** the list in ascending order
7. **Finds the index** of the value `30` and prints it

---

## 🧠 Python Concepts Practiced

- `append()` – Add single elements
- `insert()` – Insert at a specific index
- `extend()` – Add multiple items
- `remove()` – Delete by value
- `sort()` – Order the list
- `index()` – Find position of an item

---

## 💻 Code Preview

```python
# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at position 1
my_list.insert(1, 15)

# Extend with another list
my_list.extend([50, 60, 70])

# Remove the last element
my_list.remove(my_list[-1])

# Sort in ascending order
my_list.sort()

# Find and print index of 30
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
