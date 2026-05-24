# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d = {'b': 'banana', 'a': 'apple', 'd': 'date', 'c': 'cherry'}

print("Original Dictionary =", d)

# Sorting by keys
sorted_keys = dict(sorted(d.items()))
print("Dictionary sorted by keys =", sorted_keys)

# Sorting by values
sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Dictionary sorted by values =", sorted_values)
```
## Sample Output
<img width="916" height="192" alt="image" src="https://github.com/user-attachments/assets/0703572f-f5c6-4b6c-87ef-10711012bb2c" />

## Result
Thus, the Python program to sort a dictionary by keys and values was executed successfully and the output was verified.
