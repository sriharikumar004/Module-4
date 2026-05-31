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
dictionary = {
    'banana': 'yellow',
    'apple': 'red',
    'grape': 'green',
    'orange': 'orange'
}
sorted_keys = dict(sorted(dictionary.items()))
sorted_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))
print("Original Dictionary:")
print(dictionary)
print("\nDictionary Sorted by Keys:")
print(sorted_keys)
print("\nDictionary Sorted by Values:")
print(sorted_values)
```
## Sample Output
<img width="813" height="396" alt="image" src="https://github.com/user-attachments/assets/216bf04a-a426-4a25-b64b-5e687fc5c55c" />
## Result
the program is executed successfully.

