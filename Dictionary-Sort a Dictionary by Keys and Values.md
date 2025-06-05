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

```python

d={'one': 1,'two': 2,'three': 3,'four': 4,'five': 5}

by_keys = dict(sorted(d.items()))
by_values = dict(sorted(d.items(), key=lambda item: item[1]))

print("Original:", d)
print("\nSorted by keys:", by_keys)
print("\nSorted by values:", by_values)

```

## Sample Output

![image](https://github.com/user-attachments/assets/3f11e20d-89c9-4cd0-bda9-a81a28b7e7f6)

## Result

Thus implemented the python program to preform sorting in dictionaries.
